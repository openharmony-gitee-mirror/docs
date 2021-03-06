# list<a name="ZH-CN_TOPIC_0000001127284836"></a>

列表包含一系列相同宽度的列表项。适合连续、多行呈现同类数据，例如图片和文本。

## 权限列表<a name="section11257113618419"></a>

无

## 子组件<a name="section9288143101012"></a>

仅支持<[list-item-group](js-components-container-list-item-group.md)\>和<[list-item](js-components-container-list-item.md)\>。

## 属性<a name="section2907183951110"></a>

除支持[通用属性](js-components-common-attributes.md)外，还支持如下属性：

<a name="table20633101642315"></a>
<table><thead align="left"><tr id="row663331618238"><th class="cellrowborder" valign="top" width="23.119999999999997%" id="mcps1.1.6.1.1"><p id="zh-cn_topic_0000001058340523_a9ba8c579217b4b8b841b035f1d28b20e"><a name="zh-cn_topic_0000001058340523_a9ba8c579217b4b8b841b035f1d28b20e"></a><a name="zh-cn_topic_0000001058340523_a9ba8c579217b4b8b841b035f1d28b20e"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="14.67%" id="mcps1.1.6.1.2"><p id="zh-cn_topic_0000001058340523_a633002333b024497914a4b172446f14e"><a name="zh-cn_topic_0000001058340523_a633002333b024497914a4b172446f14e"></a><a name="zh-cn_topic_0000001058340523_a633002333b024497914a4b172446f14e"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="10.92%" id="mcps1.1.6.1.3"><p id="zh-cn_topic_0000001058340523_a4950f7884c6540b9ad523ac34657d952"><a name="zh-cn_topic_0000001058340523_a4950f7884c6540b9ad523ac34657d952"></a><a name="zh-cn_topic_0000001058340523_a4950f7884c6540b9ad523ac34657d952"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="9.33%" id="mcps1.1.6.1.4"><p id="p824610360217"><a name="p824610360217"></a><a name="p824610360217"></a>必填</p>
</th>
<th class="cellrowborder" valign="top" width="41.959999999999994%" id="mcps1.1.6.1.5"><p id="zh-cn_topic_0000001058340523_a1313564aa9404a338447087d5918c17d"><a name="zh-cn_topic_0000001058340523_a1313564aa9404a338447087d5918c17d"></a><a name="zh-cn_topic_0000001058340523_a1313564aa9404a338447087d5918c17d"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row389219166580"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p32747328584"><a name="p32747328584"></a><a name="p32747328584"></a>scrollpage</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p1927413328589"><a name="p1927413328589"></a><a name="p1927413328589"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p142747324586"><a name="p142747324586"></a><a name="p142747324586"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p1827423217589"><a name="p1827423217589"></a><a name="p1827423217589"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p627473213585"><a name="p627473213585"></a><a name="p627473213585"></a>设置为true时，将 list 顶部页面中非 list 部分随 list 一起滑出可视区域，当list方向为row时，不支持此属性。</p>
</td>
</tr>
<tr id="row9893216145818"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p112749323589"><a name="p112749323589"></a><a name="p112749323589"></a>cachedcount</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p1427483225810"><a name="p1427483225810"></a><a name="p1427483225810"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p16274432145815"><a name="p16274432145815"></a><a name="p16274432145815"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p32741132185811"><a name="p32741132185811"></a><a name="p32741132185811"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p02741932195811"><a name="p02741932195811"></a><a name="p02741932195811"></a>长列表延迟加载时list-item最少缓存数量。</p>
<p id="p182741432115814"><a name="p182741432115814"></a><a name="p182741432115814"></a>可视区域外缓存的list-item数量少于该值时，会触发requestitem事件。</p>
</td>
</tr>
<tr id="row9893131620589"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p827410325586"><a name="p827410325586"></a><a name="p827410325586"></a>scrollbar</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p72741332125816"><a name="p72741332125816"></a><a name="p72741332125816"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p122741532125818"><a name="p122741532125818"></a><a name="p122741532125818"></a>off</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p1227413295813"><a name="p1227413295813"></a><a name="p1227413295813"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p142744322587"><a name="p142744322587"></a><a name="p142744322587"></a>侧边滑动栏的显示模式（当前只支持纵向）：</p>
<a name="ul162752325582"></a><a name="ul162752325582"></a><ul id="ul162752325582"><li>off：不显示。</li><li>auto：按需显示(触摸时显示，2s后消失)。</li><li>on：常驻显示。</li></ul>
</td>
</tr>
<tr id="row1089321620582"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p1275832125813"><a name="p1275832125813"></a><a name="p1275832125813"></a>scrolleffect</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p7275193216582"><a name="p7275193216582"></a><a name="p7275193216582"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p13275232125815"><a name="p13275232125815"></a><a name="p13275232125815"></a>spring</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p327520323585"><a name="p327520323585"></a><a name="p327520323585"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p1827516324585"><a name="p1827516324585"></a><a name="p1827516324585"></a>滑动效果，目前支持如下滑动效果：</p>
<a name="ul13275532195819"></a><a name="ul13275532195819"></a><ul id="ul13275532195819"><li>spring：弹性物理动效，滑动到边缘后可以根据初始速度或通过触摸事件继续滑动一段距离，松手后回弹。</li><li>fade：渐隐物理动效，滑动到边缘后展示一个波浪形的渐隐，根据速度和滑动距离的变化渐隐也会发送一定的变化。</li><li>no：滑动到边缘后无效果。</li></ul>
</td>
</tr>
<tr id="row208941516165811"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p1327573215812"><a name="p1327573215812"></a><a name="p1327573215812"></a>indexer</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p15275163245815"><a name="p15275163245815"></a><a name="p15275163245815"></a>boolean | Array&lt;string&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p427553220580"><a name="p427553220580"></a><a name="p427553220580"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p627613214585"><a name="p627613214585"></a><a name="p627613214585"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p1127613275818"><a name="p1127613275818"></a><a name="p1127613275818"></a>是否展示侧边栏快速字母索引栏。设置为true或者自定义索引时，索引栏会显示在列表右边界处。示例：</p>
<p id="p19276132105811"><a name="p19276132105811"></a><a name="p19276132105811"></a>"indexer" : "true"表示使用默认字母索引表。</p>
<p id="p10276133295813"><a name="p10276133295813"></a><a name="p10276133295813"></a>"indexer" : "false"表示无索引。</p>
<p id="p1027643295815"><a name="p1027643295815"></a><a name="p1027643295815"></a>"indexer" : ['#',‘1’,'2',‘3’,'4',‘5’,'6',‘7’,'8']表示自定义索引表。自定义时"#"必须要存在。</p>
<div class="note" id="note1752771418501"><a name="note1752771418501"></a><a name="note1752771418501"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul55231518155017"></a><a name="ul55231518155017"></a><ul id="ul55231518155017"><li>indexer属性生效需要flex-direction属性配合设置为column，且columns属性设置为1。</li><li>点击索引条进行列表项索引需要list-item子组件配合设置相应的<a href="js-components-container-list-item.md#section2907183951110">section属性</a>。</li></ul>
</div></div>
</td>
</tr>
<tr id="row1981645163320"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p105121047125317"><a name="p105121047125317"></a><a name="p105121047125317"></a>indexercircle<sup id="sup43038121535"><a name="sup43038121535"></a><a name="sup43038121535"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p8512114712538"><a name="p8512114712538"></a><a name="p8512114712538"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p551317471531"><a name="p551317471531"></a><a name="p551317471531"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p4513547195316"><a name="p4513547195316"></a><a name="p4513547195316"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p1898916471451"><a name="p1898916471451"></a><a name="p1898916471451"></a>是否为环形索引。</p>
<p id="p10513447125316"><a name="p10513447125316"></a><a name="p10513447125316"></a>穿戴设备默认为true，其他为false。indexer为false时不生效。</p>
</td>
</tr>
<tr id="row1926180153418"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p1370619211500"><a name="p1370619211500"></a><a name="p1370619211500"></a>indexermulti<sup id="sup1478641710316"><a name="sup1478641710316"></a><a name="sup1478641710316"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p13706112125019"><a name="p13706112125019"></a><a name="p13706112125019"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p1770622195017"><a name="p1770622195017"></a><a name="p1770622195017"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p97060218503"><a name="p97060218503"></a><a name="p97060218503"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p1768357350"><a name="p1768357350"></a><a name="p1768357350"></a>是否开启索引条多语言功能。</p>
<p id="p57061219500"><a name="p57061219500"></a><a name="p57061219500"></a>indexer为false时不生效。</p>
</td>
</tr>
<tr id="row289205623319"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p336515269516"><a name="p336515269516"></a><a name="p336515269516"></a>indexerbubble<sup id="sup3412121919314"><a name="sup3412121919314"></a><a name="sup3412121919314"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p836613263515"><a name="p836613263515"></a><a name="p836613263515"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p153661126165120"><a name="p153661126165120"></a><a name="p153661126165120"></a>true</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p0366182611512"><a name="p0366182611512"></a><a name="p0366182611512"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p15708185468"><a name="p15708185468"></a><a name="p15708185468"></a>是否开启索引切换的气泡提示。</p>
<p id="p12366132614518"><a name="p12366132614518"></a><a name="p12366132614518"></a>indexer为false时不生效。</p>
</td>
</tr>
<tr id="row19197115453311"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p191412818511"><a name="p191412818511"></a><a name="p191412818511"></a>divider<sup id="sup918814291347"><a name="sup918814291347"></a><a name="sup918814291347"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p3914284516"><a name="p3914284516"></a><a name="p3914284516"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p10914285514"><a name="p10914285514"></a><a name="p10914285514"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p8914148051"><a name="p8914148051"></a><a name="p8914148051"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p111882182061"><a name="p111882182061"></a><a name="p111882182061"></a>item是否自带分隔线。</p>
<p id="p20914284518"><a name="p20914284518"></a><a name="p20914284518"></a>其样式参考<a href="../../nottoctopics/zh-cn_topic_0000001131154746.md#section1071433432218">样式列表</a>的divider-color、divider-height、divider-length、divider-origin。</p>
</td>
</tr>
<tr id="row311191013583"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p9276123217583"><a name="p9276123217583"></a><a name="p9276123217583"></a>shapemode</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p1527610320588"><a name="p1527610320588"></a><a name="p1527610320588"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p17276832195815"><a name="p17276832195815"></a><a name="p17276832195815"></a>default</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p142761532145817"><a name="p142761532145817"></a><a name="p142761532145817"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p182761532205818"><a name="p182761532205818"></a><a name="p182761532205818"></a>侧边滑动栏的形状类型。</p>
<a name="ul4276203212589"></a><a name="ul4276203212589"></a><ul id="ul4276203212589"><li>default：不指定，跟随主题；</li><li>rect：矩形；</li><li>round：圆形。</li></ul>
</td>
</tr>
<tr id="row10121910145814"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p227683210584"><a name="p227683210584"></a><a name="p227683210584"></a>itemscale</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p2027673265811"><a name="p2027673265811"></a><a name="p2027673265811"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p1727603216580"><a name="p1727603216580"></a><a name="p1727603216580"></a>true</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p6276163212589"><a name="p6276163212589"></a><a name="p6276163212589"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p16277132135812"><a name="p16277132135812"></a><a name="p16277132135812"></a>焦点处理时，可以通过这个属性取消焦点进出的放大缩小效果。该效果仅在智能穿戴和智慧屏上生效。</p>
<div class="note" id="note113581896559"><a name="note113581896559"></a><a name="note113581896559"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p133581695550"><a name="p133581695550"></a><a name="p133581695550"></a>仅在columns样式为1的时候生效。</p>
</div></div>
</td>
</tr>
<tr id="row11341075811"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p13277123215580"><a name="p13277123215580"></a><a name="p13277123215580"></a>itemcenter</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p927717326586"><a name="p927717326586"></a><a name="p927717326586"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p192771432115817"><a name="p192771432115817"></a><a name="p192771432115817"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p18277732135814"><a name="p18277732135814"></a><a name="p18277732135814"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p1927713211588"><a name="p1927713211588"></a><a name="p1927713211588"></a>初始化页面和滑动后页面总是有一个item处于视口交叉轴的中心位置。该效果仅在智能穿戴上生效。</p>
</td>
</tr>
<tr id="row1465212481574"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p102776324585"><a name="p102776324585"></a><a name="p102776324585"></a>updateeffect</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p4277133275818"><a name="p4277133275818"></a><a name="p4277133275818"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p627763235813"><a name="p627763235813"></a><a name="p627763235813"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p1927893215584"><a name="p1927893215584"></a><a name="p1927893215584"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p3278032145815"><a name="p3278032145815"></a><a name="p3278032145815"></a>用于设置当list内部的item发生删除或新增时是否支持动效。</p>
<a name="ul8278153205815"></a><a name="ul8278153205815"></a><ul id="ul8278153205815"><li>false：新增删除item时无过渡动效。</li><li>true：新增删除item时播放过程动效。</li></ul>
</td>
</tr>
<tr id="row1788316557427"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p198831055124217"><a name="p198831055124217"></a><a name="p198831055124217"></a>chainanimation<sup id="sup13376443103416"><a name="sup13376443103416"></a><a name="sup13376443103416"></a>5+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p0883955174217"><a name="p0883955174217"></a><a name="p0883955174217"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p888305574219"><a name="p888305574219"></a><a name="p888305574219"></a>false</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p19884755204213"><a name="p19884755204213"></a><a name="p19884755204213"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p78841255154210"><a name="p78841255154210"></a><a name="p78841255154210"></a>用于设置当前list是否启用链式联动动效，开启后列表滑动以及顶部和底部拖拽时会有链式联动的效果。链式联动效果：list内的list-item间隔一定距离，在基本的滑动交互行为下，主动对象驱动从动对象进行联动，驱动效果遵循弹簧物理动效。</p>
<a name="ul1490293714519"></a><a name="ul1490293714519"></a><ul id="ul1490293714519"><li>false：不启用链式联动</li><li>true：启用链式联动<div class="note" id="note775214910343"><a name="note775214910343"></a><a name="note775214910343"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul99031432111819"></a><a name="ul99031432111819"></a><ul id="ul99031432111819"><li>不支持动态修改。</li><li>如同时配置了indexer，链式动效不生效。</li><li>如配置了链式动效，list-item的sticky不生效。</li></ul>
</div></div>
</li></ul>
</td>
</tr>
<tr id="row8177174618571"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p1278123295811"><a name="p1278123295811"></a><a name="p1278123295811"></a>scrollvibrate</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p6278203217582"><a name="p6278203217582"></a><a name="p6278203217582"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p327833265819"><a name="p327833265819"></a><a name="p327833265819"></a>true</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p12278193225810"><a name="p12278193225810"></a><a name="p12278193225810"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p19278163265812"><a name="p19278163265812"></a><a name="p19278163265812"></a>用于设置当list滑动时是否有振动效果，仅在智能穿戴场景生效，其他场景滑动无振动效果。</p>
<a name="ul5278113217581"></a><a name="ul5278113217581"></a><ul id="ul5278113217581"><li>true：列表滑动时有振动效果。</li><li>false：列表滑动时无振动效果。</li></ul>
</td>
</tr>
<tr id="row114931435579"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p2278932185814"><a name="p2278932185814"></a><a name="p2278932185814"></a>initialindex</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p627818324584"><a name="p627818324584"></a><a name="p627818324584"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p142783321586"><a name="p142783321586"></a><a name="p142783321586"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p20278123225811"><a name="p20278123225811"></a><a name="p20278123225811"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p627813212587"><a name="p627813212587"></a><a name="p627813212587"></a>用于设置当前List初次加载时视口起始位置显示的item，默认为0，即显示第一个item，如设置的序号超过了最后一个item的序号，则设置不生效，当同时设置了initialoffset属性时，当前属性不生效。当indexer为true或者scrollpage为true时，不生效。</p>
</td>
</tr>
<tr id="row950539135714"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p827963212580"><a name="p827963212580"></a><a name="p827963212580"></a>initialoffset</p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p227917321582"><a name="p227917321582"></a><a name="p227917321582"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p62791332105814"><a name="p62791332105814"></a><a name="p62791332105814"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p1527943212583"><a name="p1527943212583"></a><a name="p1527943212583"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p327920329582"><a name="p327920329582"></a><a name="p327920329582"></a>用于设置当前List初次加载时视口的起始偏移量，偏移量无法超过当前List可滑动的范围，如果超过会被截断为可滑动范围的极限值。当indexer为true或者scrollpage为true时，不生效。</p>
</td>
</tr>
<tr id="row1914605315918"><td class="cellrowborder" valign="top" width="23.119999999999997%" headers="mcps1.1.6.1.1 "><p id="p19147135375914"><a name="p19147135375914"></a><a name="p19147135375914"></a>selected<sup id="sup2083525912347"><a name="sup2083525912347"></a><a name="sup2083525912347"></a>5+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="14.67%" headers="mcps1.1.6.1.2 "><p id="p12147105375915"><a name="p12147105375915"></a><a name="p12147105375915"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="10.92%" headers="mcps1.1.6.1.3 "><p id="p161471753195920"><a name="p161471753195920"></a><a name="p161471753195920"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="9.33%" headers="mcps1.1.6.1.4 "><p id="p314745313591"><a name="p314745313591"></a><a name="p314745313591"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="41.959999999999994%" headers="mcps1.1.6.1.5 "><p id="p11147853145914"><a name="p11147853145914"></a><a name="p11147853145914"></a>指定当前列表中被选中激活的项，可选值为list-item的section属性值。</p>
</td>
</tr>
</tbody>
</table>

