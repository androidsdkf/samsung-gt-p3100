Samsung Galaxy Tab 2 7.0 GT-P3100 Stock firmware flash file.

1. Download and install [Android command line tools] for [ADB].
1. Connect tablet to USB, enable **USB debugging** in **Developer Options**.
1. Ensure device is listed in with command `adb devices`.
1. Download [firmware] for Android [4.2.1] or [4.0.3].
1. Download [Odin Downloader] for writing firmware [v3.11.1].
1. Enable root access with command `adb root`.
1. Switch to *download mode* with `adb reboot download`.
1. Open [Odin] and ensure device is added in **Log**.
1. Select **AP** and choose path of firmware `.tar.md5` file.
1. Once its ready, select **Start**.

[Android command line tools]: https://developer.android.com/studio#command-tools
[ADB]: https://adb.clockworkmod.com/
[firmware]: https://firmwarefile.com/samsung-gt-p3100
[4.0.3]: https://www.mediafire.com/file/lqmdvwm33h09ipr/P3100DDALE1_P3100ODDALE1_INU.zip/file
[4.2.1]: http://www.mediafire.com/file/ipr10w0zgwhr4ht/P3100DDCNA3_P3100ODDCNB1_INU.zip/file
[Odin Downloader]: https://odindownloader.com/category/download
[v3.11.1]: http://www.mediafire.com/file/ty1jm4nquo4r872/odin3_v3.11.1.zip/file
[Odin]: https://odindownloader.com/tutorials/use-odin-downloader

<br>

### References

- [Samsung Galaxy Tab 2 7.0 GT-P3100 Stock Firmware :: Firmware Panda](https://firmwarepanda.com/samsung-galaxy-tab2-7-0-gt-p3100-firmware/)
- [Samsung Galaxy Tab 2 7.0 P3100 Recovery Mode and Download Mode](https://droidrecovery.com/samsung-galaxy-tab-2-7-0-p3100-recovery-mode/)
- [Download Mode SAMSUNG P3100 Galaxy Tab 2 7.0 :: HardReset.info](https://www.hardreset.info/devices/samsung/samsung-p3100-galaxy-tab-2-70/download-mode/)
- [not able to get into download mode for galaxy tab 2 7.0 P3100 :: XDA Developers](https://forum.xda-developers.com/t/not-able-to-get-into-download-mode-for-galaxy-tab-2-7-0-p3100.2272757/post-41289658)
- [How to use Odin Downloader :: Odin Downloader](https://odindownloader.com/tutorials/use-odin-downloader)
