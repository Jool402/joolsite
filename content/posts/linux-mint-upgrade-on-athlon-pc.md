---
title: "Linux Mint Upgrade on Athlon Pc"
date: 2024-06-30T19:42:35-04:00
draft: false
---

I mentioned one of my PCs running Linux with an Athlon 64 CPU in previous articles. HP built one of them, so it goes through years ever since Windows XP came out.

It went through a distrohopping phase from Arch Linux to Linux Mint. I put Arch Linux, Debian, Linux Mint, NixOS, etc. Not everything went successfully. The failed distros were Gentoo and KISS Linux.

Many Linux distros worked out of the box, but I eventually switched back to the first three distros mentioned in the list. While Gentoo installed successfully on this PC, the compile time was abysmal because my Athlon 64 computer has aged for almost two decades now. The program that took the longest to program on my PC was LLVM. I even suspected that Gentoo froze during LLVM's compilation. For KISS Linux, I just gave up installing it as it took too long to install.

Eventually, I settled on Linux Mint. I specifically chose Linux Mint XFCE because the XFCE edition of Linux Mint is the lightest version found on Linux Mint's website. Linux Mint uploaded a couple of other editions: Cinnamon Edition, XFCE Edition, and MATE edition. [Linux Mint citation] MATE is decent for older computers, but XFCE takes up less resources. Cinnamon is the heaviest of the three because it is based on the fork of GNOME 3.

I installed Linux Mint via the first part of the OEM install. The OEM install sets up the hard drive and installs the distro onto it. Furthermore, I set up the computer using the second part of the installation. The second part sets up Linux Mint after the distro installed onto the disk. Both parts of OEM installation went successfully.

However, I left my Athlon 64 PC sitting there for so many days; thus, my PC has not been used ever since. The reason why I stopped using this PC is because I got a newer and faster one.

Fast forward to late June 2024, I booted up my Athlon 64 PC, and the desktop looked clean and devoid of personal files. However, the operating system was very out of date. (The last upgrade was probably a year or two out of date.) It was because the PC was left out for so long.

As a solution, I upgraded the Linux Mint by typing `sudo apt update` and `sudo apt upgrade` on the TTY. The upgrade took around thirty minutes. Once the Linux Mint upgrade finished, the desktop environment looked clean and updated.

The only real problem was the noise from my Athlon 64 PC. The PC was loud compared to my other PCs. Suddenly, I found the unseemly unrelated solution; I switched the graphics driver from the unofficial nouveau driver to an official NVIDIA driver---It quieted down my PC.

Although the default Linux Mint XFCE desktop looked sleek, I changed the desktop and icon theme to [THEME] dark blue as blue is my favorite color.

With my old PC up to date, who knows what I will do with this computer in the coming days? I am brainstorming the use for my Athlon 64 PC. I have many other computers to play with. Eventually, I will be too busy to use the Athlon 64 PC.
