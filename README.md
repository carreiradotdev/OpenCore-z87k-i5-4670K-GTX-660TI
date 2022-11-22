# ASUS Z87-k + i5 4670K + GTX 660 TI + ASUS BT400

**Latest working macOS**: 12.4
<br>
**Current OpenCore**: 0.8.2

## Complete hardware specs
- Intel i5 4670K @ Stock (All cores (P+E+HT) activated)
- ASUS - Z87-K SK1150 4XDDR3
- ASUS GTX 660 Ti DirectCU II
- 4x 8Gb DDR3 1333Mhz

## What works
- macOS Monterey
- Audio
- HDMI/DP (Kepler has artifacts after 10/15min)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep

## Kexts used:
- AppleALC.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 11th Intel Gen - Rocket Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-11THGEN-ROCKET-LAKE)
- tonymacx86.com - in special @etorix and @CaseySJ