## 样式<a name="section5775351116"></a>

除支持[通用样式](js-components-common-styles.md)外，还支持如下样式：

<a name="table1744514388541"></a>
<table><thead align="left"><tr id="row1244614388545"><th class="cellrowborder" valign="top" width="23.11768823117688%" id="mcps1.1.6.1.1"><p id="ae8fba6e2bad749f49d7af2927756ecac"><a name="ae8fba6e2bad749f49d7af2927756ecac"></a><a name="ae8fba6e2bad749f49d7af2927756ecac"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="20.477952204779523%" id="mcps1.1.6.1.2"><p id="a4543b5564fb34df0b7d83c5640a46890"><a name="a4543b5564fb34df0b7d83c5640a46890"></a><a name="a4543b5564fb34df0b7d83c5640a46890"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="8.869113088691131%" id="mcps1.1.6.1.3"><p id="a779ef1afb2d74c0fac0e8014dd85e120"><a name="a779ef1afb2d74c0fac0e8014dd85e120"></a><a name="a779ef1afb2d74c0fac0e8014dd85e120"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="7.519248075192481%" id="mcps1.1.6.1.4"><p id="p117421754619"><a name="p117421754619"></a><a name="p117421754619"></a>必填</p>
</th>
<th class="cellrowborder" valign="top" width="40.01599840015999%" id="mcps1.1.6.1.5"><p id="aaed5c586aaf5480c8db9e53a6a22428c"><a name="aaed5c586aaf5480c8db9e53a6a22428c"></a><a name="aaed5c586aaf5480c8db9e53a6a22428c"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row194212174919"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p199724441985"><a name="p199724441985"></a><a name="p199724441985"></a>divider-color<sup id="sup3982558172012"><a name="sup3982558172012"></a><a name="sup3982558172012"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p097214420817"><a name="p097214420817"></a><a name="p097214420817"></a>&lt;color&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p2097211443820"><a name="p2097211443820"></a><a name="p2097211443820"></a>transparent</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p11972204415818"><a name="p11972204415818"></a><a name="p11972204415818"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p1397215441382"><a name="p1397215441382"></a><a name="p1397215441382"></a>item分隔线颜色，仅当list的divider属性为true时生效。</p>
</td>
</tr>
<tr id="row391641412910"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1098356680"><a name="p1098356680"></a><a name="p1098356680"></a>divider-height<sup id="sup19987635215"><a name="sup19987635215"></a><a name="sup19987635215"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p149835619814"><a name="p149835619814"></a><a name="p149835619814"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1498145614817"><a name="p1498145614817"></a><a name="p1498145614817"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p29815567820"><a name="p29815567820"></a><a name="p29815567820"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p10983561383"><a name="p10983561383"></a><a name="p10983561383"></a>item分隔线高度，仅当list的divider属性为true时生效。</p>
</td>
</tr>
<tr id="row28222110920"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1144015414911"><a name="p1144015414911"></a><a name="p1144015414911"></a>divider-length<sup id="sup5326118102117"><a name="sup5326118102117"></a><a name="sup5326118102117"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p3440174196"><a name="p3440174196"></a><a name="p3440174196"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p0440741193"><a name="p0440741193"></a><a name="p0440741193"></a>主轴宽度</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p15440541997"><a name="p15440541997"></a><a name="p15440541997"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p10440341697"><a name="p10440341697"></a><a name="p10440341697"></a>item分隔线长度，不设置时最大长度为主轴宽度，具体长度取决于divider-origin，仅当list的divider属性为true时生效。</p>
</td>
</tr>
<tr id="row46441281390"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1223216191395"><a name="p1223216191395"></a><a name="p1223216191395"></a>divider-origin<sup id="sup18714913122119"><a name="sup18714913122119"></a><a name="sup18714913122119"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p1232161919915"><a name="p1232161919915"></a><a name="p1232161919915"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p723231910913"><a name="p723231910913"></a><a name="p723231910913"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p3232141916912"><a name="p3232141916912"></a><a name="p3232141916912"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p42327191895"><a name="p42327191895"></a><a name="p42327191895"></a>item分隔线相对于item主轴起点位置的偏移量，仅当list的divider属性为true时生效。</p>
</td>
</tr>
<tr id="row39106404819"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p11283866482"><a name="p11283866482"></a><a name="p11283866482"></a>flex-direction</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p7283162488"><a name="p7283162488"></a><a name="p7283162488"></a>string</p>
<p id="p182831368480"><a name="p182831368480"></a><a name="p182831368480"></a></p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p0283762488"><a name="p0283762488"></a><a name="p0283762488"></a>column</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p172837614485"><a name="p172837614485"></a><a name="p172837614485"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p172837654814"><a name="p172837654814"></a><a name="p172837654814"></a>设置flex容器主轴的方向，指定flex项如何放置在flex容器中，可选值为：</p>
<a name="ul132831763482"></a><a name="ul132831763482"></a><ul id="ul132831763482"><li>column：主轴为纵向。</li><li>row：主轴为横向。</li></ul>
<p id="p132831263486"><a name="p132831263486"></a><a name="p132831263486"></a>其他组件默认值为row，在list组件中默认值为column。</p>
</td>
</tr>
<tr id="row114441253204717"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p192847684817"><a name="p192847684817"></a><a name="p192847684817"></a>columns</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p92848613481"><a name="p92848613481"></a><a name="p92848613481"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1928410616485"><a name="p1928410616485"></a><a name="p1928410616485"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p192844611485"><a name="p192844611485"></a><a name="p192844611485"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p1928418624820"><a name="p1928418624820"></a><a name="p1928418624820"></a>list交叉轴方向的显示列数，默认为1列。</p>
<div class="note" id="note87762014175811"><a name="note87762014175811"></a><a name="note87762014175811"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p157761214205810"><a name="p157761214205810"></a><a name="p157761214205810"></a>设置多列时，在list交叉轴上进行均分，每一列大小相同。</p>
</div></div>
</td>
</tr>
<tr id="row2220195185518"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p12617942184311"><a name="p12617942184311"></a><a name="p12617942184311"></a>align-items</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p15617194264312"><a name="p15617194264312"></a><a name="p15617194264312"></a>string</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p061744213433"><a name="p061744213433"></a><a name="p061744213433"></a>stretch</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p12617154214437"><a name="p12617154214437"></a><a name="p12617154214437"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p9617542124318"><a name="p9617542124318"></a><a name="p9617542124318"></a>list每一列交叉轴上的对齐格式，可选值为：</p>
<a name="ul166171442134312"></a><a name="ul166171442134312"></a><ul id="ul166171442134312"><li>stretch：弹性元素被在交叉轴方向被拉伸到与容器相同的高度或宽度。</li><li>flex-start：元素向交叉轴起点对齐。</li><li>flex-end：元素向交叉轴终点对齐。</li><li>center：元素在交叉轴居中。<div class="note" id="note10891229703"><a name="note10891229703"></a><a name="note10891229703"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p18891029105"><a name="p18891029105"></a><a name="p18891029105"></a>align-items样式作用在每一列的子元素上，列与列之间采用均分方式布局。</p>
</div></div>
</li></ul>
</td>
</tr>
<tr id="row487325034719"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p2028420617487"><a name="p2028420617487"></a><a name="p2028420617487"></a>item-extent</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p828496164810"><a name="p828496164810"></a><a name="p828496164810"></a>&lt;length&gt; | &lt;percentage&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p928413644818"><a name="p928413644818"></a><a name="p928413644818"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p2028416134815"><a name="p2028416134815"></a><a name="p2028416134815"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p18284660488"><a name="p18284660488"></a><a name="p18284660488"></a>设置内部item为固定大小，设置为百分比格式时，指相对于list的视口主轴方向长度的百分比。</p>
</td>
</tr>
<tr id="row99041447114713"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p172840624815"><a name="p172840624815"></a><a name="p172840624815"></a>fade-color</p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p132851863484"><a name="p132851863484"></a><a name="p132851863484"></a><span>&lt;</span><span>color</span><span>&gt;</span></p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p1728506174819"><a name="p1728506174819"></a><a name="p1728506174819"></a>grey</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p22852060481"><a name="p22852060481"></a><a name="p22852060481"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p428518694818"><a name="p428518694818"></a><a name="p428518694818"></a>设置渐隐物理动效的颜色。当滑动效果设置为渐隐物理动效时生效。</p>
</td>
</tr>
<tr id="row023410442716"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p829911534213"><a name="p829911534213"></a><a name="p829911534213"></a>scrollbar-color<sup id="sup843916381239"><a name="sup843916381239"></a><a name="sup843916381239"></a>6+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p122991553112113"><a name="p122991553112113"></a><a name="p122991553112113"></a>&lt;color&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p17299253132120"><a name="p17299253132120"></a><a name="p17299253132120"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p9299135342110"><a name="p9299135342110"></a><a name="p9299135342110"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p14300165317215"><a name="p14300165317215"></a><a name="p14300165317215"></a>设置滚动条的颜色。</p>
</td>
</tr>
<tr id="row1117810274"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p1433575912212"><a name="p1433575912212"></a><a name="p1433575912212"></a>scrollbar-width<sup id="sup10700174022317"><a name="sup10700174022317"></a><a name="sup10700174022317"></a>6+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p3335165919217"><a name="p3335165919217"></a><a name="p3335165919217"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p6335175914219"><a name="p6335175914219"></a><a name="p6335175914219"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p13335759172115"><a name="p13335759172115"></a><a name="p13335759172115"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p533510595217"><a name="p533510595217"></a><a name="p533510595217"></a>设置滚动条的宽度。</p>
</td>
</tr>
<tr id="row11452128142314"><td class="cellrowborder" valign="top" width="23.11768823117688%" headers="mcps1.1.6.1.1 "><p id="p99726914238"><a name="p99726914238"></a><a name="p99726914238"></a>scrollbar-offset<sup id="sup697216902311"><a name="sup697216902311"></a><a name="sup697216902311"></a>6+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="20.477952204779523%" headers="mcps1.1.6.1.2 "><p id="p119725918233"><a name="p119725918233"></a><a name="p119725918233"></a>&lt;length&gt;</p>
</td>
<td class="cellrowborder" valign="top" width="8.869113088691131%" headers="mcps1.1.6.1.3 "><p id="p79725972313"><a name="p79725972313"></a><a name="p79725972313"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="7.519248075192481%" headers="mcps1.1.6.1.4 "><p id="p1297210918239"><a name="p1297210918239"></a><a name="p1297210918239"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="40.01599840015999%" headers="mcps1.1.6.1.5 "><p id="p17972694239"><a name="p17972694239"></a><a name="p17972694239"></a>设置滚动条距离List默认位置的偏移量，只支持正数，默认位置在List右边缘，可以通过这个偏移量调整滚动条的水平位置，如果滚动条绘制在list外部，而list父组件有裁剪，会导致滚动条被裁剪。</p>
</td>
</tr>
</tbody>
</table>

