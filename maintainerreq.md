# To become an official maintainer for Project Pixelstar:

**Before you apply to add your device into our list of official devices, you should know a few things:**

1. You **MUST** own the device. Blind and untested builds aren't allowed. Unified, and devices with minimal hardware changes are also allowed to be maintained . 

2. Your device sources **MUST** be open source for us. Exceptions Allowed .

3. You must have basic git (cherry-pick, squash, etc) knowledge.

4. Your trees should be **clean** and should have **proper authorships** and commit names and should be ready for random inspection .

5. Release builds **MUST** be user.

6. You **MUST** be on SELinux enforcing.

7. Usage of IGNORE_SELINUX_NEVERALLOWS := true MUST be avoided.

8. Prebuilt kernels are only allowed **if your device does not have proper kernel sources**., You **MUSTN'T** ship a prebuilt kernel if you have working kernel sources available just because you save 5 minutes of build time.

9. The device **MUST NOT** include any unused props, overlays or packages. This includes, but is not limited to, packages not being built, packages that don't work, obsolete packages, placebo 'tweaks' or any packages that will include unnecessary and/or unwanted features.

10. You should have some basic knowledge of reading logcats and managing most device releated errors/bugs.

11. You must not maintain more than 3 ROMs including PIxelstar (applies for both official and unofficial) and also XDA threads are mandatory.

12. You **MUST NOT** overclock or do anything that can damage the device. This can cause instability and can harm the device.

13. You should release an unofficial build and **MUST** attach a link in the maintainership form.

14. You **MUST** not ship OEM apps or any blotwareapps in trees. (except OEM camera apps)

15. You should avoid making source changes through any scripts from device sources. and all the tracked repos must be from Project-Pixelstar ( contact core team members for exceptions)

16. you must make use of all the opt-in features and device additions which can be found [here](https://github.com/Project-PixelStar/Flags).

17. You **MUST** meet all requirements as mentioned [here](requirements.md).

18. You **MUST** consider reading rules for maintainers [here](maintainersrules.md).

**Exceptions for some of the requirements maybe made for older phones and during beta stage.**

If all is well, you may apply [here](https://github.com/Project-Pixelstar/official_devices/issues/new/choose)

If you have any doubts/questions, make sure to contact the team on [Our Telegram Group](https://telegram.me/Project_PixelStar) or email us at applicationreview@project-pixelstar.xyz

