# 子组件配置<a name="ZH-CN_TOPIC_0000001157228875"></a>

对于支持子组件配置的组件，例如容器组件，在“**\{ ... \}**”里为组件添加子组件的UI描述。**Column**、**Row**、**Stack**、**Button**、**Grid**和**List**组件都是容器组件。

以下是简单的**Column**示例：

```
Column() {
    Text('Hello')
        .fontSize(100)
    Divider()
    Text(this.myText)
        .fontSize(100)
        .fontColor(Color.Red)
}
```

可以嵌套多个子组件：

```
Column() {
    Column() {
        Button() {
            Text('+ 1')
        }.type(ButtonType.Capsule)
        .onClick(() => console.log ('+1 clicked!'))
        Image('1.jpg')
    }
    Divider()
    Column() {
        Button() {
            Text('+ 2')
        }.type(ButtonType.Capsule)
        .onClick(() => console.log ('+2 clicked!'))
        Image('2.jpg')
    }
    Divider()
    Column() {
        Button() {
            Text('+ 3')
        }.type(ButtonType.Capsule)
        .onClick(() => console.log('+3 clicked!'))
        Image('3.jpg')
    }
}.alignItems(HorizontalAlign.Center) // center align components inside Column
```

