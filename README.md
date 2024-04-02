# Raspberry-Pi-Configuration
This repository is used as a virtual storage space for everything I have managed to track down and use over the years, in my effort of creating, optimizing and maintaining my Raspberry Pi Configuration.

## Hardware

- [Raspberry Pi 4 Low-Profile Cooler](https://www.phonegallerystore.gr/shop/pc-image-sound/raspberry-pi/%ce%b1%ce%be%ce%b5%cf%83%ce%bf%cf%85%ce%ac%cf%81-%ce%b3%ce%b9%ce%b1-raspberry-pi/raspberry-pi-4-low-profile-cpu-cooler-with-rgb-and-heatsink-for-raspberry-pi-silver/)
- 


## System Leaning

- [Remove uncessary software](https://medium.com/@sean_t_king/how-to-remove-un-necessary-software-from-your-raspberry-pi-server-fa312f83e00)
- [Log2Ram](https://singleboardbytes.com/1594/install-use-log2ram-raspberry-pi.htm)
  
## Hardening

- [Delete the Pi User](https://www.pragmaticlinux.com/2021/06/delete-the-pi-user-from-your-raspberry-pi/)
- [Disable Wifi](https://pimylifeup.com/raspberry-pi-disable-wifi/)
- [Setup a Static IP Address](https://pimylifeup.com/raspberry-pi-static-ip-address/)
- [Disable IPv6](https://www.howtoraspberry.com/2020/04/disable-ipv6-on-raspberry-pi/)

## Security

- [Fail2Ban](https://pimylifeup.com/raspberry-pi-fail2ban/)
- [Two-Factor Autentication](https://www.raspberrypi.com/news/setting-up-two-factor-authentication-on-your-raspberry-pi/)
- [Mac Address Spoofing](https://pimylifeup.com/raspberry-pi-mac-address-spoofing/)
  
## Networking

- [Sync Time with a Server](https://raspberrytips.com/time-sync-raspberry-pi/)

## Updating

- [Auto Update Raspberry Pi using a Script and Cron](https://www.paulligocki.com/auto-update-raspberry-pi-using-a-script-and-cron/)



## DietPi

DietPi is an extremely lightweight and slim/diet version of Raspberry OS, it's not it's own Operating System or Distribution. DietPi is just a bundle of scripts on top of a standard Debian installation. 

Depending on your Single Board computer (SBC), DietPi is using different base images. Mainly used images are Armbian, Meveric or for PRi boards Raspberry OS, that means that Raspberry OS is used as base image, including kernel or firmware.

## Why DietPi instead of Raspian?

- Reduced amount of installed software.
- DietPi boots much faster. 
- The mount of r/w operation has been reduced down to a minimum to allow a longer lifetime of SD cards.
- DietPi uses a highly optimized kernel and File System, less prone to errors.
  
Advantages :

- SSH Pre-Installed ✅
- Lightspeed Boot ✅
- Logs in RAM [Default] ✅
- Temporary files in RAM [Default] ✅
- Low RAM & Disk Usage ✅
- Low Power Consumption ✅
- Headless Mode [Default] ✅
- DietPi-Launcher  - Easy Install/Unistall lots of apps (including Pihole, Unbound) ✅
- Firewall pre-installed?
- Well-Documented ✅
- Malware scanner?

Disadvantages :

- Installing apps, runs them locally. ❌
- Docker can be set up and used, but requires manual configuration. ❌ 

##  Apline Linux 

Sure i could use just pure Debian or Alpine, but why? I would need to add my typical required tools to them anyway, like log2ram, ntp sync, docker, micro, dig, etc. Just not worth my time to do that manually when DietPi already has most of those included without being bloated.

alpine linux (as an OS) does wonder on raspberry pi. if you only need docker (or podman) that can be a good choice. it has obscure functions, and works a bit differently than other common distribution but it does wonders for performance, mostly because the bare install is less than 20m, and it load and runs on ram

## Raspian 

## Comparative Data

- https://docs.google.com/spreadsheets/d/1mDHGZC-H6tU6_O8kuLTG8d4A8Nt7lV1Q7MXTR_6qw30/edit#gid=0


## Sources

- [Using Raspberry Pi to Control a PWM Fan and Monitor its Speed](https://blog.driftking.tw/en/2019/11/Using-Raspberry-Pi-to-Control-a-PWM-Fan-and-Monitor-its-Speed/)

- [ar51an - Raspberrypi-Fan-Control](https://github.com/ar51an/raspberrypi-fan-control)

- [RaspberryCast 3.0](https://github.com/vincelwt/RaspberryCast)


