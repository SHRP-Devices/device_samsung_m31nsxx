# SHRP device tree for Samsung Galaxy M21

## How to build
1. Set up the build environment following instructions from [here](https://shrp.github.io/#/guide) (Fully compatible/tested)
2. Clone the device tree in the root of SHRP source:
```
git clone -b android-11.0 https://github.com/soulr344/device_samsung_m21nsxx.git device/samsung/m21nsxx
```
3. To build:
```
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_m21nsxx-eng && mka recoveryimage -j$(nproc)
```
