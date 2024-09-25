### Device: Redmi Note 11
#### Device Code Name: spes/spesn
#### Device Maintainer: JassiV

### Update: 25/09/2024 - Version 3.3

- Remove quad mic support
- Enable slow-cpu media codecs
- Set correct channel mask for earpiece
- Support BT SCO mic for record_24 profile
- Add stereo support to BT SCO Headset Mic
- Correct maximum microphone count
- Address powerhal denials in sepolicy
- Build vendor modules for RIL, WFD, and GPS HAL
- Disable NFC service by default
- Add can-swap-width-height for video codecs
- Revert to previous thermal config
- Disable dynamic refresh rate
- Miscellaneous improvements and bug fixes

### Update: 07/08/2024 - Version 3.2
- **Rebased Device Source**
- Removed Duplicate Sepolicies
- Fixup Partition
- Applied August Security Patch QPR3
- Rebased Device Tree
- Reworked Thermal Management
- Updated Blobs from miui_SPESNEEAGlobal_V14.0.7.0.TGKEUXM
- Switched to SF Phase Offsets from Redfin
- Dropped Vsync Offset Properties
- Switched to Parts Based Refresh Rate QS Tile
- Built Missing Camera & Audio Libraries for 14 QPR3
- Brought Back Refresh Rate Customizations in Settings
- Shifted to NightSilver Kernel
