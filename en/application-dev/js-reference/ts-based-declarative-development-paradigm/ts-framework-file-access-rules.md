# Rules for Accessing Application Code Files<a name="EN-US_TOPIC_0000001158261215"></a>

The application code files can be accessed in the following ways:

-   Use a relative path to reference the code file. For example, if the upper-level directory is  **../common/utils/utils.ets**, use  **./common/utils/utils.ets**  for the current directory.
-   Use the root path of the current module to reference the code file, for example,  **common/utils/utils.ets**.
-   Store common code files in the  **common**  directory.

## Example<a name="section14151172218568"></a>

```
import { FoodData, FoodList } from "../common/utils/utils.ets";

@Entry
@Component
struct FoodCategoryList {  
  private foodItems: FoodData[] = [    
    new FoodData("Tomato"),    
    new FoodData("Strawberry"),    
    new FoodData("Cucumber")  
  ]  
  build() {    
    Column() {      
      FoodList({ foodItems: this.foodItems })    
    }  
  }
}
```

Example for importing a code file:

```
//common/utils/utils.ets

export class FoodData {  
  name: string;  
  constructor(name: string) {    
    this.name = name;  
  }
}

@Component
export struct FoodList {  
  private foodItems: FoodData[]

  build() {    
    Column() {      
      Flex({justifyContent: FlexAlign.Center, alignItems: ItemAlign.Center}) {        
        Text('Food List')          
          .fontSize(20)      
      }      
      .width(200)      
      .height(56)      
      .backgroundColor('#FFf1f3f5')      
      List() {        
        ForEach(this.foodItems, item => {          
          ListItem() {            
            Text(item.name)              
              .fontSize(14)          
          }        
        }, item => item.toString())      
      }    
    }  
  }
}
```

