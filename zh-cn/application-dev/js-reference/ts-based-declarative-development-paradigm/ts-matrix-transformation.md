# 矩阵变换<a name="ZH-CN_TOPIC_0000001119928158"></a>

## 导入模块<a name="section1727172013219"></a>

```
import matrix4 from '@ohos.matrix4'
```

## 权限<a name="section7743183014286"></a>

无

## matrix4.init<a name="section12864856072"></a>

init\(array: Array<number\>\): Object

Matrix的构造函数，可以通过传入的参数创建一个四阶矩阵，矩阵为列优先。

-   参数

    <a name="table69661135912"></a>
    <table><thead align="left"><tr id="row149668318915"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p7966738914"><a name="p7966738914"></a><a name="p7966738914"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p296713699"><a name="p296713699"></a><a name="p296713699"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p196718315911"><a name="p196718315911"></a><a name="p196718315911"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.790000000000003%" id="mcps1.1.6.1.4"><p id="p13769183172911"><a name="p13769183172911"></a><a name="p13769183172911"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="45.410000000000004%" id="mcps1.1.6.1.5"><p id="p9967231197"><a name="p9967231197"></a><a name="p9967231197"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row18967831393"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p39671131590"><a name="p39671131590"></a><a name="p39671131590"></a>array</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p16545165318258"><a name="p16545165318258"></a><a name="p16545165318258"></a>Array&lt;number&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p149671932919"><a name="p149671932919"></a><a name="p149671932919"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.790000000000003%" headers="mcps1.1.6.1.4 "><p id="p383310463295"><a name="p383310463295"></a><a name="p383310463295"></a>[1, 0, 0, 0,</p>
    <p id="p9833154662917"><a name="p9833154662917"></a><a name="p9833154662917"></a>0, 1, 0, 0,</p>
    <p id="p1083304672916"><a name="p1083304672916"></a><a name="p1083304672916"></a>0, 0, 1, 0,</p>
    <p id="p17833104652910"><a name="p17833104652910"></a><a name="p17833104652910"></a>0, 0, 0, 1]</p>
    </td>
    <td class="cellrowborder" valign="top" width="45.410000000000004%" headers="mcps1.1.6.1.5 "><p id="p147631917301"><a name="p147631917301"></a><a name="p147631917301"></a>参数为长度为16（4*4）的number数组, 详情见<a href="#li1515172020468">参数描述</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    <a name="table16391145317913"></a>
    <table><thead align="left"><tr id="row2391145319910"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p13911353991"><a name="p13911353991"></a><a name="p13911353991"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p193911531395"><a name="p193911531395"></a><a name="p193911531395"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1339114531391"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p156879250282"><a name="p156879250282"></a><a name="p156879250282"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p1312703682719"><a name="p1312703682719"></a><a name="p1312703682719"></a>根据入参创建的四阶矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   <a name="li1515172020468"></a>参数描述

    <a name="table139791826174616"></a>
    <table><thead align="left"><tr id="row1497992664617"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p897912619464"><a name="p897912619464"></a><a name="p897912619464"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.2"><p id="p897911263465"><a name="p897911263465"></a><a name="p897911263465"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.3"><p id="p3979626174610"><a name="p3979626174610"></a><a name="p3979626174610"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.4"><p id="p1697982614463"><a name="p1697982614463"></a><a name="p1697982614463"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row179797267464"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p119798262465"><a name="p119798262465"></a><a name="p119798262465"></a>m00</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p297952664613"><a name="p297952664613"></a><a name="p297952664613"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p18979142616461"><a name="p18979142616461"></a><a name="p18979142616461"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p49797262468"><a name="p49797262468"></a><a name="p49797262468"></a>x轴缩放值，单位矩阵默认为1。</p>
    </td>
    </tr>
    <tr id="row19979202654615"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p49791726184619"><a name="p49791726184619"></a><a name="p49791726184619"></a>m01</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p4979102614612"><a name="p4979102614612"></a><a name="p4979102614612"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p997962612465"><a name="p997962612465"></a><a name="p997962612465"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p1697952610466"><a name="p1697952610466"></a><a name="p1697952610466"></a>第2个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row397942644610"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p698019263468"><a name="p698019263468"></a><a name="p698019263468"></a>m02</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p3980182694614"><a name="p3980182694614"></a><a name="p3980182694614"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p17980172644611"><a name="p17980172644611"></a><a name="p17980172644611"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p99801626184614"><a name="p99801626184614"></a><a name="p99801626184614"></a>第3个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row109801726104619"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p79801926124614"><a name="p79801926124614"></a><a name="p79801926124614"></a>m03</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p199801126114617"><a name="p199801126114617"></a><a name="p199801126114617"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p3980426154611"><a name="p3980426154611"></a><a name="p3980426154611"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p498012617462"><a name="p498012617462"></a><a name="p498012617462"></a>无实际意义。</p>
    </td>
    </tr>
    <tr id="row1298092610468"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p8980426154620"><a name="p8980426154620"></a><a name="p8980426154620"></a>m10</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p209802026144616"><a name="p209802026144616"></a><a name="p209802026144616"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p5980162664618"><a name="p5980162664618"></a><a name="p5980162664618"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p898016260460"><a name="p898016260460"></a><a name="p898016260460"></a>第5个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row169803263461"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p298072618469"><a name="p298072618469"></a><a name="p298072618469"></a>m11</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p2980526194611"><a name="p2980526194611"></a><a name="p2980526194611"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p1898052617462"><a name="p1898052617462"></a><a name="p1898052617462"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p19805264466"><a name="p19805264466"></a><a name="p19805264466"></a>y轴缩放值，单位矩阵默认为1。</p>
    </td>
    </tr>
    <tr id="row298017266467"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p498018266469"><a name="p498018266469"></a><a name="p498018266469"></a>m12</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p798017261468"><a name="p798017261468"></a><a name="p798017261468"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p1698022614614"><a name="p1698022614614"></a><a name="p1698022614614"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p17980112611466"><a name="p17980112611466"></a><a name="p17980112611466"></a>第7个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row898017266468"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p39803262467"><a name="p39803262467"></a><a name="p39803262467"></a>m13</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p13980926154616"><a name="p13980926154616"></a><a name="p13980926154616"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p169800262468"><a name="p169800262468"></a><a name="p169800262468"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p498072684618"><a name="p498072684618"></a><a name="p498072684618"></a>无实际意义。</p>
    </td>
    </tr>
    <tr id="row119801726124612"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p109801726174615"><a name="p109801726174615"></a><a name="p109801726174615"></a>m20</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p7980326104618"><a name="p7980326104618"></a><a name="p7980326104618"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p12981826134613"><a name="p12981826134613"></a><a name="p12981826134613"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p119811126184615"><a name="p119811126184615"></a><a name="p119811126184615"></a>第9个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row798162617469"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1598112617461"><a name="p1598112617461"></a><a name="p1598112617461"></a>m21</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p598112269469"><a name="p598112269469"></a><a name="p598112269469"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p598182684611"><a name="p598182684611"></a><a name="p598182684611"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p6981826194617"><a name="p6981826194617"></a><a name="p6981826194617"></a>第10个值，xyz轴旋转会影响这个值。</p>
    </td>
    </tr>
    <tr id="row898192674616"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p2981526154618"><a name="p2981526154618"></a><a name="p2981526154618"></a>m22</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p179811826134618"><a name="p179811826134618"></a><a name="p179811826134618"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p13981132624613"><a name="p13981132624613"></a><a name="p13981132624613"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p39815261466"><a name="p39815261466"></a><a name="p39815261466"></a>z轴缩放值，单位矩阵默认为1。</p>
    </td>
    </tr>
    <tr id="row3981202613463"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p69811268467"><a name="p69811268467"></a><a name="p69811268467"></a>m23</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p1898112684618"><a name="p1898112684618"></a><a name="p1898112684618"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p99811226114615"><a name="p99811226114615"></a><a name="p99811226114615"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p139819261460"><a name="p139819261460"></a><a name="p139819261460"></a>无实际意义。</p>
    </td>
    </tr>
    <tr id="row12981162616465"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p09816268462"><a name="p09816268462"></a><a name="p09816268462"></a>m30</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p13981526154614"><a name="p13981526154614"></a><a name="p13981526154614"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p6981626174612"><a name="p6981626174612"></a><a name="p6981626174612"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p098118264469"><a name="p098118264469"></a><a name="p098118264469"></a>x轴平移值，单位px，单位矩阵默认为0。</p>
    </td>
    </tr>
    <tr id="row2098132618460"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p298112694616"><a name="p298112694616"></a><a name="p298112694616"></a>m31</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p169811326194614"><a name="p169811326194614"></a><a name="p169811326194614"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p09811426124615"><a name="p09811426124615"></a><a name="p09811426124615"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p159811926144619"><a name="p159811926144619"></a><a name="p159811926144619"></a>y轴平移值，单位px，单位矩阵默认为0。</p>
    </td>
    </tr>
    <tr id="row209811526154613"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p139814263468"><a name="p139814263468"></a><a name="p139814263468"></a>m32</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p19981126134615"><a name="p19981126134615"></a><a name="p19981126134615"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p898213261465"><a name="p898213261465"></a><a name="p898213261465"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p0982142664610"><a name="p0982142664610"></a><a name="p0982142664610"></a>z轴平移值，单位px，单位矩阵默认为0。</p>
    </td>
    </tr>
    <tr id="row159823263463"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p159821926144620"><a name="p159821926144620"></a><a name="p159821926144620"></a>m33</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.2 "><p id="p7982326184616"><a name="p7982326184616"></a><a name="p7982326184616"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.3 "><p id="p29821263465"><a name="p29821263465"></a><a name="p29821263465"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.4 "><p id="p3982152615462"><a name="p3982152615462"></a><a name="p3982152615462"></a>齐次坐标下生效，产生透视投影效果。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    // 创建一个四阶矩阵
    let matrix = Matrix4.init([1.0, 0.0, 0.0, 0.0,
                              0.0, 1.0, 0.0, 0.0,
                              0.0, 0.0, 1.0, 0.0,
                              0.0, 0.0, 0.0, 1.0])
    ```


## matrix4.identity<a name="section042975416311"></a>

identity\(\): Object

Matrix的初始化函数，可以返回一个单位矩阵对象。

-   返回值

    <a name="table27644593325"></a>
    <table><thead align="left"><tr id="row07648597326"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p176455903217"><a name="p176455903217"></a><a name="p176455903217"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p57641059173211"><a name="p57641059173211"></a><a name="p57641059173211"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1576485919323"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p147648599321"><a name="p147648599321"></a><a name="p147648599321"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p167641359113220"><a name="p167641359113220"></a><a name="p167641359113220"></a>单位矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    // matrix1 和 matrix2 效果一致
    import Matrix4 from '@ohos.matrix4'
    let matrix = Matrix4.init([1.0, 0.0, 0.0, 0.0,
                              0.0, 1.0, 0.0, 0.0,
                              0.0, 0.0, 1.0, 0.0,
                              0.0, 0.0, 0.0, 1.0])
    let matrix2 = Matrix4.identity()
    ```


