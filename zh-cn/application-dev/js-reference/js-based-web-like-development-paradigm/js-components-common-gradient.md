# 渐变样式<a name="ZH-CN_TOPIC_0000001127284866"></a>

组件普遍支持的在style或css中设置的 可以平稳过渡两个或多个指定的颜色。

开发框架支持线性渐变 \(linear-gradient\)和重复线性渐变 \(repeating-linear-gradient\)两种渐变效果。

## 线性渐变/重复线性渐变<a name="s9fb0b2412d2843e4b06e05acc39dc394"></a>

使用渐变样式，需要定义过渡方向和过渡颜色。

1.  过渡方向：通过direction或者angle指定：

    -   direction：进行方向渐变。
    -   angle：进行角度渐变。

    ```
    background: linear-gradient(direction/angle, color, color, ...);
    background: repeating-linear-gradient(direction/angle, color, color, ...);
    ```

2.  过渡颜色：支持以下四种方式：\#ff0000、\#ffff0000、rgb\(255, 0, 0\)、rgba\(255, 0, 0, 1\)。需要指定至少两种颜色。

-   参数

    <a name="tbec24098117142bc8e59e180f6a2cbed"></a>
    <table><thead align="left"><tr id="r74a4b97fb46b429ab94909799d5aa057"><th class="cellrowborder" valign="top" width="13.13131313131313%" id="mcps1.1.6.1.1"><p id="a7a35c17dc8684775a8d4ce9fa2498b53"><a name="a7a35c17dc8684775a8d4ce9fa2498b53"></a><a name="a7a35c17dc8684775a8d4ce9fa2498b53"></a>名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="29.292929292929294%" id="mcps1.1.6.1.2"><p id="ae1621e9d7be54b608b04d6e59e386fa8"><a name="ae1621e9d7be54b608b04d6e59e386fa8"></a><a name="ae1621e9d7be54b608b04d6e59e386fa8"></a>类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.14141414141414%" id="mcps1.1.6.1.3"><p id="a58edb9b081d74f8aaeecee41af5f8a11"><a name="a58edb9b081d74f8aaeecee41af5f8a11"></a><a name="a58edb9b081d74f8aaeecee41af5f8a11"></a>默认值</p>
    </th>
    <th class="cellrowborder" valign="top" width="9.09090909090909%" id="mcps1.1.6.1.4"><p id="a69d42c9602a0464eb484093c6cb89261"><a name="a69d42c9602a0464eb484093c6cb89261"></a><a name="a69d42c9602a0464eb484093c6cb89261"></a>必填</p>
    </th>
    <th class="cellrowborder" valign="top" width="34.34343434343434%" id="mcps1.1.6.1.5"><p id="a55bc093362f04d8dbcb4343d3e80f940"><a name="a55bc093362f04d8dbcb4343d3e80f940"></a><a name="a55bc093362f04d8dbcb4343d3e80f940"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="rdbe9ecbd3a3442b48d39860444d96cf8"><td class="cellrowborder" valign="top" width="13.13131313131313%" headers="mcps1.1.6.1.1 "><p id="a963cbdb8589b42b785dd1fa4892839bb"><a name="a963cbdb8589b42b785dd1fa4892839bb"></a><a name="a963cbdb8589b42b785dd1fa4892839bb"></a>direction</p>
    </td>
    <td class="cellrowborder" valign="top" width="29.292929292929294%" headers="mcps1.1.6.1.2 "><p id="ab54d4ccb681c46f7bcc4e5d702fc8b30"><a name="ab54d4ccb681c46f7bcc4e5d702fc8b30"></a><a name="ab54d4ccb681c46f7bcc4e5d702fc8b30"></a>to &lt;side-or-corner&gt;  &lt;side-or-corner&gt; = [left | right] || [top | bottom]</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.14141414141414%" headers="mcps1.1.6.1.3 "><p id="a52342ab36286439b89baabf1b7a0096f"><a name="a52342ab36286439b89baabf1b7a0096f"></a><a name="a52342ab36286439b89baabf1b7a0096f"></a>to bottom (由上到下渐变)</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.09090909090909%" headers="mcps1.1.6.1.4 "><p id="a92b9128925dc4acdbef5bfaf6af1b93d"><a name="a92b9128925dc4acdbef5bfaf6af1b93d"></a><a name="a92b9128925dc4acdbef5bfaf6af1b93d"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.34343434343434%" headers="mcps1.1.6.1.5 "><p id="a1351d071b6d54f7084bdc7e4f15c7e72"><a name="a1351d071b6d54f7084bdc7e4f15c7e72"></a><a name="a1351d071b6d54f7084bdc7e4f15c7e72"></a>指定过渡方向，如：to left (从右向左渐变)  ；或者</p>
    <p id="a8146911b819748f0890e86cdf0fecc20"><a name="a8146911b819748f0890e86cdf0fecc20"></a><a name="a8146911b819748f0890e86cdf0fecc20"></a>to bottom right (从左上角到右下角)。</p>
    </td>
    </tr>
    <tr id="r6cdda990326c445283ef0188ad38a764"><td class="cellrowborder" valign="top" width="13.13131313131313%" headers="mcps1.1.6.1.1 "><p id="ada09dad6eade41edaa02a6a85e32b884"><a name="ada09dad6eade41edaa02a6a85e32b884"></a><a name="ada09dad6eade41edaa02a6a85e32b884"></a>angle</p>
    </td>
    <td class="cellrowborder" valign="top" width="29.292929292929294%" headers="mcps1.1.6.1.2 "><p id="ad9728bbfb4304c148051212f59c32096"><a name="ad9728bbfb4304c148051212f59c32096"></a><a name="ad9728bbfb4304c148051212f59c32096"></a>&lt;deg&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.14141414141414%" headers="mcps1.1.6.1.3 "><p id="ac59bbfd4b50c44e8be93a9c8fb1039d0"><a name="ac59bbfd4b50c44e8be93a9c8fb1039d0"></a><a name="ac59bbfd4b50c44e8be93a9c8fb1039d0"></a>180deg</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.09090909090909%" headers="mcps1.1.6.1.4 "><p id="ae6853c652f2c414b8b2eee535d838115"><a name="ae6853c652f2c414b8b2eee535d838115"></a><a name="ae6853c652f2c414b8b2eee535d838115"></a>否</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.34343434343434%" headers="mcps1.1.6.1.5 "><p id="a88b591f082704070b5b802aa11442816"><a name="a88b591f082704070b5b802aa11442816"></a><a name="a88b591f082704070b5b802aa11442816"></a>指定过渡方向，以元素几何中心为坐标原点，水平方向为X轴，angle指定了渐变线与Y轴的夹角(顺时针方向)。</p>
    </td>
    </tr>
    <tr id="r5f48e6c55e0c44b7adb0bb77eb12ce04"><td class="cellrowborder" valign="top" width="13.13131313131313%" headers="mcps1.1.6.1.1 "><p id="a8aba9a5fa61b4a9ab6eaaa0b840cd463"><a name="a8aba9a5fa61b4a9ab6eaaa0b840cd463"></a><a name="a8aba9a5fa61b4a9ab6eaaa0b840cd463"></a>color</p>
    </td>
    <td class="cellrowborder" valign="top" width="29.292929292929294%" headers="mcps1.1.6.1.2 "><p id="a1402dc10b0c940b799d3330682496908"><a name="a1402dc10b0c940b799d3330682496908"></a><a name="a1402dc10b0c940b799d3330682496908"></a>&lt;color&gt; [&lt;length&gt;|&lt;percentage&gt;]</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.14141414141414%" headers="mcps1.1.6.1.3 "><p id="a630e796e57164b71aa934fc8bcc87455"><a name="a630e796e57164b71aa934fc8bcc87455"></a><a name="a630e796e57164b71aa934fc8bcc87455"></a>-</p>
    </td>
    <td class="cellrowborder" valign="top" width="9.09090909090909%" headers="mcps1.1.6.1.4 "><p id="a81076bc36e3c4674b5186aee26a0ae73"><a name="a81076bc36e3c4674b5186aee26a0ae73"></a><a name="a81076bc36e3c4674b5186aee26a0ae73"></a>是</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.34343434343434%" headers="mcps1.1.6.1.5 "><p id="a36325f0de58d4db6bf1c35678a0d8e70"><a name="a36325f0de58d4db6bf1c35678a0d8e70"></a><a name="a36325f0de58d4db6bf1c35678a0d8e70"></a>定义使用渐变样式区域内颜色的渐变效果。</p>
    </td>
    </tr>
    </tbody>
    </table>

