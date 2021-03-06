# 插值计算<a name="ZH-CN_TOPIC_0000001119768252"></a>

## 导入模块<a name="section377963175114"></a>

```
import curves from '@ohos.curves'
```

## 权限<a name="section1455919446525"></a>

无

## curves.init<a name="section10551016104218"></a>

init\(curve?: Curve\): Object

插值曲线的初始化函数，可以根据入参创建一个插值曲线对象。

-   参数

    <a name="table69661135912"></a>
    <table><thead align="left"><tr id="row149668318915"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p7966738914"><a name="p7966738914"></a><a name="p7966738914"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p296713699"><a name="p296713699"></a><a name="p296713699"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p196718315911"><a name="p196718315911"></a><a name="p196718315911"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p02881223125210"><a name="p02881223125210"></a><a name="p02881223125210"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p9967231197"><a name="p9967231197"></a><a name="p9967231197"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row18967831393"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p39671131590"><a name="p39671131590"></a><a name="p39671131590"></a>curve</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p126051952172518"><a name="p126051952172518"></a><a name="p126051952172518"></a>Curve</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p149671932919"><a name="p149671932919"></a><a name="p149671932919"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p528813237529"><a name="p528813237529"></a><a name="p528813237529"></a>Linear</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p168155166474"><a name="p168155166474"></a><a name="p168155166474"></a>曲线对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    曲线对象Object。


## curves.steps<a name="section14558238104310"></a>

steps\(count: number, end: boolean\): Object

构造阶梯曲线对象。

-   参数：

    <a name="table0249629144818"></a>
    <table><thead align="left"><tr id="row124982915486"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p13249132917480"><a name="p13249132917480"></a><a name="p13249132917480"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p12496298488"><a name="p12496298488"></a><a name="p12496298488"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p1024912919485"><a name="p1024912919485"></a><a name="p1024912919485"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p879793714527"><a name="p879793714527"></a><a name="p879793714527"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p7249192994817"><a name="p7249192994817"></a><a name="p7249192994817"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row324915297485"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p824982974812"><a name="p824982974812"></a><a name="p824982974812"></a>count</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p1224913295481"><a name="p1224913295481"></a><a name="p1224913295481"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p02491629134812"><a name="p02491629134812"></a><a name="p02491629134812"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p1279713715219"><a name="p1279713715219"></a><a name="p1279713715219"></a>-</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p13249172974815"><a name="p13249172974815"></a><a name="p13249172974815"></a>阶梯的数量，需要为正整数。</p>
    </td>
    </tr>
    <tr id="row7878205385210"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p7878155319522"><a name="p7878155319522"></a><a name="p7878155319522"></a>end</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p11878105317525"><a name="p11878105317525"></a><a name="p11878105317525"></a>boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p3878053125214"><a name="p3878053125214"></a><a name="p3878053125214"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p1587819539520"><a name="p1587819539520"></a><a name="p1587819539520"></a>true</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p4878115313527"><a name="p4878115313527"></a><a name="p4878115313527"></a>在每个间隔的起点或是终点发生阶跃变化 ，默认值为true，即在终点发生阶跃变化。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    曲线对象Object。


## curves.cubicBezier<a name="section548233515442"></a>

cubicBezier\(x1: number, y1: number, x2: number, y2: number\): Object

构造三阶贝塞尔曲线对象，曲线的值必须处于0-1之间。

-   参数

    <a name="table3158136144813"></a>
    <table><thead align="left"><tr id="row151581136164820"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p141580364487"><a name="p141580364487"></a><a name="p141580364487"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.729999999999999%" id="mcps1.1.5.1.2"><p id="p6158103613485"><a name="p6158103613485"></a><a name="p6158103613485"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="9.16%" id="mcps1.1.5.1.3"><p id="p115843684817"><a name="p115843684817"></a><a name="p115843684817"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="61.29%" id="mcps1.1.5.1.4"><p id="p41581736184811"><a name="p41581736184811"></a><a name="p41581736184811"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row71591236104812"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p16159536184811"><a name="p16159536184811"></a><a name="p16159536184811"></a>x1</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p8159113684815"><a name="p8159113684815"></a><a name="p8159113684815"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p17159133634811"><a name="p17159133634811"></a><a name="p17159133634811"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p15159163664814"><a name="p15159163664814"></a><a name="p15159163664814"></a>确定贝塞尔曲线第一点横坐标。</p>
    </td>
    </tr>
    <tr id="row74932085115"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p949316065114"><a name="p949316065114"></a><a name="p949316065114"></a>y1</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p149313011517"><a name="p149313011517"></a><a name="p149313011517"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p84938011513"><a name="p84938011513"></a><a name="p84938011513"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p124932020510"><a name="p124932020510"></a><a name="p124932020510"></a>确定贝塞尔曲线第一点纵坐标。</p>
    </td>
    </tr>
    <tr id="row94250210517"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p8425623518"><a name="p8425623518"></a><a name="p8425623518"></a>x2</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p34251829512"><a name="p34251829512"></a><a name="p34251829512"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p0425726516"><a name="p0425726516"></a><a name="p0425726516"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p34261218514"><a name="p34261218514"></a><a name="p34261218514"></a>确定贝塞尔曲线第二点横坐标。</p>
    </td>
    </tr>
    <tr id="row023810485115"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p1523810412512"><a name="p1523810412512"></a><a name="p1523810412512"></a>y2</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p923824105112"><a name="p923824105112"></a><a name="p923824105112"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p1723810475114"><a name="p1723810475114"></a><a name="p1723810475114"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p123984195113"><a name="p123984195113"></a><a name="p123984195113"></a>确定贝塞尔曲线第二点纵坐标。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    曲线对象Object。