## 事件<a name="section471854810515"></a>

除支持[通用事件](js-components-common-events.md)外，还支持如下事件：

<a name="table12718648205119"></a>
<table><thead align="left"><tr id="row17185480518"><th class="cellrowborder" valign="top" width="24.852485248524854%" id="mcps1.1.4.1.1"><p id="p14718114825114"><a name="p14718114825114"></a><a name="p14718114825114"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="29.552955295529554%" id="mcps1.1.4.1.2"><p id="p137181948105111"><a name="p137181948105111"></a><a name="p137181948105111"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="45.5945594559456%" id="mcps1.1.4.1.3"><p id="p18718164812518"><a name="p18718164812518"></a><a name="p18718164812518"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row0718194813519"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p971894825110"><a name="p971894825110"></a><a name="p971894825110"></a>indexerchange<sup id="sup27189486514"><a name="sup27189486514"></a><a name="sup27189486514"></a><span>5+</span></sup></p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p197191148155114"><a name="p197191148155114"></a><a name="p197191148155114"></a>{ local: booleanValue }</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p1871920489510"><a name="p1871920489510"></a><a name="p1871920489510"></a>多语言索引条切换事件，仅当indexer属性为true，indexermulti为true时生效。booleanValue可能值为true或者false：</p>
<a name="ul18719104820516"></a><a name="ul18719104820516"></a><ul id="ul18719104820516"><li>true: 当前展示本地索引。</li><li>false: 当前展示字母索引。</li></ul>
</td>
</tr>
<tr id="row4719114805113"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p157191048155110"><a name="p157191048155110"></a><a name="p157191048155110"></a>scroll</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p177191548175111"><a name="p177191548175111"></a><a name="p177191548175111"></a>{ scrollX: scrollXValue, scrollY: scrollYValue, scrollState: stateValue }</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p1571914895114"><a name="p1571914895114"></a><a name="p1571914895114"></a>列表滑动的偏移量和状态回调。</p>
<p id="p13719164815112"><a name="p13719164815112"></a><a name="p13719164815112"></a>stateValue: 0表示列表滑动已经停止。</p>
<p id="p1719154885113"><a name="p1719154885113"></a><a name="p1719154885113"></a>stateValue: 1表示列表正在用户触摸状态下滑动。</p>
<p id="p8719148105112"><a name="p8719148105112"></a><a name="p8719148105112"></a>stateValue: 2表示列表正在用户松手状态下滑动。</p>
</td>
</tr>
<tr id="row1371954819511"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p671984817514"><a name="p671984817514"></a><a name="p671984817514"></a>scrollbottom</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p1971944810515"><a name="p1971944810515"></a><a name="p1971944810515"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p371984855113"><a name="p371984855113"></a><a name="p371984855113"></a>当前列表已滑动到底部位置。</p>
</td>
</tr>
<tr id="row1671944812519"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p971919481515"><a name="p971919481515"></a><a name="p971919481515"></a>scrolltop</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p12719348135112"><a name="p12719348135112"></a><a name="p12719348135112"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p127193483517"><a name="p127193483517"></a><a name="p127193483517"></a>当前列表已滑动到顶部位置。</p>
</td>
</tr>
<tr id="row17209489513"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p672034817518"><a name="p672034817518"></a><a name="p672034817518"></a>scrollend</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p67202487511"><a name="p67202487511"></a><a name="p67202487511"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p1472054895112"><a name="p1472054895112"></a><a name="p1472054895112"></a>列表滑动已经结束。</p>
</td>
</tr>
<tr id="row27207484515"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p67201048125114"><a name="p67201048125114"></a><a name="p67201048125114"></a>scrolltouchup</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p1720164814510"><a name="p1720164814510"></a><a name="p1720164814510"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p17720548105118"><a name="p17720548105118"></a><a name="p17720548105118"></a>手指已经抬起且列表仍在惯性滑动。</p>
</td>
</tr>
<tr id="row18720104812512"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p14720174820515"><a name="p14720174820515"></a><a name="p14720174820515"></a>requestitem</p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p572034875112"><a name="p572034875112"></a><a name="p572034875112"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p272034815115"><a name="p272034815115"></a><a name="p272034815115"></a>请求创建新的list-item。</p>
<p id="p1372014820516"><a name="p1372014820516"></a><a name="p1372014820516"></a>长列表延迟加载时，可视区域外缓存的list-item数量少于cachedcount时，会触发该事件。</p>
</td>
</tr>
<tr id="row16353171781416"><td class="cellrowborder" valign="top" width="24.852485248524854%" headers="mcps1.1.4.1.1 "><p id="p13354161718142"><a name="p13354161718142"></a><a name="p13354161718142"></a>rotate<sup id="sup915919368206"><a name="sup915919368206"></a><a name="sup915919368206"></a>7+</sup></p>
</td>
<td class="cellrowborder" valign="top" width="29.552955295529554%" headers="mcps1.1.4.1.2 "><p id="p1135419179146"><a name="p1135419179146"></a><a name="p1135419179146"></a>{ rotateValue: number }</p>
</td>
<td class="cellrowborder" valign="top" width="45.5945594559456%" headers="mcps1.1.4.1.3 "><p id="p1835471721415"><a name="p1835471721415"></a><a name="p1835471721415"></a>返回表冠旋转角度增量值，仅智能穿戴支持。</p>
</td>
</tr>
</tbody>
</table>

