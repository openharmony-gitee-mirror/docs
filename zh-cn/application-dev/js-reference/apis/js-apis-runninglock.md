# Runninglock锁<a name="ZH-CN_TOPIC_0000001133776274"></a>

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>从 API Version 7 开始支持。

## 导入模块<a name="s56d19203690d4782bfc74069abb6bd71"></a>

```
import runninglock from '@ohos.runningLock';
```

## 权限<a name="section11257113618419"></a>

申请、使用锁的权限：ohos.permission.RUNNING\_LOCK

## RunningLockType<a name="section7299123218370"></a>

RunningLock锁的类型。

<a name="table1540155452420"></a>
<table><thead align="left"><tr id="row1947713549244"><th class="cellrowborder" valign="top" width="30.78%" id="mcps1.1.4.1.1"><p id="p74771754102410"><a name="p74771754102410"></a><a name="p74771754102410"></a>名称</p>
</th>
<th class="cellrowborder" valign="top" width="11.52%" id="mcps1.1.4.1.2"><p id="p1047755412411"><a name="p1047755412411"></a><a name="p1047755412411"></a>默认值</p>
</th>
<th class="cellrowborder" valign="top" width="57.699999999999996%" id="mcps1.1.4.1.3"><p id="p12478954132419"><a name="p12478954132419"></a><a name="p12478954132419"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1247811541240"><td class="cellrowborder" valign="top" width="30.78%" headers="mcps1.1.4.1.1 "><p id="p11478654162419"><a name="p11478654162419"></a><a name="p11478654162419"></a>BACKGROUND</p>
</td>
<td class="cellrowborder" valign="top" width="11.52%" headers="mcps1.1.4.1.2 "><p id="p9478135414243"><a name="p9478135414243"></a><a name="p9478135414243"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="57.699999999999996%" headers="mcps1.1.4.1.3 "><p id="p12478654172415"><a name="p12478654172415"></a><a name="p12478654172415"></a>阻止系统休眠的锁。</p>
</td>
</tr>
<tr id="row184789546249"><td class="cellrowborder" valign="top" width="30.78%" headers="mcps1.1.4.1.1 "><p id="p1971014525154"><a name="p1971014525154"></a><a name="p1971014525154"></a>PROXIMITY_SCREEN_CONTROL</p>
</td>
<td class="cellrowborder" valign="top" width="11.52%" headers="mcps1.1.4.1.2 "><p id="p570945210150"><a name="p570945210150"></a><a name="p570945210150"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="57.699999999999996%" headers="mcps1.1.4.1.3 "><p id="p1470645211154"><a name="p1470645211154"></a><a name="p1470645211154"></a>通过接近或者远离状态来控制亮灭屏的锁。</p>
</td>
</tr>
</tbody>
</table>

## isRunningLockTypeSupported<a name="section192192415554"></a>

isRunningLockTypeSupported\(type: RunningLockType, callback: AsyncCallback<boolean\>\): void

查询系统是否支持该类型的锁。

