# 目录结构<a name="ZH-CN_TOPIC_0000001111581264"></a>

FA应用的ets模块\(entry/src/main\)的典型开发目录结构如下：

![](figures/zh-cn_image_0000001182200571.png)

**目录结构中文件分类如下：**

-   .ets结尾的ETS（Extended TypeScript）文件，这个文件用于描述UI布局、样式、事件交互和页面逻辑。

**各个文件夹和文件的作用：**

-   **app.ets**文件用于全局应用逻辑和应用生命周期管理。
-   **pages**目录用于存放所有组件页面。
-   **common**目录用于存放公共代码文件，比如：自定义组件和公共方法。

>![](../../public_sys-resources/icon-note.gif) **说明：** 
>-   页面支持导入TypeScript和JavaScript文件。

