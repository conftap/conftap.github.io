---
layout: post
title:  "RK3x88: Flashing a new unpacked ROM on Linux"
date:   2014-04-30 05:30:59
categories: rk3188
---

1. Get [Upgrade Tool][upgradetool] (more info on the [Radxa Wiki][wiki])

2. Get a new [ROM+kernel][rom]

3. Get this [script][script] to flash kernels using the upgrade tool from #1

4. Put your device in USB host mode (hold-down reset while plugging the power cord in)

5. Run the script you got in #3.

Notes:

The script needs an unpacked ROM (like Finless) - so separate files for kernel, boot, recovery, misc, system. 

Make sure to flash the right bootloader.

[upgradetool]: http://dl.radxa.com/rock/tools/linux/Linux_Upgrade_Tool_v1.16.zip
[wiki]:        http://wiki.radxa.com/Rock/flash_the_image#Upgrade_tool_from_Rockchip
[rom]:         http://www.freaktab.com/showthread.php?9389-NEW-Finless-ROM-2-0-KitKat-4-4-2-for-AP6210-wifi-BETA
[script]:      http://www.freaktab.com/showthread.php?10060-Rockchip-Linux-Upgrade-Tool&p=137784&viewfull=1#post137784
