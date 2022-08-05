# OpenStick
Reverse engineering and mainline porting of msm8916 4g network card

### Completely open source, but commercial use is prohibited!

* Commercial activities include:
 * Sell ​​all system images and their derivatives that were originally free and open for download.
 * Publish products built with the HandsomeMod build system for a fee.
 * Mass sale of devices powered by OpenStick Linux.
* All binary files involving Qualcomm firmware in this project are for learning purposes only, and are subject to the original license of Qualcomm firmware. Any legal problems caused by improper use are at your own risk.

current progress

* Completed the transplantation of some features of msm8916-mainline to the 5.10 stable kernel, and preliminarily completed the transplantation of  HandsomeMod (openwrt), which can complete basic functions with minimal adjustment of settings.
* Completed the driving of most of the functions in the main line and run postmarketOS.
* All peripherals of the msm8916 network card are driven in Debian.
* Finished driving Modem in HandsomeMod.
* Supports programming under the Windows platform.

unfinished

* The video encoder is not working properly for some reason.
* Some wifi models do not support Modem due to the unclear logic of the original factory card switching.
* See the wiki for details.

## Brush package

* This flashing package will overwrite the partition table of the original machine (deleting useless partitions will probably free up more than 3G of space for rootfs) and the bootloader, which is no longer compatible with the Android system. Please make a backup when using it. I also don't offer a way to go back.
* Packaged in release.。

## WIKI 

​     wiki is under construction, welcome to contribute or star! !

  [WIKI地址](https://www.kancloud.cn/handsomehacker/openstick/content)

## 相关链接

  [HandsomeMod build system](https://github.com/HandsomeMod/HandsomeMod)
