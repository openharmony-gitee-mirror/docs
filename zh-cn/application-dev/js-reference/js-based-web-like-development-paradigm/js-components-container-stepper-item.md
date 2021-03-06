# stepper-item<a name="ZH-CN_TOPIC_0000001127125034"></a>

步骤导航器子组件，作为步骤导航器某一个步骤的内容展示组件。

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>从API Version 5 开始支持。

## 权限列表<a name="section11257113618419"></a>

无

## 子组件<a name="section9288143101012"></a>

支持。

## 属性<a name="section2907183951110"></a>

除支持[通用属性](js-components-common-attributes.md)外，还支持如下属性：

<a name="table20633101642315"></a>
<table><thead align="left"><tr id="row663331618238"><th class="cellrowborder" valign="top" width="23.119999999999997%" id="mcps1.1.6.1.1"><p id="a45273e2103004ff3bdd3375013e96a2a"><a name="a45273e2103004ff3bdd3375013e96a2a"></a><a name="a45273e2103004ff3bdd3375013e96a2a"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="23.119999999999997%" id="mcps1.1.6.1.2"><p id="ad5b10d4a60e44bb4a8bbb3b4416d7b27"><a name="ad5b10d4a60e44bb4a8bbb3b4416d7b27"></a><a name="ad5b10d4a60e44bb4a8bbb3b4416d7b27"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="10.48%" id="mcps1.1.6.1.3"><p id="ab2ae3d9f60d6475ab95ba095851a9d07"><a name="ab2ae3d9f60d6475ab95ba095851a9d07"></a><a name="ab2ae3d9f60d6475ab95ba095851a9d07"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="7.5200000000000005%" id="mcps1.1.6.1.4"><p id="p824610360217"><a name="p824610360217"></a><a name="p824610360217"></a>必填</p>
</th>
<th class="cellrowborder" valign="top" width="35.76%" id="mcps1.1.6.1.5"><p id="af5c3b773ed0a42e589819a6c8d257ca1"><a name="af5c3b773ed0a42e589819a6c8d257ca1"></a><a name="af5c3b773ed0a42e589819a6c8d257ca1"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row5283312343"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p228421219417"><a name="p228421219417"></a><a name="p228421219417"></a>label</p>
</td>
<td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.2 "><p id="p1628411126418"><a name="p1628411126418"></a><a name="p1628411126418"></a><a href="#table119681501422">Label</a></p>
</td>
<td class="cellrowborder" valign="top" width="10.48%" headers="mcps1.1.6.1.3 "><p id="p228441219417"><a name="p228441219417"></a><a name="p228441219417"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.5200000000000005%" headers="mcps1.1.6.1.4 "><p id="p928417121844"><a name="p928417121844"></a><a name="p928417121844"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="35.76%" headers="mcps1.1.6.1.5 "><p id="p46212038248"><a name="p46212038248"></a><a name="p46212038248"></a>自定义步骤导航器底部步骤提示文本按钮属性，不支持动态修改。如果没有定义该属性，步骤导航器在中文语言环境下，使用“返回”和“下一步”文本按钮，在非中文语言环境下，使用“BACK”和“NEXT”文本按钮。针对第一个步骤，没有回退文本按钮，针对最后一个步骤，下一步文本按钮文本使用“开始”（中文语言）或者“START”（非中文语言）。</p>
</td>
</tr>
</tbody>
</table>

**表 1**  Label对象定义

