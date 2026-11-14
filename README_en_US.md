<div align="center">
            <h1>ASUS TX Gaming 7Pro Ryzen CN OpenCore EFI</h1>
            <img src="https://img.shields.io/github/downloads/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI/total?color=white&style=plastic" />
            <img src="https://img.shields.io/github/stars/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI" />
            <br>
            <br>
            <a href="README.md">简体中文 README</a>
</div>

# Hardware Details
- Motherboard: ASUS TX Gaming 7Pro Ryzen CN (BIOS V322)
- CPU: AMD Ryzen 9 9955HX 16-Core Processor
- RAM: Samsung 16GB DDR5 5600MHz
- GPU: NVIDIA GeForce RTX 5060 Laptop
- Wireless PCIe Card: Intel(R) Wi-Fi 6E AX210 160MHz

# Working Status
- [x] Apple Services (iCloud / iMessage / FaceTime)
- [x] GPU Hardware Acceleration (Metal 4)
- [x] CPU Power Management
- [x] USB Ports
- [x] Wi-Fi & Bluetooth
- [x] Display Sleep / Wake
- [x] Onboard Audio
- [X] Sleep & Suspend

# Compatibility Range
**macOS 15 Sequoia - macOS 26 Tahoe**

File List | Applicable Scope | Description
---- | ---- | ----
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Sequoia.zip | macOS 15 Sequoia | Use when using Recovery and before installing patch 1401
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Sequoia-1401.zip | macOS 15 Sequoia | Use when system and patch 1401 installation are complete
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Tahoe.zip | macOS 26 Tahoe | Use when using Recovery and before installing patch 1401
ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI-Tahoe-1401.zip | macOS 26 Tahoe | Use when system and patch 1401 installation are complete

# How to Use
- Head over to [GitHub Releases](https://github.com/VisualTechStudio/ASUS-TX-Gaming-7Pro-Ryzen-CN-OpenCore-EFI/releases) to download the EFI matching your target macOS version and installation status.
- Use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) or another configuration tool to generate your own SMBIOS (recommended: `MacBookPro16,2`).
- Move the configured EFI into your EFI system partition (ESP). The directory structure should look like `ESP_EFI\EFI\OC\*`.
- Reboot your laptop. When the POST screen appears (ASUS TX boot animation begins), press `F2` to enter UEFI BIOS, press `F7` to enter Advanced Mode, navigate to the **Boot** tab, go to **Secure Boot**, and change **OS Type** to **Other OS**.
- Boot into the macOS installer to install macOS.
- Enjoy your Hackintosh!

# Acknowledgments
Contributors / Projects |    |    |    |    |
---- | ---- | ---- | ---- | ---- |
[acidanthera](https://github.com/acidanthera/) | [OpenCore](https://github.com/acidanthera/OpenCorePkg) | [Lilu](https://github.com/acidanthera/Lilu) | [VirtualSMC](https://github.com/acidanthera/VirtualSMC) | [AppleALC](https://github.com/acidanthera/AppleALC)
[VisualTechStudio(KL_Xydwg01)](https://github.com/VisualTechStudio/) | [SSDT-BATT-ASUS](https://github.com/VisualTechStudio/SSDT-BATT-ASUS) | - | - | - |
[laobamac](https://github.com/laobamac/) | [itlwm](https://github.com/laobamac/itlwm) | [SimpleHDA](https://github.com/laobamac/SimpleHDA) | - | - |
[ic005k](https://github.com/ic005k/) | [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) | - | - | - |
... | ... | ... | ... | ... |
