# EFI Hackintosh - X99-F8 2021 - OpenCore 0.9.6

## Features
- MacOS Ventura 14.1 Support
- Fenvi HB-1200 (BCM4360) Full Support (Please patch with OpenCore Legacy Patcher after fresh install)
- AMD RNDA1 and RDNA2 Support (agdpmod-pikera)
- All USB 2.0 and 3.0 mapped
- Only two rear USB 3.0 (bottom) is not working (Thanks XHCI Port Limit!)
- Front USB 3.0 Working

![Captura de Tela 2023-11-06 às 21 47 46 copy](https://github.com/moesuito/EFI-Hackintosh_X99-F8-2021_OC-0.9.6/assets/57041838/6ae25a2f-feaf-4c6a-848e-b0f78403eaa2)
## **Specs**
| **Component** | **Model** |
| ------------- | --------- |
| CPU | Intel(R) Xeon(R) 1660 V3 @ 4.3 GHz (Overclocked) |
| Motherboard | Huananzhi X99-F8 2021 (Rev 2.0) |
| GPU | Radeon RX 6600 8 GB |
| RAM | 64GB DDR4 Atermiter ECC 2400MHz CL14 (4x16GB) |
| WAN | Fenvi HB-1200 1200Mbps (BCM94360) |
| LAN CHIPSET | Realtek® RTL8111H Gigabit LAN |
| AUDIO CHIPSET | Realtek® ALC897 Codec |
| STORAGE | 512GB Asgard AN3 PCIe 3.0 |
## **What works**
- MacOS Sonoma 14.1 and Updates
- Wifi
- Bluetooth
- All GPU Acceleration
- Turbo Boost for V3 Xeons
- USB 3.0

## **What doesn't work**
- Sleep
- Optical Digital out

## BIOS Settings

**Disable**
- Secure Boot
- Serial/COM Port
- Compatibility Support Module (CSM)
- CFG Lock

**Enable**
- Above 4G decoding
- EHCI/XHCI Hand-off
- OS type: Windows 8.1/10 UEFI Mode
- SATA Mode: AHCI