## matrix4.copy<a name="section9959103514339"></a>

copy\(\): Object

Matrix的拷贝函数，可以拷贝一份当前的矩阵对象。

-   返回值

    <a name="table88791649133410"></a>
    <table><thead align="left"><tr id="row187917499345"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p487934917342"><a name="p487934917342"></a><a name="p487934917342"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p687910492340"><a name="p687910492340"></a><a name="p687910492340"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1887911497343"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p3879649203414"><a name="p3879649203414"></a><a name="p3879649203414"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p1187994953419"><a name="p1187994953419"></a><a name="p1187994953419"></a>当前矩阵的拷贝对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().translate({x:100})
      private matrix2 = this.matrix1.copy().scale({x:2})
      build() {
        Column() {
          Image($r("app.media.bg1"))
            .width("40%")
            .height(100)
            .transform(this.matrix1)
          Image($r("app.media.bg2"))
            .width("40%")
            .height(100)
            .margin({top:50})
            .transform(this.matrix2)
        }
      }
    }
    ```

    ![](figures/s1.png)


## Matrix4<a name="section118153513365"></a>

### combine<a name="section267686121415"></a>

combine\(matrix: Matrix4\): Object

Matrix的叠加函数，可以将两个矩阵的效果叠加起来生成一个新的矩阵对象。

-   参数

    <a name="table13750122713715"></a>
    <table><thead align="left"><tr id="row9750192717371"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p6750327173719"><a name="p6750327173719"></a><a name="p6750327173719"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p14750127123720"><a name="p14750127123720"></a><a name="p14750127123720"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p17750102710376"><a name="p17750102710376"></a><a name="p17750102710376"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p1075052733715"><a name="p1075052733715"></a><a name="p1075052733715"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p1175013272378"><a name="p1175013272378"></a><a name="p1175013272378"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row18750162743718"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p5750152723711"><a name="p5750152723711"></a><a name="p5750152723711"></a>matrix</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p180718374375"><a name="p180718374375"></a><a name="p180718374375"></a>Matrix4</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p375016274378"><a name="p375016274378"></a><a name="p375016274378"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p195305491376"><a name="p195305491376"></a><a name="p195305491376"></a>-</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p136451955183714"><a name="p136451955183714"></a><a name="p136451955183714"></a>待叠加的矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值

    <a name="table1832155273615"></a>
    <table><thead align="left"><tr id="row173211852183617"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p3321352113612"><a name="p3321352113612"></a><a name="p3321352113612"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p0321152113618"><a name="p0321152113618"></a><a name="p0321152113618"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row9321125211361"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p532275210362"><a name="p532275210362"></a><a name="p532275210362"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p143221352173614"><a name="p143221352173614"></a><a name="p143221352173614"></a>矩阵叠加后的对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().translate({x:200}).copy()
      private matrix2 = Matrix4.identity().scale({x:2}).copy()
      build() {
        Column() {
         // 先平移x轴100px，再缩放两倍x轴
          Image($r("app.media.bg1")).transform(this.matrix1.combine(this.matrix2)) 
            .width("40%")
            .height(100)
            .margin({top:50})
        }
      }
    }
    ```

    ![](figures/q1.png)


