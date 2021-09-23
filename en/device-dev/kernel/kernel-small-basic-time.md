# Time Management<a name="EN-US_TOPIC_0000001123753363"></a>

-   [Basic Concepts](#section12903185785119)
-   [Development Guidelines](#section430981720522)
    -   [Available APIs](#section1040142705214)
    -   [How to Develop](#section1381224710522)
    -   [Development Example](#section1344610245416)


## Basic Concepts<a name="section12903185785119"></a>

Time management provides all time-related services for applications based on the system clock. The system clock is generated by the interrupts triggered by the output pulse of a timer or counter. The system clock is generally defined as an integer or a long integer. The period of an output pulse is a "clock tick". The system clock is also called time scale or tick. The duration of a tick can be configured statically. People use second or millisecond as the time unit, while the operating system uses tick. When operations such as suspending a task or delaying a task are performed, the time management module converts time between ticks and seconds or milliseconds.

The mapping between ticks and seconds can be configured.

-   **Cycle**

    Cycle is the minimum time unit in the system. The cycle duration is determined by the system clock frequency, that is, the number of cycles per second.


-   **Tick**

    Tick is the basic time unit of the operating system and is determined by the number of ticks per second configured by the user.


The OpenHarmony time management module provides time conversion, statistics, and delay functions to meet users' time requirements.

## Development Guidelines<a name="section430981720522"></a>

The time management module provides APIs to implement conversion between the system running time, ticks, and seconds/milliseconds.

### Available APIs<a name="section1040142705214"></a>

The following table describes APIs available for the OpenHarmony LiteOS-A time management. For more details about the APIs, see the API reference.

**Table  1**  APIs of the time management module

<a name="table1316220185211"></a>
<table><thead align="left"><tr id="row191622182021"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p13162121815218"><a name="p13162121815218"></a><a name="p13162121815218"></a>Category</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p12162618623"><a name="p12162618623"></a><a name="p12162618623"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p16162118427"><a name="p16162118427"></a><a name="p16162118427"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row04981218910"><td class="cellrowborder" rowspan="2" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p6462616696"><a name="p6462616696"></a><a name="p6462616696"></a>Time conversion</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p164931214913"><a name="p164931214913"></a><a name="p164931214913"></a>LOS_MS2Tick</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p8504121996"><a name="p8504121996"></a><a name="p8504121996"></a>Converts milliseconds into ticks.</p>
</td>
</tr>
<tr id="row7162101814216"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p816311185217"><a name="p816311185217"></a><a name="p816311185217"></a>LOS_Tick2MS</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p161632181721"><a name="p161632181721"></a><a name="p161632181721"></a>Converts ticks into milliseconds.</p>
</td>
</tr>
<tr id="row1516317181227"><td class="cellrowborder" rowspan="2" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1077619231696"><a name="p1077619231696"></a><a name="p1077619231696"></a>Time statistics</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p181638181921"><a name="p181638181921"></a><a name="p181638181921"></a>LOS_TickCountGet</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p615864811116"><a name="p615864811116"></a><a name="p615864811116"></a>Obtains the current number of ticks.</p>
</td>
</tr>
<tr id="row101631818620"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p71633181125"><a name="p71633181125"></a><a name="p71633181125"></a>LOS_CyclePerTickGet</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p151631718124"><a name="p151631718124"></a><a name="p151631718124"></a>Obtains the number of cycles per tick.</p>
</td>
</tr>
</tbody>
</table>

### How to Develop<a name="section1381224710522"></a>

1.  Call APIs to convert time.
2.  Call APIs to perform time statistics.

>![](../public_sys-resources/icon-note.gif) **NOTE:** 
>-   The system tick count can be obtained only after the system clock is enabled.
>-   The time management module depends on  **OS\_SYS\_CLOCK**  and  **LOSCFG\_BASE\_CORE\_TICK\_PER\_SECOND**  in  **los\_config.h**.
>-   The number of system ticks is not counted when the interrupt feature is disabled. Therefore, the number of ticks cannot be used as the accurate time.

### Development Example<a name="section1344610245416"></a>

Prerequisites:

-   **LOSCFG\_BASE\_CORE\_TICK\_PER\_SECOND**, that is, the number of ticks per second in the system is configured.
-   **OS\_SYS\_CLOCK**, that is, system clock \(in Hz\), is configured.

**Sample Code**

Time conversion:

```
VOID Example_TransformTime(VOID)
{
    UINT32 uwMs;
    UINT32 uwTick;
    uwTick = LOS_MS2Tick(10000);// Convert 10000 ms into ticks.
    PRINTK("uwTick = %d \n",uwTick);
    uwMs= LOS_Tick2MS(100); // Convert 100 ticks into ms.
    PRINTK("uwMs = %d \n",uwMs);
}
```

Time statistics and delay:

```
VOID Example_GetTime(VOID)
{
    UINT32 uwcyclePerTick;
    UINT64 uwTickCount;

    uwcyclePerTick = LOS_CyclePerTickGet(); // Obtain the number of cycles per tick.
    if(0 != uwcyclePerTick)
    {
        PRINTK("LOS_CyclePerTickGet = %d \n", uwcyclePerTick);
    }

    uwTickCount = LOS_TickCountGet(); // Obtain the number of ticks.
    if(0 != uwTickCount)
    {
        PRINTK("LOS_TickCountGet = %d \n", (UINT32)uwTickCount);
    }
    LOS_TaskDelay(200);// Delay 200 ticks.
    uwTickCount = LOS_TickCountGet();
    if(0 != uwTickCount)
    {
        PRINTK("LOS_TickCountGet after delay = %d \n", (UINT32)uwTickCount);
    }
}
```

**Verification**

The result is as follows:

Time conversion:

```
uwTick = 10000 
uwMs = 100
```

Time statistics and delay:

```
LOS_CyclePerTickGet = 49500 
LOS_TickCountGet = 5042
LOS_TickCountGet after delay = 5242
```