-   示例

    ```
    #gradient {
      height: 300px;
      width: 600px;
    }
    ```

    **图 1**  默认渐变方向为从上向下渐变<a name="fd4af6346567d40febe33cb89b27cb797"></a>  
    ![](figures/默认渐变方向为从上向下渐变.png "默认渐变方向为从上向下渐变")

    ```
    /* 从顶部开始向底部由红色向绿色渐变 */
    background: linear-gradient(red, #00ff00);
    ```

    **图 2**  45度夹角渐变<a name="f2d14c573ff20422fa206c381b7e50a56"></a>  
    ![](figures/45度夹角渐变.png "45度夹角渐变")

    ```
    /* 45度夹角，从红色渐变到绿色 */
    background: linear-gradient(45deg, rgb(255,0,0),rgb(0, 255, 0));
    ```

    **图 3**  设置方向为to right为从左向右渐变<a name="fdd5bac2f37d14ab6b9dd68cdc40df08c"></a>  
    ![](figures/设置方向为to-right为从左向右渐变.png "设置方向为to-right为从左向右渐变")

    ```
    /* 从左向右渐变，在距离左边90px和距离左边360px (600*0.6) 之间270px宽度形成渐变 */
    background: linear-gradient(to right, rgb(255,0,0) 90px, rgb(0, 255, 0) 60%);
    ```

    **图 4**  从左向右渐变，重复渐变<a name="fb33af9507d004041ba9394434e73a7c9"></a>  
    ![](figures/从左向右渐变-重复渐变.png "从左向右渐变-重复渐变")

    ```
    /* 从左向右重复渐变，重复渐变区域30px（60-30）透明度0.5 */
    background: repeating-linear-gradient(to right, rgba(255, 255, 0, 1) 30px,rgba(0, 0, 255, .5) 60px);
    ```


