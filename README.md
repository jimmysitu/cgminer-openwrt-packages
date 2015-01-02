OpenWrt packages for Avalon firmware
=====================================
Usage
----
* make a link or just copy one or more dir to your openwrt_root/feeds/packages/utils
* cd to openwrt_root
* run:

    ./scripts/feeds update -i
    ./scripts/feeds install cgminer

* Open configuration menu: make menuconfig
* Find the package: Utilites ----> cgminer, [M] it
* Save and exit
* make package/cgminer/compile

