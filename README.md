# Mediatek MT8176 & MT8173

[![N|Mediatek](https://cdn-www.mediatek.com/icons/mtklogo.svg)](https://www.mediatek.com/products/tablets/mt8176)

MT8176 is a Hexa-core, 64-bit tablet platform with ARM Cortex-A72/A53 with clock speeds up to 2.1GHz and IMG PowerVR GX6250 GPU at 600MHz,

  - CPU Cluster 1: ARM Cortex-A72 @ 2.1GHz
  - CPU Cluster 2: ARM Cortex-A53 @ 1.7GHz
  - IMG PowerVR GX6250



# Development

Mediatek devices are known for little to no Custom-ROM development. That's why I'm collecting stuff for building a ROM for my MT8176 device - a Xiaomi Mi Pad 3. Somebody uploaded a full source-code for building AOSP 7.0 for GPD XD+, a device also based on Mt8176 SoC. I trimmed the source-code down and re-uploaded the important stuff on my github.

| Plugin | README |
| ------ | ------ |
| [Vendor/Mediatek/Proprietary/Custom][PlDb] | Custom libs / drivers / hals / configs |
| [Vendor/Mediatek/Proprietary/Hardware][PlGh] | Platform- & Device-Specific libs / drivers / hals / configs |
| [Vendor/Mediatek/Proprietary/External][PlDc] | External libs / drivers / hals / configs |
| [Vendor/Wisky/libs][PlGd] | Device-Specific libs / drivers / hals / configs |
| [Device/Wisky][PlOd] | Device-specific (GPD XD+) files for building a Device-Tree |
| [Device/Mediatek][PlMe] | Platform-specific files for building a Device-Tree |
| [Bootloader / LK][PlGa] | Full source-code for building a bootloader / LK.bin|


Some Kernel-Sources:
  - Mi Pad 3: https://github.com/Goayandi/android_kernel_xiaomi_cappu
  - GPD Xd+: https://github.com/Goayandi/android_kernel_mt8176_common
  - Asus ZenPad 3S 10: https://github.com/Goayandi/android_kernel_asus_z500m
  - Acer IconiaTab B3-A40: https://github.com/Goayandi/android_kernel_acer_b3-a40fhd

   
   [PlDc]: <https://github.com/Goayandi/vendor_mediatek_proprietary_external-mt8173>
   [PlDb]: <https://github.com/Goayandi/vendor_mediatek_proprietary_custom-mt8173>
   [PlGh]: <https://github.com/Goayandi/vendor_mediatek_proprietary_hardware-mt8173>
   [PlGd]: <https://github.com/Goayandi/vendor_wisky_libs-mt8173>
   [PlOd]: <https://github.com/Goayandi/device_wisky-mt8173>
   [PlMe]: <https://github.com/Goayandi/device_mediatek-mt8173>
   [PlGa]: <https://github.com/Goayandi/vendor_mediatek_proprietary_bootable-mt8173>
