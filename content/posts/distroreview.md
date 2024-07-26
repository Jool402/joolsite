---
title: "Distro Review and Usage"
date: 2024-01-27T11:06:04-05:00
draft: false
---
I have tried various distros on three of my computers. Many popular distros have a reputation for being robust for a Linux user. Then, there are less used Linux distros that created a new and smart concept. In contrast, some Linux distros did not work on my computers for some reason.

I am using a Dell Inspiron with a 360°-flippable touchscreen. I attach an external hard drive to the USB port of my laptop. so I can dual-boot. The USB 3.0 and hard drive combination is not the fastest combination as they are both slower than SATA and NVMe. Nevertheless, a Linux distro boots fine with them.

My desktop is a pre-built PC. It has an NVMe drive that has Windows 11 installed. Additionally, it has a SATA hard drive where I installed Arch Linux.

I have couple of my Raspberry Pis: the first one is running Raspberry Pi OS (Raspberry Pi 5), and the other one is running Lineage OS 20. I may change the operating systems in the future. They are both running on SD cards. I also have the 3rd most powerful Pi in the market.

## Ubuntu
I tried Ubuntu GNOME on my Raspberry Pi 4. The operating system does not perform seamlessly; at least, it performs well for a computer with a slow reputation. I went further on to install Xubuntu on the device, and it worked snappier because the XFCE desktop is faster than the GNOME desktop environment. Later, I installed the default Raspberry Pi OS onto my Raspberry Pis. I have two of the most performant Raspberry Pis. I got the Raspberry Pi 5 two days ago to test some distros. Now that I have them, I can test ARM64/AARCH64 Linux distros on my latest Pi (also known to me as a PIve).

## Debian
Debian was one of the first distros I have ever run on a computer. I started running Debian preloaded on a BeagleBone® Black. I also then installed Debian. It is stable; however, it does not like upgrading from a stable release to sid on a GUI terminal. If a user fully updates Debian by typing the commands on the tty, the distro should be ready to upgrade.

## Linux Mint
Linux Mint was the first distro that I installed on my external hard drive. I did not extensively try Linux Mint, but I did temporarily install Linux Mint on my hard drive for a short time. I used the external hard drive to attach it to one of the two USB ports on my laptop. (I did not want to wipe my Windows on my system as I still need it for some applications.)

## Fedora
After I tried Linux Mint out, it was time to run Fedora. Fedora worked great on my system. Lately, I have been having issues with this distro. One of the issues of Fedora on my external hard drive is that it keeps crashing. The crash occurred even after I upgraded the distro to its latest release even after installation. It could be because the hard drive sometimes invisibly disconnects from my computer. It could also be Fedora acting up on my device. I am still running Fedora on the external drive attached despite problems.

## OpenSUSE
I tried to install OpenSUSE on the hard drive as I wanted to try something else. Unfortunately, I could not even install this distro on my hard drive. The installer does not list the second drive on my virtual machine. It seemed like an elegant distro to try. It has the unique YaST administration tool for OpenSUSE.

## Arch Linux
Arch Linux has been running on my desktop since I put it on the SATA hard drive secondary storage device. I have never tried Arch on my new laptop, but I did try Arch on one of my netbooks. I even installed Arch on a Beagleboard: the first computer I have ever had that runs Linux.

## Conclusion
I have settled with Fedora on my external drive, but I am still contemplating whether I keep using Fedora or use a different distro. I can't be sure if the issue I described earlier was a problem from the external HDD or a Fedora problem. I still have Windows 11 on the internal SSD of my laptop. The same thing applies to my desktop.

I am sticking with Arch Linux for my desktop. Arch Linux has a reputation for breaking after updating because Arch Linux is a rolling release distro. However, it has been working well, so I am not thinking of overwriting Windows with Arch Linux because I need Windows-exclusive software to run.

The Raspberry Pi 5 is running the official operating system. The stability and function of this operating system is an effect of Debian. On the other hand, the Raspberry Pi 4 is running LineageOS 20. Both of them work well in common.

I occasionally encounter problems, but a lot of these problems are solvable (except for that Fedora bug that I wrote in the section covering Fedora).
