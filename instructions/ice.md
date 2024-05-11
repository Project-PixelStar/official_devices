```
Device name: Realme 9 Speed edition 5g
Device codename: ice
Device maintainer: Abhayabhi4721
```

# Method:

1. You must on Realme UI version between f.06 to f.14
2. Use los recovery -link given below
3. Reboot to recovery
4. Now go to Apply update -> Apply via ADB and then use the command:

adb sideload path/to/romname.zip

Note: If the status stops at 47% don't panic since that's normal
- After sideload completes, if the cmd window shows xfer:1.00x, that means the rom is flashed completely.

5. Go back to recovery then do a factory reset/format data, then reboot and enjoy!

**Update**
1. Reboot to recovery
2. While in recovery, navigate to Apply update -> Apply from ADB
3. adb sideload rom.zip (replace "rom" with actual filename)
4. Reboot to system & Enjoy

**OTA**
1. Download the update from Updater
2. Install it.
3. Reboot and Enjoy

If you want to root:
Go to recovery
Update via adb, then sideload the Magisk-v26.0.zip
Done very simple as that.

# Downloads:

* ROM: [Download](https://www.pling.com/p/2066696/)
* Recovery: [Download](https://drive.google.com/file/d/1-RLj9UkY7UzTHKaiXW8RsR64DSVBcvZ4/view?pli=1)

## Note:

* Always clean flash/wipe data if you are coming from any other ROM or if you are coming from stock.
* Flash your region's latest firmware.
* Check the changelog before flashing.
