# 常见问题<a name="ZH-CN_TOPIC_0000001128470858"></a>

-   [安装hb过程中，出现乱码、段错误](#section411894616119)
-   [安装hb过程中，提示"cannot import 'sysconfig' from 'distutils'"](#section629417571626)
-   [安装hb过程中，提示"module 'platform' has no attribute 'linux\_distribution'"](#section10871523332)
-   [安装hb过程中，提示"Could not find a version that satisfies the requirement ohos-build"](#section47351657163213)
-   [Linux编译服务器终端输入不识别的命令时提示“ImportError: No module named apt\_pkg”](#section159891252236)

## 安装hb过程中，出现乱码、段错误<a name="section411894616119"></a>

-   **现象描述**

    执行“python3 -m pip install --user ohos-build”出现乱码、段错误（segmentation fault）。


-   **可能原因**

    pip版本过低。

-   **解决办法**

    执行如下命令升级pip。

    ```
    python3 -m pip install -U pip
    ```


## 安装hb过程中，提示"cannot import 'sysconfig' from 'distutils'"<a name="section629417571626"></a>

-   **现象描述**

    执行“python3 -m pip install --user ohos-build”提示"cannot import 'sysconfig' from 'distutils'"。


-   **可能原因**

    缺少distutils模块。

-   **解决办法**

    执行如下命令安装。

    ```
    sudo apt-get install python3.8-distutils
    ```


## 安装hb过程中，提示"module 'platform' has no attribute 'linux\_distribution'"<a name="section10871523332"></a>

-   **现象描述**

    执行“python3 -m pip install --user ohos-build”提示"module 'platform' has no attribute 'linux\_distribution'"。


-   **可能原因**

    python3 pip安装兼容性问题。

-   **解决办法**

    执行如下命令重新安装pip。

    ```
    sudo apt remove python3-pip
    curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
    python get-pip.py
    ```


## 安装hb过程中，提示"Could not find a version that satisfies the requirement ohos-build"<a name="section47351657163213"></a>

-   **现象描述**

    执行“python3 -m pip install --user ohos-build”提示"Could not find a version that satisfies the requirement ohos-build"


-   **可能原因**

    可能是网络环境较差导致的安装失败。

-   **解决办法**
    1.  请检查网络连接是否正常。如果网络有问题，请修复网络问题后重新安装。
    2.  若网络正常，请尝试指定临时pypi源的方式安装：

        ```
        python3 -m pip install -i https://pypi.tuna.tsinghua.edu.cn/simple ohos-build
        ```



## Linux编译服务器终端输入不识别的命令时提示“ImportError: No module named apt\_pkg”<a name="section159891252236"></a>

-   **现象描述**

    Linux编译服务器终端输入不识别的命令时，提示"ImportError: No module named apt\_pkg"


-   **可能原因**

    python3 apt安装兼容性问题。

-   **解决办法**

    执行如下命令重新安装python3-apt。

    ```
    sudo apt-get remove  python3-apt
    sudo apt-get install python3-apt
    ```


