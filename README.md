# Huananzhi (H81 Chipset) + Intel Xeon E5-26XX v3 + RX 580 4Gb

**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.8

## Complete hardware specs
- Intel Xeon E5-26XX v3 (HEDT Haswell)
- Huananzhi (H81 Chipset)
- AMD RX 580 4 Gb (Polaris)
- Áudio Codec: Realtek ALC662
- Ethernet: Realtek 8111H Gigabit

## What works
- macOS Big Sur, macOS Catalina, macOS Monterey and macOS Ventura
- Audio
- HDMI/DP
- All USB ports
- Ethernet
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Correct USB Mapping :(

## Kexts used:
- AppleALC.kext		(1.7.8)
- CpuTscSync.kext	(1.0.9)
- Lilu.kext		(1.6.3)
- RealtekRTL8111.kext	(2.4.2)
- RestrictEvents.kext	(1.0.9)
- SMCProcessor.kext	(1.3.0)
- SMCSuperIO.kext	(1.3.0)
- USBInjectAll.kext	(0.7.6)
- VirtualSMC.kext	(1.3.0)
- WhateverGreen.kext	(1.6.3)
- XHCI-unsupported.kext	(0.9.2)

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)
- [Discord - Universo Hackintosh - Gabriel Luchina](https://discord.universohackintosh.com.br)