### invert<a name="section592117351618"></a>

invert\(\): Object

Matrix的逆函数，可以返回一个当前矩阵对象的逆矩阵，即效果正好相反。

-   返回值

    <a name="table13802173504114"></a>
    <table><thead align="left"><tr id="row380283513415"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p5802935154113"><a name="p5802935154113"></a><a name="p5802935154113"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p48021535184110"><a name="p48021535184110"></a><a name="p48021535184110"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row7802935184116"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p1803035164116"><a name="p1803035164116"></a><a name="p1803035164116"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p7803135144115"><a name="p7803135144115"></a><a name="p7803135144115"></a>当前矩阵的逆矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    // matrix1(宽放大2倍) 和 matrix2(宽缩小2倍) 效果相反
    let matrix1 = Matrix4.identity().scale({x:2})
    let matrix2 = matrix1.invert()
    ```


### translate<a name="section39828585169"></a>

translate\(\{x?: number, y?: number, z?: number\}\): Object

Matrix的平移函数，可以为当前矩阵增加x轴/Y轴/Z轴平移效果。

-   参数

    <a name="table194487472448"></a>
    <table><thead align="left"><tr id="row1449747114411"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p54494474449"><a name="p54494474449"></a><a name="p54494474449"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p444964774420"><a name="p444964774420"></a><a name="p444964774420"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p194491447144410"><a name="p194491447144410"></a><a name="p194491447144410"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p64491247114418"><a name="p64491247114418"></a><a name="p64491247114418"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p114491547194413"><a name="p114491547194413"></a><a name="p114491547194413"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1744917476446"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p164492047154417"><a name="p164492047154417"></a><a name="p164492047154417"></a>x</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p10449154716449"><a name="p10449154716449"></a><a name="p10449154716449"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p444944764413"><a name="p444944764413"></a><a name="p444944764413"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p344914744419"><a name="p344914744419"></a><a name="p344914744419"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p24499475446"><a name="p24499475446"></a><a name="p24499475446"></a>x轴的平移距离，单位px。</p>
    </td>
    </tr>
    <tr id="row63031117164514"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p12304191764512"><a name="p12304191764512"></a><a name="p12304191764512"></a>y</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p15304181764514"><a name="p15304181764514"></a><a name="p15304181764514"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p1730441764510"><a name="p1730441764510"></a><a name="p1730441764510"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p930491744519"><a name="p930491744519"></a><a name="p930491744519"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p12304141774514"><a name="p12304141774514"></a><a name="p12304141774514"></a>y轴的平移距离，单位px。</p>
    </td>
    </tr>
    <tr id="row8853111914511"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p118531119124511"><a name="p118531119124511"></a><a name="p118531119124511"></a>z</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p28531619174520"><a name="p28531619174520"></a><a name="p28531619174520"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p6853161924511"><a name="p6853161924511"></a><a name="p6853161924511"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p2853191915459"><a name="p2853191915459"></a><a name="p2853191915459"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p1349911391455"><a name="p1349911391455"></a><a name="p1349911391455"></a>z轴的平移距离，单位px。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   返回值

    <a name="table185184314312"></a>
    <table><thead align="left"><tr id="row65174334316"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p11511543194313"><a name="p11511543194313"></a><a name="p11511543194313"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p1351104364311"><a name="p1351104364311"></a><a name="p1351104364311"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row145184374318"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p8514432438"><a name="p8514432438"></a><a name="p8514432438"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p492055613433"><a name="p492055613433"></a><a name="p492055613433"></a>增加好平移效果后的矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().translate({x:100, y:200, z:30})
      build() {
        Column() {
          Image($r("app.media.bg1")).transform(this.matrix1)
            .width("40%")
            .height(100)
        }
      }
    }
    ```

    ![](figures/s3.png)


