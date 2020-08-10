# Fastboot Images For Oppo Devices
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Facervenky%2Foppofastboot)](https://hits.seeyoufarm.com) [![Hits](https://img.shields.io/github/issues-closed/acervenky/realmefastboot)](https://github.com/acervenky/oppofastboot/issues)

| Device | Region | Firmware Version | Link |
| :-: | :-: | :-: | :-: | 
| Oppo Reno 10x Zoom | IN | A20 | [AFH](https://www.androidfilehost.com/?fid=8889791610682911902) |


If your device is not listed, please follow this guide :\
[![](http://img.youtube.com/vi/WIPsJqIXrmk/0.jpg)](http://www.youtube.com/watch?v=WIPsJqIXrmk "")


# Steps To Flash 
- Download Latest Fastboot Files From Google

- Open cmd in the fastboot folder

- Boot device in fastboot mode

Use following commands to flash the images :
```
fastboot flash boot boot.img

fastboot flash system system.img

fastboot flash vbmeta vbmeta.img

fastboot flash vendor vendor.img
```

# Boot Partition Damaged Error After Root
Use the following command while in fastboot mode :
```
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
```
