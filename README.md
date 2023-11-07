# EFI Hackintosh - X99-F8 2021 - OpenCore 0.9.6

## Features
- MacOS Ventura 14.1 Support
- Fenvi HB-1200 (BCM4360) Full Support (Please patch with <a href="https://github.com/dortania/OpenCore-Legacy-Patcher"> OpenCore Legacy Patcher</a> after fresh install)
- AMD RNDA1 and RDNA2 Support (agdpmod-pikera)
- All USBs mapped
- Only two rear USB 3.0 (bottom ports) is not working (Thanks XHCI Port Limit!)
- Front USB 3.0 Working
- Supports All Haswell-E CPUs
- Support for Overclocking (Unlocked LGA-2011v3 Core i7's and 16XX-V3 Xeon)
- Support for Unlock Turbo Boost (V3's Xeon)
- Support for <a href="https://github.com/corpnewt/CPU-Name"> CPU-Name</a> (by: <a href="https://github.com/corpnewt/"> corpnewt</a>)
- SMBIOS: MacPro7,1

![Captura de Tela 2023-11-06 às 21 47 46 copy](https://github.com/moesuito/EFI-Hackintosh_X99-F8-2021_OC-0.9.6/assets/57041838/6ae25a2f-feaf-4c6a-848e-b0f78403eaa2)
## **Specs**
| **Component** | **Model** |
| ------------- | --------- |
| CPU | Intel(R) Xeon(R) 1660-V3 @ 4.3 GHz (Overclocked) |
| Motherboard | Huananzhi X99-F8 2021 (Rev 2.0) |
| GPU | Radeon RX 6600 8 GB |
| RAM | 64GB DDR4 Atermiter ECC 2400MHz CL14 (4x16GB) |
| WAN | Fenvi HB-1200 1200Mbps (BCM94360) |
| LAN CHIPSET | Realtek® RTL8111H Gigabit LAN |
| AUDIO CHIPSET | Realtek® ALC897 Codec |
| STORAGE | 512GB Asgard AN3 PCIe 3.0 |
| SMBIOS | MacPro7,1 |
## **What works**
- MacOS Sonoma 14.1 and Updates
- Wifi
- Bluetooth
- All GPU Acceleration
- Turbo Boost for V3 Xeons
- USB 3.0
- AirDrop
- All two NVMe Ports (Both mapped as internal)

## **What doesn't work**
- Sleep
- Optical Digital out
- Resizable BAR (Even with ResizeAppleGpuBars on)

## BIOS Settings

**Disable**
- Secure Boot
- Serial/COM Port
- Compatibility Support Module (CSM)
- CFG Lock

**Enable**
- Above 4G decoding
- EHCI/XHCI Hand-off
- SATA Mode: AHCI

## Benchmarks

Blackmagic RAW

![Captura de Tela 2023-11-06 às 22 02 25](https://github.com/moesuito/EFI-Hackintosh_X99-F8-2021_OC-0.9.6/assets/57041838/2075a997-aec3-48ab-b52e-f9c10cd82c56)

Geekbench 6 CPU and GPU

![Geekbench](https://github.com/moesuito/Hackintosh_EFI_X99-F8_Xeon-E5-1660-V3_Radeon-RX6600/assets/57041838/b02d3741-35f3-4ccd-b5ce-9ed96ecc7634)

Cinebench R23

![Captura de Tela 2023-11-06 às 23 01 55](https://github.com/moesuito/Hackintosh_EFI_X99-F8_Xeon-E5-1660-V3_Radeon-RX6600/assets/57041838/b47ee4ee-a9cd-42d4-a550-d2b0487ba629)

PugetBench for Premiere Pro 2023

- ** Cooming soon **

PugetBench for After Effects 2024

- ** Cooming soon **

  ## Credits
- <p>Special thnx to <a href="https://github.com/luchina-gabriel/"> Gabriel Luchina</a></p>
- <p>His knowledge and repository <a href="https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E"> BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E</a></p>

- [Opencore Team](https://dortania.github.io/getting-started/)
