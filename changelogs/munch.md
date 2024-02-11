 ```
Device name: Poco F4 / Redmi K40s
Device codename: munch
Device maintainer: Mudit
```

# Notes:
- Clean Flash [Sry for inconvenience]
- Flash Guide [here](https://github.com/Project-PixelStar/official_devices/blob/14/instructions/munch.md)
- Flash 14.x regional Firmware
- Let the rom settle
- BB improves after 1-2 cycles
- DC Dimming and Kprofiles need kernel side support
- Leica Micam build in
- No Heating issues were found in testing
- Dolby And Diarac Build in
- Don't report bugs with custom kernels
- Flash Global Firmware for better BB

# v1.1 
- Fixed Recovery issue where u could not boot into recovery after flashing rom [requires clean flash]
- rebased tree
- Added new dolby implementation from marble
- Added Spatial audio 
- Fixed Kprofiles
- Inlined Nexus Kernel  [KSU inbuild]
- Rom is compiled with LTO 
- Tune Powerhint for smoothness
- Disable backpressure prop
- Disable frame rate override feature
- Re-enable smooth motion in surfaceflinger
- Disable Skia tracing by default
- Introduced Extended Fastcharge implementation
- Introduced Battery Friendly Pocket mode
- Update clear speaker audio using DTMF + Chirp tones
- Import minimal Mi_thermald changes from AOSPA Trees
- Add some missing libs 
- under the hood changes

# January Update
- Initial A14 Update
- Added Moto Dolby
- Spatial Audio
- Added HBM, DC Dimming, Per-App RR, etc...
- Inlined with N0kernel
- Shifted to MIUI Haptics
- And many more things...

