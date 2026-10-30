<div align="center">
             <h1>ASUS TX Gaming 7Pro Ryzen CN OpenCore EFI</h1>
             <img src="https://img.shields.io/github/release/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI" />
             <img src="https://img.shields.io/github/downloads/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI/total?color=white&style=plastic" />
             <img src="https://img.shields.io/github/stars/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI" />
             <br>
             <br>
             <a href="README_en_US.md">🇬🇧English Readme</a>
</div>

# 硬件详情
- 主板:ASUS TX Gaming 7Pro Ryzen CN (BIOS V322)
- CPU:AMD Ryzen 9 9955HX 16-Core Processor
- 内存:三星 16GB DDR5 5600MHz
- 显卡:NVIDIA Geforce RTX 5060 Laptop
- 无线PCIE网卡:Intel AX210


# 工作情况
- [x] Apple服务(iCloud/iMessage/FaceTime)
- [x] GPU硬件加速(Metal 3)
- [x] CPU电源管理(AMDRyzenCPUPowerManagement)
- [x] USB端口
- [x] Wifi
- [x] 关闭显示器
- [x] 板载声卡
- [ ] 蓝牙
- [ ] 睡眠

---

- MacOS Tahoe(26)
<img width="1920" height="1080" alt="微信图片_20260504223506_33_1" src="https://github.com/user-attachments/assets/f4a6b5f6-4dbe-4929-b093-161c51f39a74" />

# OpenCore信息
- OpenCore:V1.0.7

- Kexts:
<img width="1309" height="689" alt="微信图片_20260504223656_42_1" src="https://github.com/user-attachments/assets/577901a9-64ae-40f7-8983-1e1349285a45" />

- SMBios:MacPro7,1
<img width="1309" height="689" alt="微信图片_20260504223855_51_1" src="https://github.com/user-attachments/assets/c6a9cdb6-e222-4ac1-a8b4-4cd574ea7934" />

# 使用教程
1.在安装系统前设置BIOS:
开启
- Above 4G Decoding
- ErP Ready

关闭
- Fast Boot 
- CSM 
- SVM 
- TPM 
- AMDFTPM

调整
- SATA Mode - AHCI
- Secure Boot - Other OS

2.设置 OC 启动项后直接启动烧录好的MacOS Recovery设备

3.格式化磁盘至APFS后开始安装

4.进入系统后使用 https://github.com/laobamac/OCLP-Mod/releases 的最新版本下载并安装 OS KDK 和 Root Patch

5.使用工具注入三码激活Apple服务

6.开始体验