### scale<a name="section835405115174"></a>

scale\(\{x?: number, y?: number, z?: number, centerX?: number, centerY?: number\}\): Object

Matrix的缩放函数，可以为当前矩阵增加x轴/Y轴/Z轴缩放效果。

-   参数

    <a name="table15488262465"></a>
    <table><thead align="left"><tr id="row348811644616"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p2048936144620"><a name="p2048936144620"></a><a name="p2048936144620"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p1248966204618"><a name="p1248966204618"></a><a name="p1248966204618"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p3489196104616"><a name="p3489196104616"></a><a name="p3489196104616"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.51%" id="mcps1.1.6.1.4"><p id="p11489665469"><a name="p11489665469"></a><a name="p11489665469"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.69%" id="mcps1.1.6.1.5"><p id="p248910664617"><a name="p248910664617"></a><a name="p248910664617"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row104898613466"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p9489106184612"><a name="p9489106184612"></a><a name="p9489106184612"></a>x</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p448912612461"><a name="p448912612461"></a><a name="p448912612461"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p124895614618"><a name="p124895614618"></a><a name="p124895614618"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.51%" headers="mcps1.1.6.1.4 "><p id="p10489176134615"><a name="p10489176134615"></a><a name="p10489176134615"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.69%" headers="mcps1.1.6.1.5 "><p id="p0489156104615"><a name="p0489156104615"></a><a name="p0489156104615"></a>x轴的缩放倍数。</p>
    </td>
    </tr>
    <tr id="row2489146124619"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p14489136144616"><a name="p14489136144616"></a><a name="p14489136144616"></a>y</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p648917674613"><a name="p648917674613"></a><a name="p648917674613"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p54890615465"><a name="p54890615465"></a><a name="p54890615465"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.51%" headers="mcps1.1.6.1.4 "><p id="p34891614465"><a name="p34891614465"></a><a name="p34891614465"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.69%" headers="mcps1.1.6.1.5 "><p id="p12489126134617"><a name="p12489126134617"></a><a name="p12489126134617"></a>y轴的缩放倍数。</p>
    </td>
    </tr>
    <tr id="row124892644616"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p124892644616"><a name="p124892644616"></a><a name="p124892644616"></a>z</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p19489366464"><a name="p19489366464"></a><a name="p19489366464"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p14490465467"><a name="p14490465467"></a><a name="p14490465467"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.51%" headers="mcps1.1.6.1.4 "><p id="p17490568465"><a name="p17490568465"></a><a name="p17490568465"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.69%" headers="mcps1.1.6.1.5 "><p id="p349056124615"><a name="p349056124615"></a><a name="p349056124615"></a>z轴的缩放倍数。</p>
    </td>
    </tr>
    <tr id="row038811247469"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p538813241466"><a name="p538813241466"></a><a name="p538813241466"></a>centerX</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p17388152474612"><a name="p17388152474612"></a><a name="p17388152474612"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p63311440114612"><a name="p63311440114612"></a><a name="p63311440114612"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.51%" headers="mcps1.1.6.1.4 "><p id="p93881824114611"><a name="p93881824114611"></a><a name="p93881824114611"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.69%" headers="mcps1.1.6.1.5 "><p id="p53881824104613"><a name="p53881824104613"></a><a name="p53881824104613"></a>变换中心点x轴坐标。</p>
    </td>
    </tr>
    <tr id="row925832812460"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p8258162816462"><a name="p8258162816462"></a><a name="p8258162816462"></a>centerY</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p1825872874610"><a name="p1825872874610"></a><a name="p1825872874610"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p49141140124611"><a name="p49141140124611"></a><a name="p49141140124611"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.51%" headers="mcps1.1.6.1.4 "><p id="p16258142854612"><a name="p16258142854612"></a><a name="p16258142854612"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.69%" headers="mcps1.1.6.1.5 "><p id="p34851752124617"><a name="p34851752124617"></a><a name="p34851752124617"></a>变换中心点y轴坐标。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   返回值

    <a name="table1640673712434"></a>
    <table><thead align="left"><tr id="row8406837144314"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p8406113794312"><a name="p8406113794312"></a><a name="p8406113794312"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p15406193718438"><a name="p15406193718438"></a><a name="p15406193718438"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row134061037134318"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p14406153713435"><a name="p14406153713435"></a><a name="p14406153713435"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p278017184414"><a name="p278017184414"></a><a name="p278017184414"></a>增加好缩放效果后的矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().scale({x:2, y:3, z:4, centerX:50, centerY:50})
      build() {
        Column() { 
          Image($r("app.media.bg1")).transform(this.matrix1)
            .width("40%")
            .height(100)
        }
      }
    }
    ```

    ![](figures/s4-(1).png)


### rotate<a name="section524516309189"></a>

rotate\(\{x?: number, y?: number, z?: number, angle?: number, centerX?: Length, centerY?: Length\}\): Object

Matrix的旋转函数，可以为当前矩阵增加x轴/Y轴/Z轴旋转效果。

-   参数

    <a name="table36157136470"></a>
    <table><thead align="left"><tr id="row126152139472"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p4615141354713"><a name="p4615141354713"></a><a name="p4615141354713"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p14615513174710"><a name="p14615513174710"></a><a name="p14615513174710"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p5616121314473"><a name="p5616121314473"></a><a name="p5616121314473"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p13616201310475"><a name="p13616201310475"></a><a name="p13616201310475"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p1261631311479"><a name="p1261631311479"></a><a name="p1261631311479"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row861661313473"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p1861661310471"><a name="p1861661310471"></a><a name="p1861661310471"></a>x</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p16161313104718"><a name="p16161313104718"></a><a name="p16161313104718"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p1361621334717"><a name="p1361621334717"></a><a name="p1361621334717"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p161611134473"><a name="p161611134473"></a><a name="p161611134473"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p1661601311476"><a name="p1661601311476"></a><a name="p1661601311476"></a>旋转轴向量x坐标。</p>
    </td>
    </tr>
    <tr id="row861681317477"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p16616201314710"><a name="p16616201314710"></a><a name="p16616201314710"></a>y</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p7616113124715"><a name="p7616113124715"></a><a name="p7616113124715"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p1561681344719"><a name="p1561681344719"></a><a name="p1561681344719"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p1461691314713"><a name="p1461691314713"></a><a name="p1461691314713"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p18616181313474"><a name="p18616181313474"></a><a name="p18616181313474"></a>旋转轴向量y坐标。</p>
    </td>
    </tr>
    <tr id="row17616201394719"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p16616141310476"><a name="p16616141310476"></a><a name="p16616141310476"></a>z</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p13616111344714"><a name="p13616111344714"></a><a name="p13616111344714"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p06172134472"><a name="p06172134472"></a><a name="p06172134472"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p16617131344717"><a name="p16617131344717"></a><a name="p16617131344717"></a>1</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p96171613154711"><a name="p96171613154711"></a><a name="p96171613154711"></a>旋转轴向量z坐标。</p>
    </td>
    </tr>
    <tr id="row15336171718476"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p133367172470"><a name="p133367172470"></a><a name="p133367172470"></a>angle</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p11336151712472"><a name="p11336151712472"></a><a name="p11336151712472"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p73365175476"><a name="p73365175476"></a><a name="p73365175476"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p12336171716478"><a name="p12336171716478"></a><a name="p12336171716478"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p123361917184716"><a name="p123361917184716"></a><a name="p123361917184716"></a>旋转角度。</p>
    </td>
    </tr>
    <tr id="row1661711364710"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p2061718133471"><a name="p2061718133471"></a><a name="p2061718133471"></a>centerX</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p166171013194713"><a name="p166171013194713"></a><a name="p166171013194713"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p5617191318471"><a name="p5617191318471"></a><a name="p5617191318471"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p4617111314470"><a name="p4617111314470"></a><a name="p4617111314470"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p66171813164717"><a name="p66171813164717"></a><a name="p66171813164717"></a>变换中心点x轴坐标。</p>
    </td>
    </tr>
    <tr id="row461714130476"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p8617131312470"><a name="p8617131312470"></a><a name="p8617131312470"></a>centerY</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p661761374713"><a name="p661761374713"></a><a name="p661761374713"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p1361719133473"><a name="p1361719133473"></a><a name="p1361719133473"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p116173132476"><a name="p116173132476"></a><a name="p116173132476"></a>0</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p15617313164712"><a name="p15617313164712"></a><a name="p15617313164712"></a>变换中心点y轴坐标。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   返回值

    <a name="table105212343434"></a>
    <table><thead align="left"><tr id="row165393415435"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p45383415436"><a name="p45383415436"></a><a name="p45383415436"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p953153484317"><a name="p953153484317"></a><a name="p953153484317"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1053634174317"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p115311346433"><a name="p115311346433"></a><a name="p115311346433"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p6680414184414"><a name="p6680414184414"></a><a name="p6680414184414"></a>增加好旋转效果后的矩阵对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().rotate({x:1, y:1, z:2, angle:30})
      build() {
        Column() {
          Image($r("app.media.bg1")).transform(this.matrix1)
            .width("40%")
            .height(100)
        }.width("100%").margin({top:50})
      }
    }
    ```

    ![](figures/1-19.png)