-   参数：

    <a name="table69661135912"></a>
    <table><thead align="left"><tr id="row149668318915"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p7966738914"><a name="p7966738914"></a><a name="p7966738914"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="27.74%" id="mcps1.1.5.1.2"><p id="p296713699"><a name="p296713699"></a><a name="p296713699"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="11.200000000000001%" id="mcps1.1.5.1.3"><p id="p196718315911"><a name="p196718315911"></a><a name="p196718315911"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="46.239999999999995%" id="mcps1.1.5.1.4"><p id="p9967231197"><a name="p9967231197"></a><a name="p9967231197"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row99671533914"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p134721811816"><a name="p134721811816"></a><a name="p134721811816"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.74%" headers="mcps1.1.5.1.2 "><p id="p11967433914"><a name="p11967433914"></a><a name="p11967433914"></a>RunningLockType</p>
    </td>
    <td class="cellrowborder" valign="top" width="11.200000000000001%" headers="mcps1.1.5.1.3 "><p id="p19671336916"><a name="p19671336916"></a><a name="p19671336916"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.239999999999995%" headers="mcps1.1.5.1.4 "><p id="p69671631796"><a name="p69671631796"></a><a name="p69671631796"></a>需要查询的锁的类型。</p>
    </td>
    </tr>
    <tr id="row10192174731012"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p61933477103"><a name="p61933477103"></a><a name="p61933477103"></a>callback</p>
    </td>
    <td class="cellrowborder" valign="top" width="27.74%" headers="mcps1.1.5.1.2 "><p id="p1193104791012"><a name="p1193104791012"></a><a name="p1193104791012"></a>AsyncCallback&lt;boolean&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="11.200000000000001%" headers="mcps1.1.5.1.3 "><p id="p1919313476105"><a name="p1919313476105"></a><a name="p1919313476105"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="46.239999999999995%" headers="mcps1.1.5.1.4 "><p id="p81931947161019"><a name="p81931947161019"></a><a name="p81931947161019"></a>指定的callback回调方法，用于获取返回值。</p>
    <p id="p1189279101115"><a name="p1189279101115"></a><a name="p1189279101115"></a>callback返回值：支持返回true，不支持返回false。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.isRunningLockTypeSupported(runningLock.RunningLockType.BACKGROUND, (error, supported) => {
        if (typeof error === "undefined") {
            console.info('BACKGROUND support status is ' + supported);
        } else {
            console.log('error: ' + error);
        }
    })
    ```


## isRunningLockTypeSupported<a name="section517513334611"></a>

isRunningLockTypeSupported\(type: RunningLockType\): Promise<boolean\>

查询系统是否支持该类型的锁。

-   参数：

    <a name="table12266112710718"></a>
    <table><thead align="left"><tr id="row626618271679"><th class="cellrowborder" valign="top" width="15.1%" id="mcps1.1.5.1.1"><p id="p626612710712"><a name="p626612710712"></a><a name="p626612710712"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="21.55%" id="mcps1.1.5.1.2"><p id="p826613271875"><a name="p826613271875"></a><a name="p826613271875"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="10.100000000000001%" id="mcps1.1.5.1.3"><p id="p142678273718"><a name="p142678273718"></a><a name="p142678273718"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="53.25%" id="mcps1.1.5.1.4"><p id="p1926718271072"><a name="p1926718271072"></a><a name="p1926718271072"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row162676272717"><td class="cellrowborder" valign="top" width="15.1%" headers="mcps1.1.5.1.1 "><p id="p1826716272716"><a name="p1826716272716"></a><a name="p1826716272716"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.55%" headers="mcps1.1.5.1.2 "><p id="p42673277712"><a name="p42673277712"></a><a name="p42673277712"></a>RunningLockType</p>
    </td>
    <td class="cellrowborder" valign="top" width="10.100000000000001%" headers="mcps1.1.5.1.3 "><p id="p426792717710"><a name="p426792717710"></a><a name="p426792717710"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.25%" headers="mcps1.1.5.1.4 "><p id="p1426717270710"><a name="p1426717270710"></a><a name="p1426717270710"></a>需要查询的锁的类型。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值：

    <a name="table82682027272"></a>
    <table><thead align="left"><tr id="row92681627972"><th class="cellrowborder" valign="top" width="25.569999999999997%" id="mcps1.1.3.1.1"><p id="p19268192715713"><a name="p19268192715713"></a><a name="p19268192715713"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="74.42999999999999%" id="mcps1.1.3.1.2"><p id="p22684273719"><a name="p22684273719"></a><a name="p22684273719"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1926882720712"><td class="cellrowborder" valign="top" width="25.569999999999997%" headers="mcps1.1.3.1.1 "><p id="p172682272071"><a name="p172682272071"></a><a name="p172682272071"></a>Promise&lt;boolean&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="74.42999999999999%" headers="mcps1.1.3.1.2 "><p id="p102681127973"><a name="p102681127973"></a><a name="p102681127973"></a>Promise实例，用于异步获取返回值，支持返回true，不支持返回false。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.isRunningLockTypeSupported(runningLock.RunningLockType.PROXIMITY_SCREEN_CONTROL)
    .then(supported => {
        console.info('PROXIMITY_SCREEN_CONTROL support status is ' + supported);
    })
    .catch(error => {
        console.log('error: ' + error);
    });
    ```


## createRunningLock<a name="section787751152220"></a>

createRunningLock\(name: string, type: RunningLockType, callback: AsyncCallback<RunningLock\>\): void

创建RunningLock锁。

