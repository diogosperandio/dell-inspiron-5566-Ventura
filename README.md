# macOS Ventura EFI for Dell Inspiron 5566

This repository contains the EFI folder used to install macOS Ventura on a Dell Inspiron 5566.

> For educational purposes only. This configuration is specific to the hardware listed below.

## Hardware specifications

| Component | Specification |
| --- | --- |
| Laptop | Dell Inspiron 5566 |
| CPU | Intel Core i5-7200U (Kaby Lake) |
| Integrated graphics | Intel HD Graphics 620 |
| Storage | Kingston SA400S3 SSD |
| Audio | Realtek ALC3246 |
| Wi-Fi | Intel AC 8265 NGW |
| Ethernet | Realtek RTL810xE |
| Operating system | macOS Ventura 13.7.8 |

The original Wi-Fi card did not work with this configuration, so it was replaced with an Intel AC 8265 NGW.

## Working features
- All functions are working
- Wi-Fi
- Audio and volume keys
- Screen brightness and brightness keys
- Touchpad

## Tools used

1. [Hardware-Sniffer](https://github.com/lzhoang2801/Hardware-Sniffer) — collected the hardware specifications.
2. [SSDTTime](https://github.com/corpnewt/SSDTTime) — generated the ACPI files.
3. [OpCore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) — created the EFI folder. Very easy, great tool.
4. [macOS image](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install-recovery.html) - to -+239,.download legacy versions of macOS including 10.7 to current

.