### transformPoint<a name="section174811817131913"></a>

transformPoint\(point: Point\): Point

Matrix的坐标点转换函数，可以将当前的变换效果作用到一个坐标点上。

-   参数

    <a name="table119403115448"></a>
    <table><thead align="left"><tr id="row2194113144418"><th class="cellrowborder" valign="top" width="13.71%" id="mcps1.1.6.1.1"><p id="p16194153124416"><a name="p16194153124416"></a><a name="p16194153124416"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="13.62%" id="mcps1.1.6.1.2"><p id="p13194133194414"><a name="p13194133194414"></a><a name="p13194133194414"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="8.469999999999999%" id="mcps1.1.6.1.3"><p id="p1519453194417"><a name="p1519453194417"></a><a name="p1519453194417"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p1819415319442"><a name="p1819415319442"></a><a name="p1819415319442"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.68%" id="mcps1.1.6.1.5"><p id="p519423174416"><a name="p519423174416"></a><a name="p519423174416"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row51941131104416"><td class="cellrowborder" valign="top" width="13.71%" headers="mcps1.1.6.1.1 "><p id="p5194113134411"><a name="p5194113134411"></a><a name="p5194113134411"></a>point</p>
    </td>
    <td class="cellrowborder" valign="top" width="13.62%" headers="mcps1.1.6.1.2 "><p id="p4194531194418"><a name="p4194531194418"></a><a name="p4194531194418"></a>Point</p>
    </td>
    <td class="cellrowborder" valign="top" width="8.469999999999999%" headers="mcps1.1.6.1.3 "><p id="p31941319445"><a name="p31941319445"></a><a name="p31941319445"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p819443119442"><a name="p819443119442"></a><a name="p819443119442"></a>-</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.68%" headers="mcps1.1.6.1.5 "><p id="p18195193117449"><a name="p18195193117449"></a><a name="p18195193117449"></a>需要转换的坐标点。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   返回值

    <a name="table7708628154313"></a>
    <table><thead align="left"><tr id="row19708202811434"><th class="cellrowborder" valign="top" width="17.380000000000003%" id="mcps1.1.3.1.1"><p id="p37081528184313"><a name="p37081528184313"></a><a name="p37081528184313"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.62%" id="mcps1.1.3.1.2"><p id="p570992819433"><a name="p570992819433"></a><a name="p570992819433"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row18709132813439"><td class="cellrowborder" valign="top" width="17.380000000000003%" headers="mcps1.1.3.1.1 "><p id="p670932804310"><a name="p670932804310"></a><a name="p670932804310"></a>Point</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.62%" headers="mcps1.1.3.1.2 "><p id="p1370992874318"><a name="p1370992874318"></a><a name="p1370992874318"></a>返回矩阵变换后的Point对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    import Matrix4 from '@ohos.matrix4'
    import prompt from '@system.prompt'
    
    @Entry
    @Component
    struct Test {
      private matrix1 = Matrix4.identity().transformPoint([100, 10])
      build() {
        Column() {
         Button("get Point")
          .onClick(() => {
           prompt.showToast({message:JSON.stringify(this.matrix1),duration:2000})
          }).backgroundColor(0x2788D9)
        }.width("100%").padding(50)
      }
    }
    ```

    ![](figures/222.gif)


