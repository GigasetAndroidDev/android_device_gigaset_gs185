# TWRP for Gigaset GS185

Minimal tree to build TWRP in android-9.0

## Compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_gs185-eng

mka adbd recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm MSM8917 Snapdragon 425
CPU     | Quad-core 1.4 GHz ARM® Cortex™ A53
GPU     | 500MHz Adreno 308
Memory  | 2 GB RAM
Shipped Android Version | 8.1
Storage | 16 GB
MicroSD | Up to 256 GB
Battery | Removable Li-Po 4000mAh battery
Dimensions | 147 x 70,6 x 8,8 mm
Display | 720 x 1440 pixels, 5.5 inches (293 ppi)
Rear Camera | 13 MP, f/2.0, autofocus, LED flash
Front Camera | 13 MP

## Device picture

![GS185](https://www.gigaset.com/media/catalog/product/cache/1/image/1800x/040ec09b1e35df139433887a97daa66f/g/s/gs185_metal_cognac_fr_1.jpg "GS185 in blue")
