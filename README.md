# OpenCore-MSI-B360M-i3-9100-UHD630
Hackintosh for MSI B360M with OpenCore.

## Before That

The [original EFI](https://github.com/SuperNG6/MSI-B360-Big-Sur-EFI/releases/download/12.1/ONLY.IGPU.Macmini8.1.zip)  version was created by [SuperNG6](https://github.com/SuperNG6), and I made some changes based on it, adding themes(themes I used [5T33Z0](https://github.com/5T33Z0/Lenovo-T530-Hackintosh-OpenCore)'s version, thanks to him) and fine-tuned Quirks according to my personal preferences.

Cause of my SSD or something else, I cannot upgrade to Monterey, but that not means this version cannot use to Monterey, I just cannot test it.

Another thing you need to know is that I'm still in the learning phase of OC so it will take a while to get completely out of the reference, but I'll try to get it done.

Also I have a lot of other devices, I can't ask others to update as soon as possible, so I need to master the configuration method by myself to provide the EFI of my other devices, and share with you guys here.

## Configuration

- CPU: i3-9100(UHD630) | 999
- MotherBoard: MSI B360M | 619
- Graphics: UHD 630
- Memory: Gloway 32 GB(16 GB DDR4 * 2) | 369 * 2
- SSD: Asgard AN3 500G | 499
- Hard Disk: 1T HHD 
- WIFI Card: N/A
- Bluetooth: N/A
- Power: Delta NX450（450W）| 269
- Cooling：Thermalright AS120 | 109
- Fan：ARCTIC 12cm | 39
- Cable：JONSBO U3 | 299

## How To Use This EFI?

- Download EFI and copy to your EFI partition on your mac
- Find the proper Serial Number, and setting in your config.plist
- Reboot and enjoy

## How To Get(Config) Your Own EFI?

Check follows posts and just do it, you'll get your own OC/EFI.

- [https://dortania.github.io/OpenCore-Install-Guide/](https://dortania.github.io/OpenCore-Install-Guide/) Dortania's OpenCore Install Guide
- [https://apple.sqlsec.com](https://apple.sqlsec.com) Overview of how to config OC/EFI.
- [https://blog.xjn819.com/post/opencore-guide.html](https://blog.xjn819.com/post/opencore-guide.html) How to setting Quirks in OC/EFI/config.plist.
- [https://github.com/daliansky/OC-little](https://github.com/daliansky/OC-little) Make hotpatch, also you can check `Improvements 系统优化` in [this post](https://github.com/i0Ek3/Hackintosh_4_Hasee_Shinelon_A40L) of mine.


## Credit

- [SuperNG6](https://github.com/SuperNG6)
- [5T33Z0](https://github.com/5T33Z0)
