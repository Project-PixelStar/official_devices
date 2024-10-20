 ```
Device name: Redmi note 13 Pro 5G / Poco X6 5G
Device codename: garnet
Device maintainer: JYR_RC
```

# Notes:
- Clean flash recommended
- Flash Guide [here](https://github.com/Project-PixelStar/official_devices/blob/14/instructions/garnet.md)
- Let the rom settle
- BB improves after 1-2 cycles
- No Heating issues were found in testing
- Dolby build in
- Don't report bugs with custom kernels
- Flash Global Firmware for better BB

# v3.4 - Uday :
- Integrity pass default
- Based oct security patch
- Bump to version 3.4
- PixelPropsUtils: Restore keystore safetynet attestation blocking
- PixelPropsUtils: update to latest komodo beta
- Switch to CUSTOM QTI thermal
- Added missing sepolicy thermal logs spam
- Fixed flickering in AOD (POCO DEVICES)
- Improved udfps unlock speed
- Improvements in miuicamera (redmi and poco devices)
- Fixed filters video recording miuicamera
- Fixed small micro lags in 60hz (qs)
- Fixed icon face unlock in loockscreen
- Switch Kernel to STRIX 5.10.226 clang version 19.0.0 ksu support
- Build libutils.vendor
- Allow setsockopt syscall for qcom c2audio
- Update from V816.0.12.0.UNRMIXM
- Import missing media codec blobs
- Move media codecs dolby to vendor
- Use AOSP default Codec2/OMX ranks
- Move dolby to hw/xiaomi
- Update vendor blobs from V816.0.12.0 UNRMIXM

# v3.3 - Uday
- Sep security patch
- Integrity pass default
- Add intelligent equalizer setting in dolby
- Added zram support
- Enable option for full screen aspect ratio
- Remove hw_acc effect
- Configure RefreshRate brightness thresholds
- Build oss soundtrigger hal
- Disable ELF checks for some camera libraries
- Set display idle time to 0 fixes screen flickering in low brightness
- Improved automatic brightness
- Improvements in colors, now they are more vivid
- Fix the faceunlock icon from being hidden in fod
- Improved speed and performance in games
