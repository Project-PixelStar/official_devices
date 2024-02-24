```
Device name: Realme GT 5G
Device codename: cupidr
Device maintainer: MNoxx
```

# Method:

flashing-for-beginners:

How to install Custom rom [Beginners Friendly]

1. You must on latest Realme UI depends on your region.
2. Unlock your bootloader.
3. Download all the 3 images(boot, dtbo and vendor_boot) from the website
4. Reboot to bootloader
5. flash all the 3 images by using the following commands:

fastboot flash boot boot.img

fastboot flash vendor_boot vendor_boot.img

fastboot flash dtbo dtbo.img

6. After all images get flashed successfully. Boot your phone to Recovery from Bootloader with "fastboot reboot recovery" command.
7. Now go to Apply update -> Apply via ADB and then use the command: 

adb sideload path/to/romname.zip


Note: If the status stops at 47% don't panic since that's normal

- After sideload completes, if the cmd window shows xfer:1.00x, that means the rom is flashed completely.

8. Go back to recovery then do a factory reset/format data, then reboot and enjoy!

If you want to root:
Go to recovery
Update via adb, then sideload the Magisk-v26.0.zip

If you want to preserve your root in the next OTA updates.
Use the same thing you used to preserve like in Realme UI.

Done very simple as that.

# Downloads:

* ROM: [Download]()
* Recovery: [Download](https://drive.google.com/file/d/14elHLllnIrqncnT4m61ZJ5qAnM_gM67m/view?usp=drive_link)

## Note:

* Always clean flash/wipe data if you are coming from any other ROM or if you are coming from stock.
* Flash your region's latest firmware.
* Check the changelog before flashing.
