# 基本概念<a name="ZH-CN_TOPIC_0000001078716892"></a>

在程序运行过程中，出现需要由CPU立即处理的事务时，CPU暂时中止当前程序的执行转而处理这个事务，这个过程叫做中断。当硬件产生中断时，通过中断号查找到其对应的中断处理程序，执行中断处理程序完成中断处理。

通过中断机制，在外设不需要CPU介入时，CPU可以执行其它任务；当外设需要CPU时，CPU会中断当前任务来响应中断请求。这样可以使CPU避免把大量时间耗费在等待、查询外设状态的操作上，有效提高系统实时性及执行效率。

下面介绍下中断的相关概念：

-   中断号

    中断请求信号特定的标志，计算机能够根据中断号判断是哪个设备提出的中断请求。

-   中断请求

    “紧急事件”向CPU提出申请（发一个电脉冲信号），请求中断，需要CPU暂停当前执行的任务处理该“紧急事件”，这一过程称为中断请求。

-   中断优先级

    为使系统能够及时响应并处理所有中断，系统根据中断事件的重要性和紧迫程度，将中断源分为若干个级别，称作中断优先级。

-   中断处理程序

    当外设发出中断请求后，CPU暂停当前的任务，转而响应中断请求，即执行中断处理程序。产生中断的每个设备都有相应的中断处理程序。

-   中断触发

    中断源向中断控制器发送中断信号，中断控制器对中断进行仲裁，确定优先级，将中断信号发送给CPU。中断源产生中断信号的时候，会将中断触发器置“1”，表明该中断源产生了中断，要求CPU去响应该中断。

-   中断向量

    中断服务程序的入口地址。

-   中断向量表

    存储中断向量的存储区，中断向量与中断号对应，中断向量在中断向量表中按照中断号顺序存储。


