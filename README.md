# Dell Latitude E6330 Mojave Hackintosh EFI

This repository contains the EFI boot partition of my Dell Latitude E6330 running macOS Mojave 10.14.4.  

Known issues:
1. Keyboard mapping for Fkey row is wrong.  Still working on that.
2. Sleep isn't perfect.  Usually works, but not always.
3. Battery indicator is intermittent.  I have done the DSDT patch and have all the required kexts, but it only works sometimes - not always.  Prefer to use HWMonitor because it can read the battery percentage even when the macOS indicator cannot.  Power adapter status doesn't change when you plug in or unplug the adapter.

I've also included the decompiled droptables from origin.  Of course, with laptops, it's ALWAYS recommended to do this yourself because even two of the exact same laptop might have different tables.  Use them at your own risk... they're mostly here for my own use.

Laptop specs:

Dell Latitude E6330
Core i5-3320M 2c4t CPU w/ Intel HD 4000 Graphics
8GB DDR3 RAM
WD Blue 250GB SSD
Broadcom BCM94352HMB


Working:
WiFi (Up to 250mbps Up and Down)
Bluetooth
AirDrop
Intel Turboboost
Graphics Acceleration
Software Brightness Control
Parallels Virtualization
SSD Trim
Lid Close to Turn Off Screen
Sleep (semi-working)
Battery Indicator (semi-working)