-   参数：

    <a name="table9878312223"></a>
    <table><thead align="left"><tr id="row6878618227"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p1487811115229"><a name="p1487811115229"></a><a name="p1487811115229"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="36.88%" id="mcps1.1.5.1.2"><p id="p1987813113226"><a name="p1987813113226"></a><a name="p1987813113226"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="7.8100000000000005%" id="mcps1.1.5.1.3"><p id="p10878101102213"><a name="p10878101102213"></a><a name="p10878101102213"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="40.489999999999995%" id="mcps1.1.5.1.4"><p id="p68781112224"><a name="p68781112224"></a><a name="p68781112224"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row205362045162115"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p5536134542111"><a name="p5536134542111"></a><a name="p5536134542111"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="36.88%" headers="mcps1.1.5.1.2 "><p id="p5536114512117"><a name="p5536114512117"></a><a name="p5536114512117"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.8100000000000005%" headers="mcps1.1.5.1.3 "><p id="p1253617450215"><a name="p1253617450215"></a><a name="p1253617450215"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.489999999999995%" headers="mcps1.1.5.1.4 "><p id="p155361545102116"><a name="p155361545102116"></a><a name="p155361545102116"></a>锁的名字。</p>
    </td>
    </tr>
    <tr id="row19878113221"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p1087811152212"><a name="p1087811152212"></a><a name="p1087811152212"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="36.88%" headers="mcps1.1.5.1.2 "><p id="p14878615224"><a name="p14878615224"></a><a name="p14878615224"></a>RunningLockType</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.8100000000000005%" headers="mcps1.1.5.1.3 "><p id="p198788152211"><a name="p198788152211"></a><a name="p198788152211"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.489999999999995%" headers="mcps1.1.5.1.4 "><p id="p1287815113222"><a name="p1287815113222"></a><a name="p1287815113222"></a>要创建的锁的类型。</p>
    </td>
    </tr>
    <tr id="row84458101013"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p104459119108"><a name="p104459119108"></a><a name="p104459119108"></a>callback</p>
    </td>
    <td class="cellrowborder" valign="top" width="36.88%" headers="mcps1.1.5.1.2 "><p id="p144619141011"><a name="p144619141011"></a><a name="p144619141011"></a>AsyncCallback&lt;<a href="#section189341937163212">RunningLock</a>&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="7.8100000000000005%" headers="mcps1.1.5.1.3 "><p id="p844617111014"><a name="p844617111014"></a><a name="p844617111014"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="40.489999999999995%" headers="mcps1.1.5.1.4 "><p id="p14467151017"><a name="p14467151017"></a><a name="p14467151017"></a>指定的callback回调方法，用于获取返回的RunningLock锁对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.createRunningLock("running_lock_test", runningLock.RunningLockType.BACKGROUND)
    .then(runninglock => {
        var used = runninglock.isUsed();
        console.info('runninglock is used: ' + used);
        runninglock.lock(500);
        used = runninglock.isUsed();
        console.info('after lock runninglock is used ' + used);
    })
    .catch(error => {
        console.log('create runningLock test error: ' + error);
    })
    ```


## createRunningLock<a name="section16799155115717"></a>

createRunningLock\(name: string, type: RunningLockType\): Promise<RunningLock\>

创建Runninglock锁。

-   参数：

    <a name="table254113503814"></a>
    <table><thead align="left"><tr id="row85411350182"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p15415503818"><a name="p15415503818"></a><a name="p15415503818"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="33.57%" id="mcps1.1.5.1.2"><p id="p4541105010811"><a name="p4541105010811"></a><a name="p4541105010811"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="12.1%" id="mcps1.1.5.1.3"><p id="p1554115507812"><a name="p1554115507812"></a><a name="p1554115507812"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="39.51%" id="mcps1.1.5.1.4"><p id="p5541650982"><a name="p5541650982"></a><a name="p5541650982"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row55417507819"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p1754114500810"><a name="p1754114500810"></a><a name="p1754114500810"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.57%" headers="mcps1.1.5.1.2 "><p id="p65412501586"><a name="p65412501586"></a><a name="p65412501586"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="12.1%" headers="mcps1.1.5.1.3 "><p id="p1354195015810"><a name="p1354195015810"></a><a name="p1354195015810"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.51%" headers="mcps1.1.5.1.4 "><p id="p654111501384"><a name="p654111501384"></a><a name="p654111501384"></a>锁的名字。</p>
    </td>
    </tr>
    <tr id="row454111501682"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p1054275016813"><a name="p1054275016813"></a><a name="p1054275016813"></a>type</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.57%" headers="mcps1.1.5.1.2 "><p id="p55426505812"><a name="p55426505812"></a><a name="p55426505812"></a>RunningLockType</p>
    </td>
    <td class="cellrowborder" valign="top" width="12.1%" headers="mcps1.1.5.1.3 "><p id="p1254210501587"><a name="p1254210501587"></a><a name="p1254210501587"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.51%" headers="mcps1.1.5.1.4 "><p id="p1254245010819"><a name="p1254245010819"></a><a name="p1254245010819"></a>要创建的锁的类型。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   返回值：

    <a name="table17542250488"></a>
    <table><thead align="left"><tr id="row35421550384"><th class="cellrowborder" valign="top" width="32.57%" id="mcps1.1.3.1.1"><p id="p35421501189"><a name="p35421501189"></a><a name="p35421501189"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="67.43%" id="mcps1.1.3.1.2"><p id="p1254213507819"><a name="p1254213507819"></a><a name="p1254213507819"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row165431250282"><td class="cellrowborder" valign="top" width="32.57%" headers="mcps1.1.3.1.1 "><p id="p115430501589"><a name="p115430501589"></a><a name="p115430501589"></a>Promise&lt;<a href="#section189341937163212">RunningLock</a>&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="67.43%" headers="mcps1.1.3.1.2 "><p id="p165439501082"><a name="p165439501082"></a><a name="p165439501082"></a>Promise实例，用于异步获取返回的RunningLock锁对象。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.createRunningLock("running_lock_test", runningLock.RunningLockType.BACKGROUND)
    .then(runninglock => {
        console.info('create runningLock success');
    })
    .catch(error => {
        console.log('create runningLock test error: ' + error);
    })
    ```