## 方法<a name="section47669296127"></a>

支持[通用方法](js-components-common-methods.md)外，还支持如下方法：

<a name="t0c307a0cf3734cb28f3adf6af246a486"></a>
<table><thead align="left"><tr id="r83b0c5b4f4b54874b1b3d7a36bcfa36b"><th class="cellrowborder" valign="top" width="14.09%" id="mcps1.1.4.1.1"><p id="af4002018158a424c9fe9ad1a0e8a395f"><a name="af4002018158a424c9fe9ad1a0e8a395f"></a><a name="af4002018158a424c9fe9ad1a0e8a395f"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="34.910000000000004%" id="mcps1.1.4.1.2"><p id="a08987b2b1bc34babb92dd601235b0e24"><a name="a08987b2b1bc34babb92dd601235b0e24"></a><a name="a08987b2b1bc34babb92dd601235b0e24"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="51%" id="mcps1.1.4.1.3"><p id="a5e3e3d76323a4ebe96e1bdb1d1c338eb"><a name="a5e3e3d76323a4ebe96e1bdb1d1c338eb"></a><a name="a5e3e3d76323a4ebe96e1bdb1d1c338eb"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="r6eb16143d32645c2ae58f1e4857b0d99"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="a16f9fd69364541c3bf57f9b2305ba51f"><a name="a16f9fd69364541c3bf57f9b2305ba51f"></a><a name="a16f9fd69364541c3bf57f9b2305ba51f"></a>scrollTo</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="abfb4febc1ae4429b8f593e96c50c9bc7"><a name="abfb4febc1ae4429b8f593e96c50c9bc7"></a><a name="abfb4febc1ae4429b8f593e96c50c9bc7"></a>{ index: number(指定位置) }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="a75c53230ef704966b5b25d2e2606584f"><a name="a75c53230ef704966b5b25d2e2606584f"></a><a name="a75c53230ef704966b5b25d2e2606584f"></a>list滑动到指定index的item位置。</p>
</td>
</tr>
<tr id="r9c30e9310fb349a4bf157e92668927fc"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="a8ce0c025f94046a89cfe7a3d4e20d802"><a name="a8ce0c025f94046a89cfe7a3d4e20d802"></a><a name="a8ce0c025f94046a89cfe7a3d4e20d802"></a>scrollBy</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="ae74f4613d9a44d7f890b38e10b61e249"><a name="ae74f4613d9a44d7f890b38e10b61e249"></a><a name="ae74f4613d9a44d7f890b38e10b61e249"></a><a href="#t54327f53ea104788bc430b9047ecb47b">ScrollParam</a></p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="a5a3997da89d649f0ac1c71461d953294"><a name="a5a3997da89d649f0ac1c71461d953294"></a><a name="a5a3997da89d649f0ac1c71461d953294"></a>触发list滑动一段距离。</p>
<p id="a0767362b2b4a4535a06cb42e483b14cd"><a name="a0767362b2b4a4535a06cb42e483b14cd"></a><a name="a0767362b2b4a4535a06cb42e483b14cd"></a>智慧屏特有方法。</p>
</td>
</tr>
<tr id="row10674141618528"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p1166501614521"><a name="p1166501614521"></a><a name="p1166501614521"></a>scrollTop</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p13665201655211"><a name="p13665201655211"></a><a name="p13665201655211"></a>{ smooth: boolean }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p1466520168521"><a name="p1466520168521"></a><a name="p1466520168521"></a>smooth缺省为false，表示直接滚动到顶部。</p>
<p id="p1166519160524"><a name="p1166519160524"></a><a name="p1166519160524"></a>smooth为true，表示平滑滚动到顶部。</p>
</td>
</tr>
<tr id="row1067461665217"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p96651616195214"><a name="p96651616195214"></a><a name="p96651616195214"></a>scrollBottom</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p566501617522"><a name="p566501617522"></a><a name="p566501617522"></a>{ smooth: boolean }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p1966571635219"><a name="p1966571635219"></a><a name="p1966571635219"></a>smooth缺省为false，表示直接滚动到底部。</p>
<p id="p1566513161529"><a name="p1566513161529"></a><a name="p1566513161529"></a>smooth为true，表示平滑滚动到底部。</p>
</td>
</tr>
<tr id="row667481665218"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p966520161520"><a name="p966520161520"></a><a name="p966520161520"></a>scrollPage</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p1166551610522"><a name="p1166551610522"></a><a name="p1166551610522"></a>{ reverse: boolean, smooth: boolean }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p156651016205211"><a name="p156651016205211"></a><a name="p156651016205211"></a>reverse缺省值为false，表示下一页，无完整页则滚动到底部。</p>
<p id="p11665141617522"><a name="p11665141617522"></a><a name="p11665141617522"></a>reverse为true，表示上一页，无完整页则滚动到顶部。</p>
<p id="p466513161522"><a name="p466513161522"></a><a name="p466513161522"></a>smooth缺省值为false，表示直接滚动一页。</p>
<p id="p5665131615528"><a name="p5665131615528"></a><a name="p5665131615528"></a>smooth为true，表示平滑滚动一页。</p>
</td>
</tr>
<tr id="row13674616205216"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p176652164528"><a name="p176652164528"></a><a name="p176652164528"></a>scrollArrow</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p166513161529"><a name="p166513161529"></a><a name="p166513161529"></a>{ reverse: boolean, smooth: boolean }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p1966551617521"><a name="p1966551617521"></a><a name="p1966551617521"></a>reverse缺省值为false，表示向底部方向滑动一段距离，无足够距离则滚动到底部。</p>
<p id="p266511168524"><a name="p266511168524"></a><a name="p266511168524"></a>reverse为true，表示向顶部方向滑动一段距离，无足够距离则滚动到顶部。</p>
<p id="p466510161529"><a name="p466510161529"></a><a name="p466510161529"></a>smooth缺省值为false，表示直接滚动。</p>
<p id="p966561612526"><a name="p966561612526"></a><a name="p966561612526"></a>smooth为true，表示平滑滚动。</p>
</td>
</tr>
<tr id="row146741516135215"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p16666161613523"><a name="p16666161613523"></a><a name="p16666161613523"></a>collapseGroup</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p466641685216"><a name="p466641685216"></a><a name="p466641685216"></a>{ groupid: string }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p206661165523"><a name="p206661165523"></a><a name="p206661165523"></a>收拢指定的group。</p>
<p id="p15666516205215"><a name="p15666516205215"></a><a name="p15666516205215"></a>groupid：需要收拢的group的id。</p>
<p id="p1566613167526"><a name="p1566613167526"></a><a name="p1566613167526"></a>当groupid未指定时收拢所有的group。</p>
</td>
</tr>
<tr id="row2674171665212"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p16666716155214"><a name="p16666716155214"></a><a name="p16666716155214"></a>expandGroup</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p1466681665219"><a name="p1466681665219"></a><a name="p1466681665219"></a>{ groupid: string }</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p11666816135210"><a name="p11666816135210"></a><a name="p11666816135210"></a>展开指定的group。</p>
<p id="p1766615169528"><a name="p1766615169528"></a><a name="p1766615169528"></a>groupid：需要展开的group的id。</p>
<p id="p1766616164528"><a name="p1766616164528"></a><a name="p1766616164528"></a>当groupid未指定时展开所有的group。</p>
</td>
</tr>
<tr id="row9562194955312"><td class="cellrowborder" valign="top" width="14.09%" headers="mcps1.1.4.1.1 "><p id="p4562174912536"><a name="p4562174912536"></a><a name="p4562174912536"></a>currentOffset</p>
</td>
<td class="cellrowborder" valign="top" width="34.910000000000004%" headers="mcps1.1.4.1.2 "><p id="p5562449185318"><a name="p5562449185318"></a><a name="p5562449185318"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.1.4.1.3 "><p id="p8563144914534"><a name="p8563144914534"></a><a name="p8563144914534"></a>返回当前滑动的偏移量。返回值类型是Object，返回值说明请见<a href="#table1145513617576">表2</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 1**  ScrollParam

