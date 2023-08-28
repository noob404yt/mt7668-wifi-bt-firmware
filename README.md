# Firmware files for MT7668 WiFi/BT chip
Firmware files required by MT7668 WiFi/BT chip on PS4. These files are to be added to the initramfs.cpio.gz.

## How to add firmware files to initram?
For the detailed tutorial, click [here](https://ps4linux.com/ps4-mt7668-wifi-bluetooth-kernel-drivers#How_to_build_initram_with_MT7668_WiFi_Bluetooth_firmware_files). Else, keep reading.
1. Extract initram.
2. Clone this repository into the `lib/firmware` folder.
3. Repack initram and use with the [modified kernel](https://ps4linux.com/ps4-mt7668-wifi-bluetooth-kernel-drivers#Requirements).

## Thanks to
1. *novice4321* (Sponsored initial driver port to PS4)
2. *Reo Au In* (Sponsored inubilt drivers; tested on Belize)
3. *misfit-mischief* (Tested on Baikal)
4. *DF_AUS* (Donor)
5. Many others (will update as and when I remember)

## Support me
Kindly donate on [Ko-fi](https://ko-fi.com/noob404), if you can.
