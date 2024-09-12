 ```
Device name: Poco F4 / Redmi K40s
Device codename: munch
Device maintainer: Mudit
```

# Notes:
- DIRTY FLASHABLE!! (Clean Flash Recommended)
- Flash Guide [here](https://github.com/Project-PixelStar/official_devices/blob/14/instructions/munch.md)
- Flash HyperOS V816.1.0.3.0.ULMMIXM Firmware [Downlaod](https://xmfirmwareupdater.com/firmware/munch/stable/OS1.0.3.0.ULMMIXM/)
- Let the rom settle
- BB improves after 1-2 cycles
- DC Dimming needs kernel side support
- Leica Micam build in which fully functional
- No Heating issues were found in testing
- Dolby build in
- Don't report bugs with custom kernels
- Flash Global Firmware for better BB

# v3.3 - Uday
- Removed Clear Calling
- Switch to opengl
- Addressed issue where refresh rate changes to 60hz on landscape for all the apps
- Fixed TEE
- STRONG Integrity and Locked Bootloader until google fcks up
- Upsteamed NOVA Kernel
- Fix corner cutouts in display
- Minor improvements

# v3.2 - Uday
- Improved Powerhint
- Add Clear Calling Support (Needs some testing since it was just a flag)
- Updated blobs to HyperOS V816.1.0.3.0.ULMMIXM
- Add Equalizer to XiaomiDolby & expose in launcher
- rootdir: Set ro.boot.hardware.revision property
- Improvements and fixes in 60HZ on Landscape
- keylayout: Copy using Soong
- Add back LDAC/LDHC support
- Misc Under the hood changes

# v3.0 - Uday
- Switched to Nova Kernel 
- Switched to Neutron Clang
- Addressed random system ui crash and reboots
- Optimized Powerhint
- Fixed Per app refresh rate bug
- LDAC Support is removed
- Adapted Dolby for QPR3
- Added Uclamp Support
- Add ripple animation for face unlock

# v2.5 - Uday
- Rebased Device Tree 
- Optimized kernel
- Add option for "60HZ on landscape" in per-app-rr
- Improve the design for termal profiles and per app rr pages
- Optimized ART 
- Fix Dolby on Bluetooth
- Update blobs to HyperOS V816.0.1.0.ULMMIXM
- Make signed builds

# v2.0 - Uday
- Rebased DT
- Switch to Star Kernel
- KSU inbuilt
- Spatial audio has been dropped
- Dolby and Leica are inbuilt
- Add Support for increased touch polling rate (Kernel Side support)
- Adapt Part Switches for QPR2
- Rom is compiled with LTO 
- Add Support for KProfiles (Kernel Side Support) 
- Move Thermal Profiles to System and add icon for it
- Many under the hood changes...

# v1.3 - Uday
- Feb security patch
- Switched to nexus kernel (N0K is WIP) (KSU Inbuild)
- Fixed wired headphones
- Touch control page in thermal profiles
- audio: fixup audio io policy voip_rx flags
- Build mapperextensions 1.2
- rootdir: audio HAL: Optimize for Spatial Audio
- Fix "/sys/ lines must have 5 or 6 entries"
- Do not try to load kernel modules
- some under the hood changes... 

# v1.2
- Switch to N0Kernel [KSU inbuilt]
- Nuked KProfiles
- munch: Update blobs to V14.0.6.0.TLMMIXM 
- update other fp to latest version
- munch: Update Adreno blobs from LA.UM.9.14.r1-23300-LAHAINA.QSSI14.0
- munch: init: rm package cache on early boot
- munch: Stop using Vulkan UI renderer!! 
- munch: Inherit TouchFeature Type
- munch: Switch to SkiaGL Threaded
- Switch to Oneplus Dolby
- Added support for ac4 dolby decoders
- munch: Use 8Gb dalvik heap size config
- munch: Silence some spammy logging
- Update some deprecated code
- munch: Optimise dex flags
- munch: rootdir: Hide Magisk Better
- munch: Build VNDK 30, 31, 32, 33 fallback
- munch: parts: Add {navigation,video} thermal profiles
- munch: Enable VoNR Calls support
- Revert, update some props from miui
- smooth_display -> refresh control page
- Fixed MICAM Issue
- Other changes which I forgot to mention

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

