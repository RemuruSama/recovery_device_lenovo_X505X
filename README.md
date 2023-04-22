# TWRP device tree for Lenovo Smart Tab M10 HD wifi (TB-X505X)

## Release info
This is an unofficial build.  It decrypts data partition.  MTP working.  Install at your own risk.

Build with minimal AOSP TWRP for Android 11.0.

### About Device

![Lenovo Smart Tab M10 HD](https://static.lenovo.com/ww/campaigns/2019/smarttab/lenovo-smart-tab-gallery-5.jpg "Lenovo Smart Tab M10 HD (TB-X505X)")

Recovery Device Tree for Lenovo Smart Tab M10 HD LTE (TB-X505X)
================================================================
Component   | Specs
-------:|:-------------------------
Chipset| Qualcomm Snapdragon 429 (SDM429)
CPU | ARM Cortex-A53, Quad-Core, 2.0 GHz
GPU     | Qualcomm Adreno 504, 650 MHz
Memory  | 2 GB (soldered)
Shipped Android Version | 9.0 (Pie), upgrade to 10 (Android Q)
Storage | 16 GB (eMPC)
MicroSD | Up to 256 GB
Battery | 4850 mAh, Li-Po (non-removable)
Display | 1280x800 pixels, 10.1"
Front Camera | 2.0 MP, fixed focus
Rear Camera  | 5.0 MP, auto focus
Wifi | dual band, 802.11a/ac/b/g/n
Bluetooth | v4.2
USB | USB-C (micro USB)
Release Date | July, 2019


To build:

```
. build/envsetup.sh
lunch twrp_X505F-eng
mka recoveryimage
```
