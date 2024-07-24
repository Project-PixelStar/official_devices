```
Device name: Xiaomi 11T Pro
Device codename: vili
Device maintainer: Jezzay97
```
# v3.0 - Uday
- July security patch QPR3
- Rebased device tree
- Signed user build to pass play integrity by default
- Addressed some sepolicy denials
- Added Notch Bar Killer overlay
- Use AOSP default Codec2/OMX ranks
- Improved dolby audio config
- Fixed thermal config path and permission for Xiaomi parts
- Switched to vendor-defined display color modes
- Added charging control and fastcharge support
- Built with clang 18

- Kernel:
- switched to void kernel thanks to Omar
- KernelSU by default
- Improved scheduler
- Overclock touch SPI bus to 10 MHz
- Improved idle drain slightly

# Notes:
- CLEAN FLASH
- Let the rom settle
- BB improves after 1-2 cycles

# May Update : 
- Initial QPR2
- Rebased and cleaned up device trees (thanks Omar for helping)
- Dolby audio (Dax config by klozz)
- Adjust Color Modes from stock (Thanks Klozz)
- Updated Xiaomi parts from Haydn
- Added Clear speaker drawable
- Added SpatialAudio
- Added dynamic thermal profile implementation by Haydn
- Updated included firmware to V816.0.1.0.UKDEUXM
- Updated vili specific blobs to V816.0.1.0.UKDEUXM (credits to TheStrechh)
- Updated common blobs from Haydn V816.0.1.0.UKKCNXM
- vili: overlay: Adjust status bar padding
- sm8350-common: overlay: Add Notch Bar Killer overlay
- better RAM management
- Update sf durations from Pixel 5
- Move from phase offsets to work durations
- Use dex2oat64 on sm8350
- Reduce LOWI debug level
- Now much smoother..

- Kernel:
- Updated KSU to the latest version
- Rebased to include latest changes from lineageOS
- Added optimization flags
