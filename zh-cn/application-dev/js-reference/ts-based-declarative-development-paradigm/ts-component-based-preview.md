# @Preview<a name="ZH-CN_TOPIC_0000001124516048"></a>

用**@Preview**装饰的自定义组件可以在DevEco的PC预览上进行单组件预览，加载页面时，将创建并呈现**@Preview**装饰的自定义组件。

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>在单个源文件中，最多可以使用**@Preview**装饰一个自定义组件。

## 示例<a name="section2270154810523"></a>

**@Preview**的用法如下：

```
// Display only Hello Component1 on the PC preview. The content under MyComponent is displayed on the real device.
@Entry
@Component
struct MyComponent {
    build() {
        Column() {
            Row() {
                Text('Hello World!')
                    .fontSize("50lpx")
                    .fontWeight(FontWeight.Bold)
            }
            Row() {
                Component1()
            }
            Row() {
                Component2()
            }
        }
    }
}
@Preview
@Component
struct Component1 {
    build() {
        Column() {
            Row() {
                Text('Hello Component1')
                    .fontSize("50lpx")
                    .fontWeight(FontWeight.Bold)
            }
        }
    }
}

@Component
struct Component2 {
    build() {
        Column() {
            Row() {
                Text('Hello Component2')
                    .fontSize("50lpx")
                    .fontWeight(FontWeight.Bold)
            }
        }
    }
}
```

