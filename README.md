# AMD Ryzen Hackintosh

**MacOS version**:  11.2
**OpenCore version**: 0.6.6

**02/02/2021**

* Updated to OpenCore 0.6.6
* Updated Kexts:

* AppleALC
* Lilu
* VirtualSMC
* WhateverGreen

* Importante: With OC 0.6.6, Bootstrap.efi has been replaced with LauncherOption. More infos about this change here: (https://dortania.github.io/OpenCore-Post-Install/multiboot/bootstrap.html#prerequisites)

* If you are going to use this EFI, please change the SMBIOS data. 
* I have no responsibility for any problems that may occur with your setup.

## Specification

| Component        | Model                                  |
| ---------------- | -------------------------------------- |
| CPU              | AMD Ryzen 5 1600AF                     |
| MotherBoard      | MSI B450M Pro-VDH Max                  |
| OS Disk          | XRayDisk 120GB SSD                     |
| RAM              | 16GB 2x8GB Asgard Loki 3200MHz         |
| GPU              | Radeon RX 5500 XT                      |
| Network/BT card  | Intel WiFi 6 AX200                     |

[![big_sur_ryzentosh](https://i.postimg.cc/wTMSL5rS/big-sur-ryzentosh.png)](https://postimg.cc/svF6RWsc)

## Patches, Drivers & Kexts

* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla)
* [OpenRuntime](https://github.com/acidanthera/OpenCorePkg)
* [Lilu](https://github.com/acidanthera/Lilu)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
* [AppleALC](https://github.com/acidanthera/AppleALC)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [Intel WiFI/BT](https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth)


## What works?

* Almost everything...
* Hardware acceleration - CPU/GPU
* Audio from external DisplayPort
* Audio from front/back panel
* WIFI/BT ~Thanks to OpenIntelWireless
* AirPlay
* Handoff 
* Sleep/wake

## Currently known problems and solutions:

* <strike>Keyboard Hot Keys +/- volume over DisplayPort doesn't work</strike> [Monitor Control](https://github.com/MonitorControl/MonitorControl)
* DRM doesn't work
* Send files with Airdrop doesn't work either
* Mic from front/back panel

## Credits and links

* [sileshn](https://github.com/sileshn/Ryzentosh)
* [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/)
