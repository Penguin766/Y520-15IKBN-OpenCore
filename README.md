# Y520-15IKBN-OpenCore
### **Ready-to-use OpenCore 0.8.5 EFI for Lenovo Legion Y520-15IKBN**

> ❓ If you don't know how to use this EFI, please refer to this [guide](https://dortania.github.io/OpenCore-Install-Guide/)<br>

> ⚠️ If you want to use this EFI with your Apple ID, please refer to this [guide](https://youtu.be/JtYAAjgniIc) (but generate serial for MacBookPro14,3 not MacPro6,1)

## ☑️ Tested versions
| Version | Works? | EFI |
| :---: | :---: | :---: |
| **macOS Monterey 12.6** | ✅ | [Download]() | 

## 🔘 Status
| Feature | Works? | Notes |
| :---: | :---: | :---: |
| **Built-in Wi-Fi & Bluetooth** | ✅ | Works also in macOS Recovery |
| **Ethernet** | ✅ | - |
| **Intel GPU (iGPU)** | ✅ | - |
| **Audio** | ✅ | - |
| **Microphone** | ✅ | - |
| **Webcam** | ✅ | - |
| **External display via HDMI** | 🔶<br>Partially | Sometimes when laptop wakes up from sleep,<br>external display stops working and you need to<br>disconnect and reconnect the cable |
| **Build-in keyboard** | ✅ | - |
| **Trackpad** | 🔶<br>Partially | Physical buttons doesn't work and you need to<br>enable "**Tap to click**" in System Preferences
| **USB 2, USB 3 & USB-C** | ✅ | - |
| **Sleep** | ✅ | - |
| **FileVault** | ✅ | - |
| **Battery percentage** | ✅ | - |
| **Nvidia GPU** | ❌ | - |
| **SD Card Reader** | ❌ | - |

## 🔧 BIOS Settings
| Setting | Enabled? |
| :---: | :---: |
| Secure Boot | ❌ |
| Fast Boot | ❌ |
| Intel Virtual Technology | ✅ |
| Intel Platform Trust Technology | ❌ |

## Acknowledgments
**[dortania](https://github.com/dortania/)** for [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)<br>
**[acidanthera](https://github.com/acidanthera)** for [OpenCore](https://github.com/acidanthera/OpenCorePkg) and most of the kexts and drivers<br>
**[USBToolBox](https://github.com/USBToolBox)** for [USBToolBox & UTBmap](https://github.com/USBToolBox/kext) kexts<br>
**[OpenIntelWireless](https://github.com/OpenIntelWireless)** for Intel [Wi-Fi](https://github.com/OpenIntelWireless/itlwm) & [Bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) kexts<br>
**[Mieze](https://github.com/Mieze)** for [Realtek RTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) kext<br>
**[1Revenger1](https://github.com/1Revenger1)** for [ECEnabler](https://github.com/1Revenger1/ECEnabler) kext<br>
**[VoodooSMBus](https://github.com/VoodooSMBus)** for [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI) kext<br>
**[jaromeyer](https://github.com/jaromeyer)** for inspiration how to write this ReadMe
