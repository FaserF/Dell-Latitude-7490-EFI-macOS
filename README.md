# Dell Latitude 7490 Hackintosh EFI
# macOS 14 Sonoma with Intel Wireless via AirportItlwm

Dell 14" Latidude 7490 i5-8650U OpenCore configuration
Has BootChime enabled, debug modes turned off, non verbose

Thanks to all those that allowed me to find working configs (boy the trackpad was a fun one)

## Tested macOS version:
macOS 14.7.0 Using latest OpenCore as of Sept 16, 2024

## System configuration
- Intel Core i5-8650U
- 32GB DDR4-2400MHz RAM (2x16Gb)
- Intel UHD 620 Graphics
- Idk some generic NVMe 256Gb drive
- Intel Dual-Band Wireless-AC 8265

## Confirm working
1) Loudspeaker
2) 3.5mm headphone jack
3) Battery Management
4) Backlight Control (Fn+B & Fn+S)
5) Touchpad with Gestures
6) WiFi (2.4/5GHz)
7) Bluetooth
8) USB-C Display Output
9) Barrel Plug for Charging (Dell)
10) iGPU Acceleration
11) Native hotkey support with Fn keys

^_3.5mm headphone jack might not work properly after system wakes from sleep, reboot will resolve the issue._

## Not working
1) HDMI output

## Unknown (not tested)
1) Intel TurboBoost (Unable to monitor)
2) Ethernet
3) Handoff and Airdrop (Likely not working due to AppleItlwm Limitations)
4) USB-C Data Transfer
5) WWAN
6) SD Card Reader
7) ThunderBolt and Touchscreen (SKU did not include)8
8) SideCar over WiFi

## Credits
6) https://raw.githubusercontent.com/lohseng97/Dell-Latitude-7490-EFI-macOS-BigSur
1) Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI: https://github.com/Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI/tree/Catalina-OpenCore
2) niiknow/Hackintosh-Latitude-7390: https://github.com/niiknow/Hackintosh-Latitude-7390
3) dortania/OpenCore-Install-Guide: https://dortania.github.io/OpenCore-Install-Guide/
4) OpenIntelWireless/itlwm: https://github.com/OpenIntelWireless/itlwm/
5) xzhih/one-key-hidpi：https://github.com/xzhih/one-key-hidpi
6) acidanthera/OpenCorePkg: https://github.com/acidanthera/OpenCorePkg/releases/