<a name="table119681501422"></a>
<table><thead align="left"><tr id="row9968170228"><th class="cellrowborder" valign="top" width="11.06%" id="mcps1.2.5.1.1"><p id="p18968201227"><a name="p18968201227"></a><a name="p18968201227"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="9.08%" id="mcps1.2.5.1.2"><p id="p199691501328"><a name="p199691501328"></a><a name="p199691501328"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.450000000000001%" id="mcps1.2.5.1.3"><p id="p139699019213"><a name="p139699019213"></a><a name="p139699019213"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="71.41%" id="mcps1.2.5.1.4"><p id="p1969507219"><a name="p1969507219"></a><a name="p1969507219"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1496930728"><td class="cellrowborder" valign="top" width="11.06%" headers="mcps1.2.5.1.1 "><p id="p3969110127"><a name="p3969110127"></a><a name="p3969110127"></a>prevLabel</p>
</td>
<td class="cellrowborder" valign="top" width="9.08%" headers="mcps1.2.5.1.2 "><p id="p99691100212"><a name="p99691100212"></a><a name="p99691100212"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.450000000000001%" headers="mcps1.2.5.1.3 "><p id="p1996919011215"><a name="p1996919011215"></a><a name="p1996919011215"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="71.41%" headers="mcps1.2.5.1.4 "><p id="p8969202219"><a name="p8969202219"></a><a name="p8969202219"></a>步骤导航器底部回退文本按钮的描述文本。</p>
</td>
</tr>
<tr id="row296910827"><td class="cellrowborder" valign="top" width="11.06%" headers="mcps1.2.5.1.1 "><p id="p896910627"><a name="p896910627"></a><a name="p896910627"></a>nextLabel</p>
</td>
<td class="cellrowborder" valign="top" width="9.08%" headers="mcps1.2.5.1.2 "><p id="p1696900529"><a name="p1696900529"></a><a name="p1696900529"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.450000000000001%" headers="mcps1.2.5.1.3 "><p id="p18969301227"><a name="p18969301227"></a><a name="p18969301227"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="71.41%" headers="mcps1.2.5.1.4 "><p id="p159691801223"><a name="p159691801223"></a><a name="p159691801223"></a>步骤导航器底部下一步文本按钮的描述文本。</p>
</td>
</tr>
<tr id="row119116012913"><td class="cellrowborder" valign="top" width="11.06%" headers="mcps1.2.5.1.1 "><p id="p99121704918"><a name="p99121704918"></a><a name="p99121704918"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="9.08%" headers="mcps1.2.5.1.2 "><p id="p1912401095"><a name="p1912401095"></a><a name="p1912401095"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.450000000000001%" headers="mcps1.2.5.1.3 "><p id="p149121201396"><a name="p149121201396"></a><a name="p149121201396"></a>normal</p>
</td>
<td class="cellrowborder" valign="top" width="71.41%" headers="mcps1.2.5.1.4 "><p id="p491230493"><a name="p491230493"></a><a name="p491230493"></a>步骤导航器当前步骤的初始状态，可选值为：</p>
<a name="ul15229514162318"></a><a name="ul15229514162318"></a><ul id="ul15229514162318"><li>normal：正常状态，右侧文本按钮正常显示，可点击进入下一个步骤。</li></ul>
<a name="ul5182101916236"></a><a name="ul5182101916236"></a><ul id="ul5182101916236"><li>disabled：不可用状态，右侧文本按钮灰度显示，不可点击进入下一个步骤。</li></ul>
<a name="ul16451423182317"></a><a name="ul16451423182317"></a><ul id="ul16451423182317"><li>waiting：等待状态，右侧文本按钮不显示，使用等待进度条，不可点击进入下一个步骤。</li></ul>
</td>
</tr>
</tbody>
</table>

## 样式<a name="section1326042123512"></a>

除支持[通用样式](js-components-common-styles.md)外，还支持如下样式：

