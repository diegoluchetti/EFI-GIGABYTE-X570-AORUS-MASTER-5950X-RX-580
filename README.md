# Hackintosh: Gigabyte X570 Aorus Master + 5950X + RX 580 8GB

![AboutThisMac](https://user-images.githubusercontent.com/23700365/135357946-539d1748-5f4a-4e8e-befb-b2119a552ab3.png)

**Latest working macOS**: 12.0
<br>
**Current OpenCore**: 0.7.4

## Complete hardware specs
- AMD Ryzen 5950X
- Gigabyte X570 Aorus Master
- WC Corsair H115i Platinum
- AsRock RX 580 8 GB
- Defaul Wireless - AX200 (without kexts)
- 32GB RAM Corsair Dominator - 3600 MHz DDR4
- SSD NVME Gen4 - XGX Gammix S50 1 Tb

## What works
- macOS Big Sur, macOS Catalina and macOS Monterey
- Audio
- HDMI/DP
- All USB ports
- 1x 2.5Gbit Ethernet (RTL8125E)
- 1x Gbit Ethernet (Intel 82576)
- Everything iCloud related (Drive, iMessage, Facetime, etc)
- Temperature monitoring for everything
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used:
- SmallTreeIntel82576.kext
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- NVMeFix.kext
- RestrictEvents.kext
- SMCAMDProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- https://browser.geekbench.com/v5/cpu/10291264
- https://browser.geekbench.com/v5/compute/3491713
- https://browser.geekbench.com/v5/compute/3491714

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI AMD - Ryzen and Threadripper (1XXX, 2XXX, 3XXX, 4XXX, 5XXX)](https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER)