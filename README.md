# 项目说明

使用 GitHub Actions 编译 OnePlus6 Ace SukiSU Ultra 内核，基于一加官方内核源代码

当前内核版本号 `5.10.226` 最新内核版本号 `5.10.236`

## Note

Use at your own risk! 使用前请用 KernelFlasher 类似工具备份内核

## 支持特性  

### SukiSU Ultra

- [x] SukiSU Ultra 最新
- [x] SuSFS 1.5.11 开启全部特性支持
- [x] KPM 支持

### 杂项

- [x] 移除内核版本号 -dirty 后缀
- [x] 增加应用隐藏补丁
- [x] 增加 zram lz4kd 算法
- [x] 支持 GitHub Actions 编译选项

### 参考

- [OnePlusOSS/android_kernel_5.10_oneplus_mt6895](https://github.com/OnePlusOSS/android_kernel_5.10_oneplus_mt6895) 官方开源内核项目
- [OnePlusOSS/android_vendor_mediatek_kernel_modules_mt6895](https://github.com/OnePlusOSS/android_vendor_mediatek_kernel_modules_mt6895) 官方开源内核项目
- [SukiSU Ultra 项目地址](https://github.com/SukiSU-Ultra/SukiSU-Ultra) SukiSU Ultra 主仓库
- [SukiSU Ultra 相关修补文件](https://github.com/SukiSU-Ultra/SukiSU_patch) 用于参考进行 SukiSU Ultra & SuSFS & KPM 内核修补及其他杂项修补
- [SukiSU Ultra 一加 SukiSU Ultra 内核编译工作流](https://github.com/ShirkNeko/Action_OnePlus_MKSU_SUSFS) 用于参考内核修补整体流程及内核配置项
