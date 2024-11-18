# Raspberry-Pi-Configuration
This repository is used as a virtual storage space for everything I have managed to track down and use over the years, in my effort of creating, optimizing and maintaining my Raspberry Pi Configuration.

## Hardware

- [Raspberry Pi 4 Low-Profile Cooler](https://www.phonegallerystore.gr/shop/pc-image-sound/raspberry-pi/%ce%b1%ce%be%ce%b5%cf%83%ce%bf%cf%85%ce%ac%cf%81-%ce%b3%ce%b9%ce%b1-raspberry-pi/raspberry-pi-4-low-profile-cpu-cooler-with-rgb-and-heatsink-for-raspberry-pi-silver/)
  
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


## Resources

- https://mlagerberg.gitbooks.io/raspberry-pi/content/2.1-iptables.html
- https://raspberrytips.com/security-tips-raspberry-pi/
- https://www.instructables.com/Another-Raspberry-Pi-Cluster
- https://pimylifeup.com/cron-jobs-and-crontab/
- https://jamesachambers.com/best-ssd-storage-adapters-for-raspberry-pi-4-400/
- https://pimylifeup.com/raspberry-pi-vpn-server/
- https://dietpi.com/forum/t/changing-dietpi-user-in-scripts/4254
- https://gist.github.com/rdmarsh/5070295
- https://medium.com/codex/complete-self-hosted-bitwarden-for-raspberry-pi-24b59c3b02df
- https://adminscriptbank.wordpress.com/2016/09/16/debian-debian-jessie-fail2ban-implementation/
- https://dietpi.com/docs/dietpi_tools/
- https://hub.docker.com/r/pihole/pihole
- https://ikarus.sg/extend-sd-card-lifespan-with-log2ram
- https://github.com/containrrr/watchtower
- https://github.com/louislam/uptime-kuma
- https://github.com/peterblazejewicz/raspberry-pi-setup#space-cleanup
- https://github.com/tschaffter/raspberry-pi
- https://github.com/wtsxDev/Raspberry-Pi
- https://linuxfun.org/en/2021/01/01/what-log2ram-does-en/
- https://phoenixnap.com/kb/docker-on-raspberry-pi
- https://pimylifeup.com/raspberry-pi-volumio/
- https://www.cyberciti.biz/tips/how-to-linux-prevent-the-reuse-of-old-passwords.html
- https://www.eliaslundgaard.com/posts/mount-nas-to-pi/
- https://www.tomshardware.com/how-to/save-space-raspberry-pi-os
- https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-2
- http://kamilslab.com/2016/12/17/how-to-set-up-ssh-keys-on-the-raspberry-pi/
- https://pimylifeup.com/raspberry-pi-docker/
- https://raspberrypi.stackexchange.com/questions/79728/keep-hdmi-off-on-boot
- https://askubuntu.com/questions/1314479/ntp-not-supported
- https://blues.com/blog/tips-tricks-optimizing-raspberry-pi-power/
- https://www.reddit.com/r/raspberry_pi/comments/1eue4o/psa_if_your_pi_has_ssh_exposed_to_the_world/
- https://www.raspberrypi.com/documentation/computers/configuration.html
- https://kalitut.com/raspberry-pi-HDMI-port/
- https://gist.github.com/herrbischoff/bb6db0896400764aed6d
- https://thibmaek.com/posts/raspberry-pi-login-with-ssh-keys
- https://sites.google.com/site/cartwrightraspberrypiprojects/home/steps/remove-unused-stuff-from-raspbian
- https://web.archive.org/web/20130625182139/https://extremeshok.com/2012/07/22/raspberry-pi-raspbian-tuning-optimising-optimizing-for-reduced-memory-usage/
- http://jheyman.github.io/blog/pages/RaspberryPiTipsAndTricks/
- https://core-electronics.com.au/guides/raspberry-pi-workshop-for-beginners
- https://www.selfhostedlabs.com/raspberrypiproject/
- https://kalitut.com/secure-ssh-server-on-raspberry-pi/
- https://www.reddit.com/r/sysadmin/comments/fsf621/securing_a_raspberry_pi_on_the_network/
- https://www.reddit.com/r/selfhosted/comments/b3pwk3/securing_raspberry_pi/
- https://www.reddit.com/r/raspberry_pi/comments/54zssu/securing_your_pi_for_real_and_not_just_pretend/
- https://pimylifeup.com/raspberry-pi-wireguard/
- https://pimylifeup.com/raspberry-pi-ebook-server/
- https://www.jeffgeerling.com/blog/2020/fastest-usb-storage-options-raspberry-pi
- https://obutterbach.medium.com/unlock-the-full-potential-of-pihole-e795342e0e36
- https://pimylifeup.com/raspberry-pi-zram/
- https://www.blackmoreops.com/2021/10/25/vcgencmd-command-not-found/



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


