# chgrp<a name="ZH-CN_TOPIC_0000001134006260"></a>

-   [命令功能](#section01)
-   [命令格式](#section02)
-   [参数说明](#section03)
-   [使用指南](#section04)
-   [使用实例](#section05)
-   [输出说明](#section06)

## 命令功能<a name="section01"></a>

chgrp用于修改文件的群组。

## 命令格式<a name="section02"></a>

chgrp \[_group_\] \[_pathname_\]

## 参数说明<a name="section03"></a>

**表 1**  参数说明

<a name="table1049mcpsimp"></a>

<table><thead align="left"><tr id="row1055mcpsimp"><th class="cellrowborder" valign="top" width="21%" id="mcps1.2.4.1.1"><p id="p1057mcpsimp"><a name="p1057mcpsimp"></a><a name="p1057mcpsimp"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="52%" id="mcps1.2.4.1.2"><p id="p1059mcpsimp"><a name="p1059mcpsimp"></a><a name="p1059mcpsimp"></a>参数说明</p>
</th>
<th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.3"><p id="p1061mcpsimp"><a name="p1061mcpsimp"></a><a name="p1061mcpsimp"></a>取值范围</p>
</th>
</tr>
</thead>
<tbody><tr id="row1062mcpsimp"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p1064mcpsimp"><a name="p1064mcpsimp"></a><a name="p1064mcpsimp"></a>group</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.4.1.2 "><p id="p1066mcpsimp"><a name="p1066mcpsimp"></a><a name="p1066mcpsimp"></a>文件群组。</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.3 "><p id="p1068mcpsimp"><a name="p1068mcpsimp"></a><a name="p1068mcpsimp"></a>[0,0xFFFFFFFF]</p>
</td>
</tr>
<tr id="row172161126124218"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p12217026154215"><a name="p12217026154215"></a><a name="p12217026154215"></a>pathname</p>
</td>
<td class="cellrowborder" valign="top" width="52%" headers="mcps1.2.4.1.2 "><p id="p4218826194210"><a name="p4218826194210"></a><a name="p4218826194210"></a>文件路径。</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.3 "><p id="p182181026104214"><a name="p182181026104214"></a><a name="p182181026104214"></a>已存在的文件。</p>
</td>
</tr>
</tbody>
</table>

## 使用指南<a name="section04"></a>

- 在需要修改的文件名前加上文件群组值就可以修改该文件的所属组。
- fatfs文件系统不支持修改用户组id。

## 使用实例<a name="section05"></a>

举例：chgrp 100 testfile

## 输出说明<a name="section06"></a>

**示例**  修改 /dev目录下testfile 文件的群组为100

```shell
OHOS:/dev$ ll testfile
-rw-r--r-- 0 0 0 0 1970-01-01 00:00 testfile
OHOS:/dev$ chgrp 100 testfile                                           
OHOS:/dev$ ll testfile                                                   
-rw-r--r-- 0 0 100 0 1970-01-01 00:00 testfile
OHOS:/dev$
```
