# OpenCore EFI Setup for Asus TUF B550-Plus, Ryzen 5700X and Radeon RX 6600 XT

OpenCore's EFI folder foder AMD based Hackintosh.

<img src="imgs/about.png" alt="drawing" height="400"/>
<img src="imgs/neofetch.png" alt="drawing" height="400"/>

## System Specifications

| Name               | Model                            |
| ------------------ | -------------------------------- |
| **Motherboard**    | Asus TUF B550-Plus               |
| **CPU**            | AMD Ryzen 5700X                  |
| **GPU**            | Gigabyte Radeon RX 6600 XT 8GB   |
| **RAM**            | HyperX Fury 2x16 DDR4 3600 MHz   |
| **SSD**            | Lexar NM710 2TB                  |
| **Ethernet**       | Realtek Ethernet Controller      |
| **WiFi/Bluetooth** | Fenvi T919 (BCM94360)            |

### Software

- **OpenCore:** v0.9.5
- **macOS:** v13.6.4 Ventura

### Notes

- Resize Bar MUST BE enabled, otherwise you will get glitches screen on Mac recovery
- Sonoma installation is possible, only problem is Broadcom wifi. Except that, EFI must work on Sonoma for sure
- Don't forget to set your own CPU cores counter (look at AMD Vanilla patch guide), USB Mapping (I personally use USBToolbox + UTBMap) and S/N for proper iMessage support

## Known Issues

- Front jack not working
- Kext for RTL Ethernet need to be added
