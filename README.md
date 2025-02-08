# Samsung Galaxy Tab A 10.1" 2019 LTE version (SM-T515)
![Samsung Galaxy Tab A 10.1" 2019](https://images.samsung.com/is/image/samsung/id-feature-metal-unibody-design-for-a-premium-feel-156191669?$FB_TYPE_A_PNG$)
This is just an experimental device tree, forked from [samsung-exynos7904-devs/android_device_samsung_gta3xl](https://github.com/samsung-exynos7904-devs/android_device_samsung_gta3xl).
This might not successfully working to bring ARMv8-A, because from the factory, this tablet runs with arm32_binder64 a.k.a 64 bit SoC/CPU but run on 32 bit OS.
And this lacking the common files for supporting both the LTE (SM-T515) and the WiFi only version (SM-T510), help are greatly appreciated because I really need to make a vendor partition image to make arm64 GSI working on this tablet.

I might build the half-baked common files cuz I founded out Samsung Galaxy A40 (SM-A405FM) has some identical hardware, but definitely will not guaranteed working.
I have no skill about this thing so I only learn by observing the existing ones.

# Basic	Spec Sheet
From [gta3xlwifi-dev/device_samsung_gta3xlwifi](https://github.com/gta3xlwifi-dev/device_samsung_gta3xlwifi?tab=readme-ov-file#device-specifications)
| Basic | Spec Sheet |
|-------|------------|
| SoC   | Exynos 7904 (14 nm) |
| CPU   | Octa-core (2x1.8 GHz Cortex-A73 & 6x1.6 GHz Cortex-A53) |
| GPU | Mali-G71 MP2 |
| Memory | 2GB/3GB RAM, LPDDR3 |
| Shipped Android Version | 9.0 (Pie), upgradable to Android 11 with One UI 3.0 |
| Battery | Non-removable Li-Po 6150 mAh battery |
| Storage | 16GB/32GB/64GB/128GB, eMMC 5.1 |
| Battery | Non-removable Li-Po 6150 mAh battery |
| Dimensions | 245.2 x 149.4 x 7.5 mm (9.65 x 5.88 x 0.30 in) |
| Display Type | TFT LCD, ~80.7% screen-to-body ratio |
| Display Size | 10.1 inches, 295.8 cm² |
| Display Resolution | 1200 x 1920 pixels, 16:10 ratio (~224 ppi density) |
| Rear Camera (Single Camera) | 8 MP, f/2.0, autofocus |
| Front Camera | 5 MP, f/2.2 |
