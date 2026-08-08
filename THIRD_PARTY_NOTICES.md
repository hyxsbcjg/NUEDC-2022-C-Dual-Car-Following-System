# 第三方软件声明

根目录 MIT License 只适用于可确认的项目原创部分，不覆盖下列第三方组件：

- Texas Instruments：`source/ti/` 的设备头、DriverLib 和 `driverlib.a`，以及两车启动文件和生成配置。保留文件头中的版权、再分发条件和免责声明。
- Arm：`source/third_party/CMSIS/` 的 CMSIS Core 头文件，使用 [Apache-2.0](licenses/Apache-2.0.txt)。
- TDK InvenSense ICM45686 驱动。
- 逐飞科技：2 车的 `zf_common`、`zf_drive`、`zf_device` 驱动源码文件头标明 [GPL-3.0 或更高版本](licenses/GPL-3.0.txt)。Keil 还链接原始 `zf_device_config.lib`；仓库中没有单独说明该二进制授权的文件。
- LCKFB、OLED、灰度传感器及其他保留上游标识的示例代码。

源码文件中的版权声明和许可条款继续有效。再分发或商用前，应逐文件核对上游许可证、NOTICE、厂商条款和原创权属；来源不明的历史片段不会因本仓库发布而自动获得额外授权。
