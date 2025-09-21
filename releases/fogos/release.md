layout: page
title: test
permalink: /releases/fogos

PixelOS is an AOSP based ROM, with Google apps included and all Pixel goodies. We aim to provide an experience similar to Google Pixel phones with numerous performance enhancements and a small amount of useful additional features.


```
/* Your warranty is now void.

*

* I am not responsible for bricked devices, dead SD cards,

* thermonuclear war, or you getting fired because the alarm app failed. Please

* do some research if you have any concerns about features included in this ROM

* before flashing it! YOU are choosing to make these modifications, and if

* you point the finger at me for messing up your device, I will laugh at you.

*/
```

READ OUR BLOG


Device Specific Issues:

• So far, everything is working



Downloads

Get the latest PixelOS Build for Motorola Moto G34 5G Download



Notes

• GApps are included

• Moto Camera shipped by default (everything works).



Flashing Instructions

Clean flash (coming from a Motorol/stock):

• Reboot to bootloader (fastboot)

• Connect phone to PC

• flash copy-partitions (if you are coming from stock)

• fastboot flash --slot=all boot boot.img

• fastboot reboot recovery

• Select Wipe data/factory reset & confirm

• Go back and select Apply update from ADB

• adb sideload PixelOS*.zip

• After installation complete, Reboot system.



Clean flash (coming from another AOSP ROM):

• Follow the same procedure as dirty flashing ones below, and format data in the end.



Dirty Flash (updating from previous PixelOS ROM):

• Reboot to recovery

• Apply update from ADB

• adb sideload PixelOS*.zip

• After installation complete, Reboot system.



Join our Telegram Group https://t.me/PixelOSChat

We depend on donations to keep our infrastructure running, show your support by donating!

Support PixelOS | PixelOS
PixelOS is a non-profit project that depends on your donations for keeping the project running.

blog.pixelos.net



Source Code

PixelOS http://github.com/PixelOS-AOSP

Device Tree https://github.com/sm6375-PixelOS/android_device_motorola_fogos

https://github.com/sm6375-PixelOS/android_vendor_motorola_sm6375-common

Vendor Tree https://github.com/sm6375-PixelOS/android_vendor_motorola_fogos

Kernel Tree https://github.com/sm6375-PixelOS/android_kernel_motorola_sm6375



ROM OS Version: Android 15.

ROM Kernel: Linux 5.4.x

Stable Release Date: 13 July 2025