## RunningLock<a name="section189341937163212"></a>

阻止系统休眠的锁。

### lock<a name="section86521450132716"></a>

lock\(timeout: number\): void

锁定和持有RunningLock

-   参数：

    <a name="table206539501273"></a>
    <table><thead align="left"><tr id="row3653205002714"><th class="cellrowborder" valign="top" width="14.82%" id="mcps1.1.5.1.1"><p id="p165311506273"><a name="p165311506273"></a><a name="p165311506273"></a>参数名</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.729999999999999%" id="mcps1.1.5.1.2"><p id="p1065365082714"><a name="p1065365082714"></a><a name="p1065365082714"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="9.16%" id="mcps1.1.5.1.3"><p id="p4653175062711"><a name="p4653175062711"></a><a name="p4653175062711"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="61.29%" id="mcps1.1.5.1.4"><p id="p665425019272"><a name="p665425019272"></a><a name="p665425019272"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row7654150172712"><td class="cellrowborder" valign="top" width="14.82%" headers="mcps1.1.5.1.1 "><p id="p0444142272919"><a name="p0444142272919"></a><a name="p0444142272919"></a>timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.729999999999999%" headers="mcps1.1.5.1.2 "><p id="p26542503275"><a name="p26542503275"></a><a name="p26542503275"></a>number</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.16%" headers="mcps1.1.5.1.3 "><p id="p17654105062720"><a name="p17654105062720"></a><a name="p17654105062720"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="61.29%" headers="mcps1.1.5.1.4 "><p id="p965405018273"><a name="p965405018273"></a><a name="p965405018273"></a>锁定和持有RunningLock的时长。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.createRunningLock("running_lock_test", runningLock.RunningLockType.BACKGROUND)
    .then(runningLock => {
        runningLock.lock(100)
        console.info('create runningLock success')
    })
    .catch(error => {
        console.log('Lock runningLock test error: ' + error)
    });
    ```


### unlock<a name="section19100160122813"></a>

unlock\(\): void

释放Runninglock锁。

-   示例：

    ```
    runningLock.createRunningLock("running_lock_test", runningLock.RunningLockType.BACKGROUND)
    .then(runningLock => {
        runningLock.unlock()
        console.info('unLock runningLock success')
    })
    .catch(error => {
        console.log('unLock runningLock test error: ' + error)
    });
    ```


### isUsed<a name="section1410593619146"></a>

isUsed\(\): boolean

查询当前Runninglock是持有状态，还是释放状态。

-   返回值：

    <a name="table115061181517"></a>
    <table><thead align="left"><tr id="row1150161121510"><th class="cellrowborder" valign="top" width="17.01%" id="mcps1.1.3.1.1"><p id="p1015015113159"><a name="p1015015113159"></a><a name="p1015015113159"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="82.99%" id="mcps1.1.3.1.2"><p id="p2150211201512"><a name="p2150211201512"></a><a name="p2150211201512"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17150811131514"><td class="cellrowborder" valign="top" width="17.01%" headers="mcps1.1.3.1.1 "><p id="p1150161110157"><a name="p1150161110157"></a><a name="p1150161110157"></a>boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="82.99%" headers="mcps1.1.3.1.2 "><p id="p51501611141518"><a name="p51501611141518"></a><a name="p51501611141518"></a>当前RunningLock是持有状态返回true，释放状态返回false。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例：

    ```
    runningLock.createRunningLock("running_lock_test", runningLock.RunningLockType.BACKGROUND)
    .then(runningLock => {
        var used = runningLock.isUsed()
        console.info('runningLock used status: ' + used)
    })
    .catch(error => {
        console.log('runningLock isUsed test error: ' + error)
    });
    ```