<a name="table1744514388541"></a>
<table><thead align="left"><tr id="row1244614388545"><th class="cellrowborder" valign="top" width="23.11768823117688%" id="mcps1.1.6.1.1"><p id="a4e80fb5a797c4328af30d59e2c570c71"><a name="a4e80fb5a797c4328af30d59e2c570c71"></a><a name="a4e80fb5a797c4328af30d59e2c570c71"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="20.477952204779523%" id="mcps1.1.6.1.2"><p id="a4238bd3a376645a3ad8498d3916ed6c8"><a name="a4238bd3a376645a3ad8498d3916ed6c8"></a><a name="a4238bd3a376645a3ad8498d3916ed6c8"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.869113088691131%" id="mcps1.1.6.1.3"><p id="a5ece9efc3a1d464a868f9557e4784a97"><a name="a5ece9efc3a1d464a868f9557e4784a97"></a><a name="a5ece9efc3a1d464a868f9557e4784a97"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="7.519248075192481%" id="mcps1.1.6.1.4"><p id="p117421754619"><a name="p117421754619"></a><a name="p117421754619"></a>必填</p>
</th>
<th class="cellrowborder" valign="top" width="40.01599840015999%" id="mcps1.1.6.1.5"><p id="a2454f35c1eef44b4bb681caaa3ce48fc"><a name="a2454f35c1eef44b4bb681caaa3ce48fc"></a><a name="a2454f35c1eef44b4bb681caaa3ce48fc"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row492070486"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p16782113422516"><a name="p16782113422516"></a><a name="p16782113422516"></a>color</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p678210342255"><a name="p678210342255"></a><a name="p678210342255"></a>&lt;color&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p0942146308"><a name="p0942146308"></a><a name="p0942146308"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p9782134122511"><a name="p9782134122511"></a><a name="p9782134122511"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p15360112213810"><a name="p15360112213810"></a><a name="p15360112213810"></a>文本颜色。</p>
</td>
</tr>
<tr id="row926613588711"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p15365537102518"><a name="p15365537102518"></a><a name="p15365537102518"></a>font-size</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p1636517375255"><a name="p1636517375255"></a><a name="p1636517375255"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p7365103717256"><a name="p7365103717256"></a><a name="p7365103717256"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p336663712252"><a name="p336663712252"></a><a name="p336663712252"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p836022215814"><a name="p836022215814"></a><a name="p836022215814"></a>文本大小。</p>
</td>
</tr>
<tr id="row1747615510720"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p3376124017256"><a name="p3376124017256"></a><a name="p3376124017256"></a>allow-scale</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p1437654010251"><a name="p1437654010251"></a><a name="p1437654010251"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1376154072515"><a name="p1376154072515"></a><a name="p1376154072515"></a>true</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p1937615404253"><a name="p1937615404253"></a><a name="p1937615404253"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p536014229815"><a name="p536014229815"></a><a name="p536014229815"></a>文本尺寸是否跟随系统设置字体缩放尺寸进行放大缩小。</p>
</td>
</tr>
<tr id="row79081352873"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p0781642162510"><a name="p0781642162510"></a><a name="p0781642162510"></a>font-style</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p107816428255"><a name="p107816428255"></a><a name="p107816428255"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p17811342142514"><a name="p17811342142514"></a><a name="p17811342142514"></a>normal</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p189135463810"><a name="p189135463810"></a><a name="p189135463810"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p10377104215812"><a name="p10377104215812"></a><a name="p10377104215812"></a>文本字体样式，可选值为：</p>
<a name="ul6878946122313"></a><a name="ul6878946122313"></a><ul id="ul6878946122313"><li>normal: 标准的字体样式；</li><li>italic: 斜体的字体样式。</li></ul>
</td>
</tr>
<tr id="row1033315491718"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p9764174572513"><a name="p9764174572513"></a><a name="p9764174572513"></a>font-weight</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p37641045112510"><a name="p37641045112510"></a><a name="p37641045112510"></a>number|string</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1976434511252"><a name="p1976434511252"></a><a name="p1976434511252"></a>normal</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p63843547813"><a name="p63843547813"></a><a name="p63843547813"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p107081551486"><a name="p107081551486"></a><a name="p107081551486"></a>文本字体粗细，number类型取值[100, 900]的整数（被100整除），默认为400，取值越大，字体越粗。string类型取值为：lighter、normal、bold、bolder。</p>
</td>
</tr>
<tr id="row387010448715"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1693494732511"><a name="p1693494732511"></a><a name="p1693494732511"></a>text-decoration</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p7934124713256"><a name="p7934124713256"></a><a name="p7934124713256"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1493416479256"><a name="p1493416479256"></a><a name="p1493416479256"></a>none</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p198071106919"><a name="p198071106919"></a><a name="p198071106919"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p169212584815"><a name="p169212584815"></a><a name="p169212584815"></a>文本修饰，可选值为：</p>
<a name="ul1768145382318"></a><a name="ul1768145382318"></a><ul id="ul1768145382318"><li>underline: 文本下划线修饰。</li><li>line-through: 穿过文本的修饰线。</li><li>none: 标准文本。</li></ul>
</td>
</tr>
<tr id="row279314411076"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1543212507250"><a name="p1543212507250"></a><a name="p1543212507250"></a>font-family</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p1243215092510"><a name="p1243215092510"></a><a name="p1243215092510"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p34321750192510"><a name="p34321750192510"></a><a name="p34321750192510"></a>sans-serif</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p19356791696"><a name="p19356791696"></a><a name="p19356791696"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p18361661099"><a name="p18361661099"></a><a name="p18361661099"></a>字体列表，用逗号分隔，每个字体用字体名或者字体族名设置。列表中第一个系统中存在的或者通过<a href="js-components-common-customizing-font.md">自定义字体</a>指定的字体，会被选中作为文本的字体。</p>
</td>
</tr>
</tbody>
</table>

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>-   不支持长宽样式，宽和父容器stepper一样，高是父容器stepper减去底部导航按钮的高度。
>-   不支持posit样式。

## 事件<a name="section121081858163714"></a>

除支持[通用事件](js-components-common-events.md)外，还支持如下事件：

<a name="table3706139102712"></a>
<table><thead align="left"><tr id="row3706394279"><th class="cellrowborder" valign="top" width="24.852485248524854%" id="mcps1.1.4.1.1"><p id="a426b8903842d48fa8012a24ff3c997eb"><a name="a426b8903842d48fa8012a24ff3c997eb"></a><a name="a426b8903842d48fa8012a24ff3c997eb"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="29.552955295529554%" id="mcps1.1.4.1.2"><p id="a53448ba47e5e4ae9bf7774c90820e970"><a name="a53448ba47e5e4ae9bf7774c90820e970"></a><a name="a53448ba47e5e4ae9bf7774c90820e970"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="45.5945594559456%" id="mcps1.1.4.1.3"><p id="add489ff50c444f24b759162c7f4bad9a"><a name="add489ff50c444f24b759162c7f4bad9a"></a><a name="add489ff50c444f24b759162c7f4bad9a"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row144051516142716"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p17545162122718"><a name="p17545162122718"></a><a name="p17545162122718"></a>appear</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p17545182113270"><a name="p17545182113270"></a><a name="p17545182113270"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p18545172132717"><a name="p18545172132717"></a><a name="p18545172132717"></a>当该步骤出现时触发。</p>
</td>
</tr>
<tr id="row79737130274"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p105451921102718"><a name="p105451921102718"></a><a name="p105451921102718"></a>disappear</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p254582112712"><a name="p254582112712"></a><a name="p254582112712"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p14545162142719"><a name="p14545162142719"></a><a name="p14545162142719"></a>当该步骤消失时触发。</p>
</td>
</tr>
</tbody>
</table>

## 方法<a name="section2279124532420"></a>

不支持[通用方法](js-components-common-methods.md)。

## 示例<a name="section10326712123215"></a>

详见[stepper示例](js-components-container-stepper.md)。

