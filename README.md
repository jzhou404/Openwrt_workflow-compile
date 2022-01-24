Openwrt Github Workflow 云编译

上游使用snowwolf的代码： https://github.com/coolsnowwolf/lede

<设备名称>.config 文件是配置内容

在Action里， This workflow has a workflow_dispatch event trigger. 点击右侧的 Run workflow 即可开始编译

编译成功后，在Actions里下载固件OpenWrt_firmware_<设备名>_<时间>即可。

编译时间大约2小时左右