<a name="t54327f53ea104788bc430b9047ecb47b"></a>
<table><thead align="left"><tr id="r6bc769560d884ebca11d7ef155cfc00c"><th class="cellrowborder" valign="top" width="12.000000000000002%" id="mcps1.2.6.1.1"><p id="a2b340d5b063045f9b972339877932f7d"><a name="a2b340d5b063045f9b972339877932f7d"></a><a name="a2b340d5b063045f9b972339877932f7d"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="22.000000000000004%" id="mcps1.2.6.1.2"><p id="a9710da1e083c4c4980317ab1772446a1"><a name="a9710da1e083c4c4980317ab1772446a1"></a><a name="a9710da1e083c4c4980317ab1772446a1"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="24.000000000000004%" id="mcps1.2.6.1.3"><p id="a273155109e9b41b1876c7b4944800ee4"><a name="a273155109e9b41b1876c7b4944800ee4"></a><a name="a273155109e9b41b1876c7b4944800ee4"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="21.000000000000004%" id="mcps1.2.6.1.4"><p id="ae31408099fa24514bac47cf09a9e7b1a"><a name="ae31408099fa24514bac47cf09a9e7b1a"></a><a name="ae31408099fa24514bac47cf09a9e7b1a"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="21.000000000000004%" id="mcps1.2.6.1.5"><p id="a333063706a09429cbe9ac81130d2b6cc"><a name="a333063706a09429cbe9ac81130d2b6cc"></a><a name="a333063706a09429cbe9ac81130d2b6cc"></a>备注</p>
</th>
</tr>
</thead>
<tbody><tr id="r6d4c75c9670d49ada849ec9f6bef83dd"><td class="cellrowborder" valign="top" width="12.000000000000002%" headers="mcps1.2.6.1.1 "><p id="ac4d9ce9a62d9442cb65658878f44e018"><a name="ac4d9ce9a62d9442cb65658878f44e018"></a><a name="ac4d9ce9a62d9442cb65658878f44e018"></a>dx</p>
</td>
<td class="cellrowborder" valign="top" width="22.000000000000004%" headers="mcps1.2.6.1.2 "><p id="aa6b8f1f0155a4954aab3a9609cadaf3a"><a name="aa6b8f1f0155a4954aab3a9609cadaf3a"></a><a name="aa6b8f1f0155a4954aab3a9609cadaf3a"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="24.000000000000004%" headers="mcps1.2.6.1.3 "><p id="a95db84bc6a774d029883ad1abae2d022"><a name="a95db84bc6a774d029883ad1abae2d022"></a><a name="a95db84bc6a774d029883ad1abae2d022"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.4 "><p id="aaa6df3c43c9b47bf81b339edcae98840"><a name="aaa6df3c43c9b47bf81b339edcae98840"></a><a name="aaa6df3c43c9b47bf81b339edcae98840"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.5 "><p id="aaffe44e874d74b6297ea7841258cb941"><a name="aaffe44e874d74b6297ea7841258cb941"></a><a name="aaffe44e874d74b6297ea7841258cb941"></a>水平方向滑动的偏移量，单位为px。</p>
</td>
</tr>
<tr id="rf56d36eb7a184adc843f20b499344ed6"><td class="cellrowborder" valign="top" width="12.000000000000002%" headers="mcps1.2.6.1.1 "><p id="acb8223e7297d4dbfa243b4b974c92560"><a name="acb8223e7297d4dbfa243b4b974c92560"></a><a name="acb8223e7297d4dbfa243b4b974c92560"></a>dy</p>
</td>
<td class="cellrowborder" valign="top" width="22.000000000000004%" headers="mcps1.2.6.1.2 "><p id="aa88695593f93485a9b64158a7e05cda4"><a name="aa88695593f93485a9b64158a7e05cda4"></a><a name="aa88695593f93485a9b64158a7e05cda4"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="24.000000000000004%" headers="mcps1.2.6.1.3 "><p id="a08e26d1dfd3e406b849dfaa715b0e985"><a name="a08e26d1dfd3e406b849dfaa715b0e985"></a><a name="a08e26d1dfd3e406b849dfaa715b0e985"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.4 "><p id="aede3e64e10724335b9297743fece7e4a"><a name="aede3e64e10724335b9297743fece7e4a"></a><a name="aede3e64e10724335b9297743fece7e4a"></a>0</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.5 "><p id="ade99317ad7354fee8e88ca282cf70446"><a name="ade99317ad7354fee8e88ca282cf70446"></a><a name="ade99317ad7354fee8e88ca282cf70446"></a>垂直方向滑动的偏移量，单位为px。</p>
</td>
</tr>
<tr id="r69d5b3d9c60a4a5ea242be132f754948"><td class="cellrowborder" valign="top" width="12.000000000000002%" headers="mcps1.2.6.1.1 "><p id="ae0636046822644c7b7a5289fbbcd53e6"><a name="ae0636046822644c7b7a5289fbbcd53e6"></a><a name="ae0636046822644c7b7a5289fbbcd53e6"></a>smooth</p>
</td>
<td class="cellrowborder" valign="top" width="22.000000000000004%" headers="mcps1.2.6.1.2 "><p id="a7d930786d83a4f9f92a4ba4e6cbb9db0"><a name="a7d930786d83a4f9f92a4ba4e6cbb9db0"></a><a name="a7d930786d83a4f9f92a4ba4e6cbb9db0"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="24.000000000000004%" headers="mcps1.2.6.1.3 "><p id="a643ff67584184620885e6ee1fddee8cb"><a name="a643ff67584184620885e6ee1fddee8cb"></a><a name="a643ff67584184620885e6ee1fddee8cb"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.4 "><p id="ac86052e652c54edead6588ad0932a118"><a name="ac86052e652c54edead6588ad0932a118"></a><a name="ac86052e652c54edead6588ad0932a118"></a>true</p>
</td>
<td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.6.1.5 "><p id="a1a8906b49d5e48f98a068f339df880e9"><a name="a1a8906b49d5e48f98a068f339df880e9"></a><a name="a1a8906b49d5e48f98a068f339df880e9"></a>列表位置跳转时是否有滑动动画。</p>
</td>
</tr>
</tbody>
</table>

