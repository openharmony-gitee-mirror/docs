# form<a name="ZH-CN_TOPIC_0000001127284848"></a>

表单容器，支持容器内input元素的内容提交和重置。

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>从 API Version 6 开始支持。

## 权限列表<a name="section11257113618419"></a>

无

## 子组件<a name="section9288143101012"></a>

支持。

## 属性<a name="section2907183951110"></a>

支持[通用属性](js-components-common-attributes.md)。

## 样式<a name="section10683162023215"></a>

支持[组件通用样式](js-components-common-styles.md)。

## 事件<a name="section77341431152917"></a>

处支持[通用事件](js-components-common-events.md)外，还支持如下事件：

<a name="table1180610218398"></a>
<table><thead align="left"><tr id="row8806162153917"><th class="cellrowborder" valign="top" width="22.7022702270227%" id="mcps1.1.4.1.1"><p id="p0807112143914"><a name="p0807112143914"></a><a name="p0807112143914"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="16.881688168816883%" id="mcps1.1.4.1.2"><p id="p380752110397"><a name="p380752110397"></a><a name="p380752110397"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="60.41604160416041%" id="mcps1.1.4.1.3"><p id="p118071121183910"><a name="p118071121183910"></a><a name="p118071121183910"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row380713217397"><td class="cellrowborder" valign="top" width="22.7022702270227%" headers="mcps1.1.4.1.1 "><p id="p19132135593918"><a name="p19132135593918"></a><a name="p19132135593918"></a>submit</p>
</td>
<td class="cellrowborder" valign="top" width="16.881688168816883%" headers="mcps1.1.4.1.2 "><p id="p17807152183918"><a name="p17807152183918"></a><a name="p17807152183918"></a><a href="#table195257111418">FormResult</a></p>
</td>
<td class="cellrowborder" valign="top" width="60.41604160416041%" headers="mcps1.1.4.1.3 "><p id="p8807102116392"><a name="p8807102116392"></a><a name="p8807102116392"></a>点击提交按钮，进行表单提交时，触发该事件。</p>
</td>
</tr>
<tr id="row38502504218"><td class="cellrowborder" valign="top" width="22.7022702270227%" headers="mcps1.1.4.1.1 "><p id="p1085019519428"><a name="p1085019519428"></a><a name="p1085019519428"></a>reset</p>
</td>
<td class="cellrowborder" valign="top" width="16.881688168816883%" headers="mcps1.1.4.1.2 "><p id="p108501958427"><a name="p108501958427"></a><a name="p108501958427"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="60.41604160416041%" headers="mcps1.1.4.1.3 "><p id="p2850758423"><a name="p2850758423"></a><a name="p2850758423"></a>点击重置按钮后，触发该事件。</p>
</td>
</tr>
</tbody>
</table>

**表 1**  FormResult

<a name="table195257111418"></a>
<table><thead align="left"><tr id="row55251211114111"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p2052551119411"><a name="p2052551119411"></a><a name="p2052551119411"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p2525141116412"><a name="p2525141116412"></a><a name="p2525141116412"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p55251011134114"><a name="p55251011134114"></a><a name="p55251011134114"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row352501115412"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p15525191113412"><a name="p15525191113412"></a><a name="p15525191113412"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p145256112413"><a name="p145256112413"></a><a name="p145256112413"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1852512118411"><a name="p1852512118411"></a><a name="p1852512118411"></a>input元素的name和value的值。</p>
</td>
</tr>
</tbody>
</table>

## 方法<a name="section2279124532420"></a>

支持[通用方法](js-components-common-methods.md)。

## 示例<a name="section1241545010391"></a>

```
<!-- xxx.hml -->
<form onsubmit='onSubmit' onreset='onReset'>
  <label>选项一</label>
  <input type='radio' name='radioGroup' value='radio1'></input>
  <label>选项二</label>
  <input type='radio' name='radioGroup' value='radio2'></input>
  <text>输入文本</text>
  <input type='text' name='user'></input>
  <input type='submit'>Submit</input>
  <input type='reset'>Reset</input>
</form>
```

```
// xxx.js
export default{
  onSubmit(result) {
    console.log(result.value.radioGroup) // radio1 or radio2
    console.log(result.value.user) // text input value
  },
  onReset() {
    console.log('reset all value')
  }
}
```