## curves.spring<a name="section185801926114514"></a>

spring\(velocity: number, mass: number, stiffness: number, damping: number\): Object

构造弹簧曲线对象。

-   参数

    <a name="table131871943104820"></a>
    <table><thead align="left"><tr id="row181871743184818"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p1218734312483"><a name="p1218734312483"></a><a name="p1218734312483"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.729999999999999%" id="mcps1.1.5.1.2"><p id="p418784319488"><a name="p418784319488"></a><a name="p418784319488"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="9.16%" id="mcps1.1.5.1.3"><p id="p11871343184815"><a name="p11871343184815"></a><a name="p11871343184815"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="61.29%" id="mcps1.1.5.1.4"><p id="p318719438480"><a name="p318719438480"></a><a name="p318719438480"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row191871543204816"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p181872434485"><a name="p181872434485"></a><a name="p181872434485"></a>velocity</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p10187154315489"><a name="p10187154315489"></a><a name="p10187154315489"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p12187114324819"><a name="p12187114324819"></a><a name="p12187114324819"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p618794317482"><a name="p618794317482"></a><a name="p618794317482"></a>初始速度。</p>
    </td>
    </tr>
    <tr id="row1618041604916"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p418071614913"><a name="p418071614913"></a><a name="p418071614913"></a>mass</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p4180916174920"><a name="p4180916174920"></a><a name="p4180916174920"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p12180161674916"><a name="p12180161674916"></a><a name="p12180161674916"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p1718091618492"><a name="p1718091618492"></a><a name="p1718091618492"></a>质量。</p>
    </td>
    </tr>
    <tr id="row10880111194912"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p1088021114913"><a name="p1088021114913"></a><a name="p1088021114913"></a>stiffness</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p1388011104913"><a name="p1388011104913"></a><a name="p1388011104913"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p15880101154919"><a name="p15880101154919"></a><a name="p15880101154919"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p288031184919"><a name="p288031184919"></a><a name="p288031184919"></a>刚度。</p>
    </td>
    </tr>
    <tr id="row1773111135015"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p373121105014"><a name="p373121105014"></a><a name="p373121105014"></a>damping</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p177311185012"><a name="p177311185012"></a><a name="p177311185012"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p27381105013"><a name="p27381105013"></a><a name="p27381105013"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p47414115501"><a name="p47414115501"></a><a name="p47414115501"></a>阻尼。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    曲线对象Object。


## 示例<a name="section75051320581"></a>

```
import Curves from '@ohos.curves'
let curve1 = Curves.init() // 创建一个默认线性插值曲线
let curve2 = Curves.init(Curve.EaseIn) // 创建一个默认先慢后快插值曲线
let curve3 = Curves.spring(100, 1, 228, 30) // 创建一个弹簧插值曲线
let curve3 = Curves.cubicBezier(0.1, 0.0, 0.1, 1.0) // 创建一个三阶贝塞尔曲线
```

曲线对象只能通过上面的接口创建。

<a name="table268mcpsimp"></a>
<table><thead align="left"><tr id="row274mcpsimp"><th class="cellrowborder" valign="top" width="39.26%" id="mcps1.1.3.1.1"><p id="p276mcpsimp"><a name="p276mcpsimp"></a><a name="p276mcpsimp"></a>接口名称</p>
</th>
<th class="cellrowborder" valign="top" width="60.74%" id="mcps1.1.3.1.2"><p id="p280mcpsimp"><a name="p280mcpsimp"></a><a name="p280mcpsimp"></a>功能描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row281mcpsimp"><td class="cellrowborder" valign="top" width="39.26%" headers="mcps1.1.3.1.1 "><p id="p825816201103"><a name="p825816201103"></a><a name="p825816201103"></a>interpolate(time: number): number</p>
</td>
<td class="cellrowborder" valign="top" width="60.74%" headers="mcps1.1.3.1.2 "><p id="p163641244113119"><a name="p163641244113119"></a><a name="p163641244113119"></a>插值曲线的插值计算函数，可以通过传入的归一化时间参数返回当前的插值。</p>
<p id="p71285919117"><a name="p71285919117"></a><a name="p71285919117"></a>time: 当前的归一化时间参数，有效值范围0到1。</p>
<p id="p154022291218"><a name="p154022291218"></a><a name="p154022291218"></a>返回归一化time时间点对应的曲线插值。</p>
</td>
</tr>
</tbody>
</table>

-   示例

    ```
    import Curves from '@ohos.curves'
    let curve = Curves.init(Curve.EaseIn) // 创建一个默认先慢后快插值曲线
    let value: number = curve.interpolate(0.5) // 计算得到时间到一半时的插值
    ```


## 整体示例<a name="section839432815193"></a>

```
import Curves from '@ohos.curves'
@Entry
@Component
struct ImageComponent {
  @State widthSize: number = 200
  @State heightSize: number = 200
  build() {
    Column() {
      Text()
        .margin({top:100})
        .width(this.widthSize)
        .height(this.heightSize)
        .backgroundColor(Color.Red)
        .onClick(()=> {
          let curve = Curves.cubicBezier(0.25, 0.1, 0.25, 1.0);
          this.widthSize = curve.interpolate(0.5) * this.widthSize;
          this.heightSize = curve.interpolate(0.5) * this.heightSize;
        })
        .animation({duration: 2000 , curve: Curves.spring(0.25, 0.1, 0.25, 1.0)})
    }.width("100%").height("100%")
  }
}
```

![](figures/5-20.gif)

