---
layout: post
title:  "RK3x88: Flashing a new ROM on Linux"
date:   2014-04-30 05:30:59
categories: rk3188
---

1. Get upgrade_tool[upgrade_tool]

2. Get a new ROM+kernel[rom]

3. Get this script to flash kernels[script]

4. Put your device in USB host mode (hold-down reset while plugging the power cord in)

5. Run the script you got in #3.

Notes:
The script needs an unpacked ROM (like Finless) - so separate files for kernel, boot, recovery, misc, system. 
Make sure to flash the right bootloader.

[rkflashtool]: http://dl.radxa.com/rock/tools/linux/Linux_Upgrade_Tool_v1.16.zip
[rom]:         http://www.freaktab.com/showthread.php?9389-NEW-Finless-ROM-2-0-KitKat-4-4-2-for-AP6210-wifi-BETA
[script]:      http://www.freaktab.com/showthread.php?10060-Rockchip-Linux-Upgrade-Tool&p=137784&viewfull=1#post137784
