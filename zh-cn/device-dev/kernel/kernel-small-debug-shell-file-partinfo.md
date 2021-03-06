# partinfo<a name="ZH-CN_TOPIC_0000001179845931"></a>

-   [命令功能](#section1777503617199)
-   [命令格式](#section185501447132114)
-   [参数说明](#section1304151212252)
-   [使用指南](#section4566131982520)
-   [使用实例](#section4351134942514)
-   [输出说明](#section66689331412)

## 命令功能<a name="section1777503617199"></a>

partinfo命令用于查看系统识别的硬盘，SD卡多分区信息。

## 命令格式<a name="section185501447132114"></a>

partinfo <_dev\_inodename_\>

## 参数说明<a name="section1304151212252"></a>

**表 1**  参数说明

<a name="table1390mcpsimp"></a>
<table><thead align="left"><tr id="row1396mcpsimp"><th class="cellrowborder" valign="top" width="22%" id="mcps1.2.4.1.1"><p id="p1398mcpsimp"><a name="p1398mcpsimp"></a><a name="p1398mcpsimp"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="51%" id="mcps1.2.4.1.2"><p id="p1400mcpsimp"><a name="p1400mcpsimp"></a><a name="p1400mcpsimp"></a>参数说明</p>
</th>
<th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.3"><p id="p1402mcpsimp"><a name="p1402mcpsimp"></a><a name="p1402mcpsimp"></a>取值范围</p>
</th>
</tr>
</thead>
<tbody><tr id="row1403mcpsimp"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.4.1.1 "><p id="p1405mcpsimp"><a name="p1405mcpsimp"></a><a name="p1405mcpsimp"></a>dev_inodename</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.2.4.1.2 "><p id="p1407mcpsimp"><a name="p1407mcpsimp"></a><a name="p1407mcpsimp"></a>要查看的分区名字。</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.3 "><p id="p1409mcpsimp"><a name="p1409mcpsimp"></a><a name="p1409mcpsimp"></a>合法的分区名。</p>
</td>
</tr>
</tbody>
</table>

## 使用指南<a name="section4566131982520"></a>

无。

## 使用实例<a name="section4351134942514"></a>

举例：partinfo /dev/mmcblk0p0

## 输出说明<a name="section66689331412"></a>

**示例** 查看系统分区信息

```shell
OHOS # partinfo /dev/mmcblk0p0

part info :
disk id          : 0
part_id in system: 1
part no in disk  : 0
part no in mbr   : 0
part filesystem  : 00
part sec start   : 20480
part sec count   : 102400
```

