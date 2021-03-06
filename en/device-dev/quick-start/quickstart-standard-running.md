# Running an Image<a name="EN-US_TOPIC_0000001142160948"></a>

-   [Running an Image](#section153991115191314)
-   [Next](#section5600113114323)

## Running an Image<a name="section153991115191314"></a>

After the image burning is complete, perform the following steps to run the system:

>![](../public_sys-resources/icon-note.gif) **NOTE:** 
>This operation procedure is required only if this is the first time you burn an image for the standard system.

1.  In DevEco Device Tool, click  **Monitor**  to open the serial port tool.

    ![](figures/open-the-serial-port-tool.png)

2.  Restart the development board. Before the autoboot countdown ends, press any key to enter the system.

    ![](figures/press-any-key-to-enter-the-system.gif)

3.  Run the following commands to set system boot parameters:

    ```
    setenv bootargs 'mem=640M console=ttyAMA0,115200 mmz=anonymous,0,0xA8000000,384M clk_ignore_unused rootdelay=10 hardware=Hi3516DV300 init=/init root=/dev/ram0 rw blkdevparts=mmcblk0:1M(boot),15M(kernel),20M(updater),2M(misc),3307M(system),256M(vendor),-(userdata)';
    ```

    ```
    setenv bootcmd 'mmc read 0x0 0x82000000 0x800 0x4800; bootm 0x82000000'
    ```

    ![](figures/setenv-bootargs.png)

4.  Save the parameter settings.

    ```
    save
    ```

    ![](figures/save-the-parameter-settings.png)

5.  Restart the development board to start the system.

    ```
    reset
    ```

    ![](figures/start-the-system.png)


## Next<a name="section5600113114323"></a>

Congratulations! You have completed the quick start for the standard system. Get yourself familiar with OpenHarmony by a  [Development Example for Clock App](../guide/device-clock-guide.md).

