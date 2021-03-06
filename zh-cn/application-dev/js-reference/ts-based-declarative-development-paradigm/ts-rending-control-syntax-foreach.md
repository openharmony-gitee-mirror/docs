# 循环渲染<a name="ZH-CN_TOPIC_0000001110788996"></a>

开发框架提供**ForEach**组件来迭代数组，并为每个数组项创建相应的组件。**ForEach**定义如下：

```
ForEach(
    arr: any[], // Array to be iterated
    itemGenerator: (item: any) => void, // child component generator
    keyGenerator?: (item: any) => string // (optional) Unique key generator, which is recommended.
)
```

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>-   循环渲染使用ForEach从提供的数组中自动生成子组件；
>-   必须在容器组件内使用；
>-   第一个参数必须是数组：允许空数组，空数组场景下不会创建子组件。同时允许设置返回值为数组类型的函数，例如**arr.slice\(1, 3\)**，设置的函数不得改变包括数组本身在内的任何状态变量，如**Array.splice**、**Array.sort**或**Array.reverse**这些原地修改数组的函数；
>-   第二个参数用于生成子组件的lambda函数。它为给定数组项生成一个或多个子组件。单个组件和子组件列表必须括在大括号“**\{....\}**”中；
>-   可选的第三个参数是用于键值生成的匿名函数。它为给定数组项生成唯一且稳定的键值。当子项在数组中的位置更改时，子项的键值不得更改，当数组中的子项被新项替换时，被替换项的键值和新项的键值必须不同。键值生成器的功能是可选的。但是，出于性能原因，强烈建议提供，这使开发框架能够更好地识别数组更改。如单击进行数组反向时，如果没有提供键值生成器，则ForEach中的所有节点都将重建。
>-   生成的子组件必须允许在**ForEach**的父容器组件中，允许子组件生成器函数中包含**if/else**条件渲染，同时也允许**ForEach**包含在**if/else**条件渲染语句中。
>-   子项生成器函数的调用顺序不一定和数组中的数据项相同，在开发过程中不要假设子项生成器和键值生成器函数是否执行以及执行顺序。如下示例可能无法正常工作：
>    ```
>    ForEach(anArray, item => {Text(`${++counter}. item.label`)})
>    ```
>    正确的示例如下：
>    ```
>    ForEach(anArray.map((item1, index1) => { return { i: index1 + 1, data: item1 }; }), 
>            item => Text(`${item.i}. item.data.label`),
>            item => item.data.id.toString())
>    ```

## 示例<a name="section155489126613"></a>

简单类型数组示例：

```
@Entry
@Component
struct MyComponent {
    @State arr: number[] = [10, 20, 30]
    build() {
        Column() {
            Button() {
                Text('Reverse Array')
            }.onClick(() => {
                this.arr.reverse()
            })

            ForEach(this.arr,                         // Parameter 1: array to be iterated
                    (item: number) => {               // Parameter 2: item generator
                        Text(`item value: ${item}`)
                        Divider()
                    },
                    (item: number) => item.toString() // Parameter 3: unique key generator, which is optional but recommended.
            )
        }
    }
}
```

复杂类型数组示例：

```
class Month {
  year: number
  month: number
  days: Array<number>

  constructor(year, month, days) {
    this.year = year;
    this.month = month;
    this.days = days;
  }
}

@Entry
@Component
struct Calendar1 {
// simulate with 6 months
  @State calendar: Month[] = [
    new Month(2020, 1, [...Array(31).keys()]),
    new Month(2020, 2, [...Array(28).keys()]),
    new Month(2020, 3, [...Array(31).keys()]),
    new Month(2020, 4, [...Array(30).keys()]),
    new Month(2020, 5, [...Array(31).keys()]),
    new Month(2020, 6, [...Array(30).keys()]),
  ]

  build() {
    Column() {
      Button('next month')
        .onClick(() => {
          this.calendar.shift()
          this.calendar.push({
            year: 2020,
            month: 7,
            days: [...Array(31)
              .keys()]
          })
        })
      ForEach(this.calendar,
        (item: Month) => {
          Text('month:' + item.month)
            .fontSize(30)
            .padding(20)
          Grid() {
            ForEach(item.days,
              (day: number) => {
                GridItem() {
                  Text((day + 1).toString())
                    .fontSize(30)
                }
              },
              (day: number) => day.toString())
          }
          .columnsTemplate('1fr 1fr 1fr 1fr 1fr 1fr 1fr')
          .rowsGap(20)
        },
        // field is used together with year and month as the unique ID of the month.
        (item: Month) => (item.year * 12 + item.month).toString())
    }
  }
}
```

