<div align="center">
             <h1>ASUS TX Gaming 7Pro Ryzen CN OpenCore EFI</h1>
             <img src="https://img.shields.io/github/downloads/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI/total?color=white&style=plastic" />
             <img src="https://img.shields.io/github/stars/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI" />
             <br>
             <br>
             <a href="README_en_US.md">English Readme</a>
</div>

# 硬件详情
- 主板:ASUS TX Gaming 7Pro Ryzen CN (BIOS V322)
- CPU:AMD Ryzen 9 9955HX 16-Core Processor
- 内存:三星 16GB DDR5 5600MHz
- 显卡:NVIDIA Geforce RTX 5060 Laptop
- 无线PCIE网卡:Intel(R) Wi-Fi 6E AX210 160MHz


# 工作情况
- [x] Apple服务(iCloud/iMessage/FaceTime)
- [x] GPU硬件加速(Metal 4)
- [x] CPU电源管理
- [x] USB端口
- [x] Wifi及蓝牙
- [x] 关闭显示器
- [x] 板载声卡
- [X] 睡眠

# 适配范围
**macOS 15 Sequoia - macOS 26 Tahoe**


文件列表 | 适用范围 | 说明
---- | ---- | ----
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Sequoia.zip | Macos 15 Sequoia | 需要使用Recovery及未安装1401时使用
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Sequoia-1401.zip | Macos 15 Sequoia | 已完成系统及1401安装时使用
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Tahoe.zip | Macos 26 Tahoe | 需要使用Recovery及未安装1401时使用
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Tahoe-1401.zip | Macos 26 Tahoe | 已完成系统及1401安装时使用

# 如何使用
- 前往[Github Release](https://github.com/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI/releases)根据文件列表以及适用范围下载EFI
- 使用[OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)或其他工具，生成SMBIOS=MacBookPro16,2的三码
- 将修改后的EFI移入ESP_EFI\，目录应为ESP_EFI\EFI\OC\*
- 重新启动，等待自检完成（TX动画开始播放）时按下F2，进入UEFI BIOS，按下F7进入高级模式，进入"启动"选项卡，进入"安全启动"页面，将"安全启动类型"修改为"Other OS"
- 使用macOS安装器安装macOS
- 开始使用

# 致谢
贡献者/项目 |    |    |    |    |
---- | ---- | ---- | ---- | ---- |
[acidanthera](https://github.com/acidanthera/) | [OpenCore](https://github.com/acidanthera/OpenCorePkg) | [Lilu](https://github.com/acidanthera/Lilu) | [VirtualSMC](https://github.com/acidanthera/VirtualSMC) | [AppleALC](https://github.com/acidanthera/AppleALC)
[VisualTechStudio(KL_Xydwg01)](https://github.com/VisualTechStudio/) | [SSDT-BATT-ASUS](https://github.com/VisualTechStudio/SSDT-BATT-ASUS) | - | - | - |
[laobamac](https://github.com/laobamac/) | [itlwm](https://github.com/laobamac/itlwm) | [SimpleHDA](https://github.com/laobamac/SimpleHDA) | - | - |
[ic005k](https://github.com/ic005k/) | [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) | - | - | - |
... | ... | ... | ... | ... |
