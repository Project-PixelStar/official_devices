# Flash ROM on Redmi Note 11 Spes & Spesn

*Jashkirat Virdi, January 13, 2024*

1. Bootup OrangeFox Recovery
2. Select "Wipe", and tick data (only if your device is not encrypted, or if it is encrypted with FDE). Then tick cache, and tick dalvik. Unless there is a very specific reason which requires it, do NOT wipe system or vendor - wiping them manually might end in tears.
3. If you are changing ROMs on a device that is encrypted with FBE, then you must format data either before or after flashing the new ROM. If you have a device with A/B partitions, then you must format data both before, and after, flashing the new ROM.
4. Swipe to wipe (this will restore the installed ROM to a known state, and will remove apps/settings that might be incompatible with the ROM that you wish to install).
5. Select the ROM that you want to flash (From Internal Storage, SD Card, or OTG).
6. Swipe to flash.
7. Reboot OrangeFox recovery - before doing anything else - so that any changes to partitions/filesystems done by flashing the new ROM will take full effect.
8. Flash whatever else you might want to flash (e.g., GAPPs, Magisk, etc.).
9. Reboot your device.
10. Wait for a long time while the new ROM sets itself up (go and make a cup of tea!).
11. Enjoy.

**NOTES:**

Credit - [OrangeFox Wiki](https://wiki.orangefox.tech/en/guides/flashing)