**表 2**  currentOffset返回对象属性说明

<a name="table1145513617576"></a>
<table><thead align="left"><tr id="row1445543665717"><th class="cellrowborder" valign="top" width="21.82%" id="mcps1.2.4.1.1"><p id="p0455183695711"><a name="p0455183695711"></a><a name="p0455183695711"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.4.1.2"><p id="p2045533685711"><a name="p2045533685711"></a><a name="p2045533685711"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="38.18%" id="mcps1.2.4.1.3"><p id="p144557363572"><a name="p144557363572"></a><a name="p144557363572"></a>备注</p>
</th>
</tr>
</thead>
<tbody><tr id="row545516365576"><td class="cellrowborder" valign="top" width="21.82%" headers="mcps1.2.4.1.1 "><p id="p6455136135712"><a name="p6455136135712"></a><a name="p6455136135712"></a>x</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.4.1.2 "><p id="p14456113625711"><a name="p14456113625711"></a><a name="p14456113625711"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="38.18%" headers="mcps1.2.4.1.3 "><p id="p19456436165717"><a name="p19456436165717"></a><a name="p19456436165717"></a>当前x轴滑动偏移量，单位为px。</p>
</td>
</tr>
<tr id="row134561936125711"><td class="cellrowborder" valign="top" width="21.82%" headers="mcps1.2.4.1.1 "><p id="p194561736145714"><a name="p194561736145714"></a><a name="p194561736145714"></a>y</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.4.1.2 "><p id="p1345612364579"><a name="p1345612364579"></a><a name="p1345612364579"></a>number</p>
</td>
<td class="cellrowborder" valign="top" width="38.18%" headers="mcps1.2.4.1.3 "><p id="p1144122515599"><a name="p1144122515599"></a><a name="p1144122515599"></a>当前y轴滑动偏移量，单位为px。</p>
</td>
</tr>
</tbody>
</table>

## 示例<a name="section24931424488"></a>

```
<!-- index.hml -->
<div class="container">
  <list class="todo-wrapper">
    <list-item for="{{todolist}}" class="todo-item">
      <text class="todo-title">{{$item.title}}</text>
      <text class="todo-title">{{$item.date}}</text>
    </list-item>
  </list>
</div>
```

```
// index.js
export default {
  data: {
    todolist: [{
      title: '刷题',
      date: '2021-12-31 10:00:00',
    }, {
      title: '看电影',
      date: '2021-12-31 20:00:00',
    }],
  },
}
```

```
/* index.css */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  left: 0px;
  top: 0px;
  width: 454px;
  height: 454px;
}
.todo-wrapper {
  width: 454px;
  height: 300px;
}
.todo-item {
  width: 454px;
  height: 80px;
  flex-direction: column;
}
.todo-title {
  width: 454px;
  height: 40px;
  text-align: center;
}
```

![](figures/33.png)

