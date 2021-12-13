# rtw89-usb

Please feel free to use it under GPL license.
Also welcome to upstream to the Linux kernel if you want.

Driver for 802.11ax USB Adapter with chipset:
  RTL8852AU 
  
  [Dlink DWA-X1850 AX1800](http://www.dlinktw.com.tw/home/product?id=10120)

This driver is based on Realtek's [rtw89 driver](https://github.com/torvalds/linux/tree/master/drivers/net/wireless/realtek/rtw89) in Linux main trunk.
It's not the formal release, and it's not updated for a long time. 
Hope there is still some which can help, and sooner someone may update onto the linux kernel for USB wifi.

## Build

```console
$ make clean
$ make
```

## Installation

Load driver for test:
```console
$ sudo mkdir -p /lib/firmware/rtw89
$ sudo cp fw/rtw8852* /lib/firmware/rtw89/
$ sudo modprobe mac80211
$ sudo insmod rtw89_core.ko
$ sudo insmod rtw89_usb.ko
```

## General Commands

On Going.
It's not the completed one, and not updated for a while. 


    
