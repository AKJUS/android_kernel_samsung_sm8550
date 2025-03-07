[![GitHub release](https://img.shields.io/github/release/qlenlen/android_kernel_samsung_sm8550)](https://GitHub.com/qlenlen/android_kernel_samsung_sm8550/releases/) 
[![Github all releases](https://img.shields.io/github/downloads/qlenlen/android_kernel_samsung_sm8550/total)](https://GitHub.com/qlenlen/android_kernel_samsung_sm8550/releases/)
### :zap: Features
- 基于三星官方源码补全专属驱动
- 定期合并AOSP上游改动与其他优化
- 集成Re:Kernel以提供更好的墓碑体验
- 更快速的lz4与鸿蒙lz4kd提供zram支持
- 集成SUSFS提供更强的反检测能力

### 🔖 Important Notice
- 使用TWRP或者 [kernel flasher](https://github.com/qlenlen/KernelFlasher/releases) 刷入
- GKI模式开机即可集成KSU激活root权限
- 若使用LKM模式则需自行修补init_boot
- 适配KernelSU (24.12.24特别版)
- 适配Apatch (自24.12.07的发行版开始)

### ⭐ OneDesign
- 外版本地化支持（激活国行专属的qq微信录音、来电归属、状态栏实时网速、移除相机快门音、定位组件激活等）
- 国行功能扩展（启用港版独占的Onedrive系统相册同步 仅供Qyz使用、应用商店换源、天气换源）
- 功能扩展（电池旁路供电、去除截图声音、去除麦克风右上角绿点、240hz触控采样、新样式状态栏日期、状态栏图标大小调整、相册功能扩展、分身支持全部应用、5G切换tile、快捷关机菜单、解除截图安全限制、三星核心破解扩展、侧屏幕one支付面板等）
- 便捷功能（SELinux状态管理、解除刷新率限制、快捷开启开发者与ADB、GC回收等）
- 实用工具（去除AVB校验、分区备份、采样率测试、App管理等）

### 📰 Kernel Source Guideline
1. Download stock source code from [Samsung Opensource](https://opensource.samsung.com/uploadSearch?searchValue=S918B)
2. Clone AOSP from [repo](https://github.com/aosp-mirror/kernel_common/tree/android13-5.15-lts)
3. Merge anything you like into the stock one
4. Compile and you get it

### Credit
- Source from AOSP
- Drivers from Samsung
- Refer to some commits from `samsung-sm8550`
