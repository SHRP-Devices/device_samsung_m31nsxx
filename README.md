# SHRP device tree for Samsung Galaxy M31

## How to build
1. Set up the build environment following instructions from [here](https://shrp.github.io/#/guide) (Fully compatible/tested)
2. Clone the device tree in the root of SHRP source:
```
git clone -b android-11.0 https://github.com/soulr344/device_samsung_m31nsxx.git device/samsung/m31nsxx
```
3. To build:
```
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_m31nsxx-eng && mka recoveryimage -j$(nproc)
```
