---
title: "VMware on Linux"
date: 2024-10-07
draft: false
description: "Install VMWare on Linux"
tags: ["VMWare", "Virtualization", "Tools", "Linux"]
---
### Intro

I understand that many of you newcomers to **Linux** from **Windows** soemtimes prefer to use **VMWare** coz that's what you are used to. Although I would highly recommend **Virt-Manager** as it's Kernel based. But for you who prefer VMWare follow the guide below..

<p align="center">
    <img src="https://i.imgur.com/FDUoyg6.png" alt="shot">
</p>

### The Guide

All packages compile from the **AUR**, but if you are on **XeroLinux** or have the **Chaotic-AUR** repos they will simply just install, no compilation needed.

- Grab the packages

```Bash
paru/yay -S vmware-workstation vmware-unlocker-bin vmware-keymaps
```

- Activate Networking & other services :

```Bash
sudo modprobe -a vmw_vmci vmmon
sudo systemctl enable --now vmware-networks.service
sudo systemctl enable --now vmware-usbarbitrator.service
```

Finally there's the matter of the Linux Guest OS, to set the correct resolution, it has to come with certain packages but in any case I will show you how to install them and enable..

To enable the service just run :

```Bash
sudo systemctl enable --now vmtoolsd
```

### Issues

If resolution does not get fixed and you are stuck at low, then you might need to install the necessary packages... Below is what you need for the various Distros out there... Reboot then run the above command...

- Video Drivers

```Bash
sudo pacman -S xf86-video-vmware open-vm-tools
```

Yet another tool to add to the arsenal...
