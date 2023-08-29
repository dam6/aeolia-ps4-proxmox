# aeolia-ps4-proxmox
## Run Proxmox on Aeolia jailbroken PS4

# Prerequisites
1. A jailbroken PS4 (tested on firmware 9.00)
2. A external hard drive (SSD recommended for VMs, HDD will work fine with containers)

# About releases
This releases aims to easily run Proxmox on your Aeolia jailbroken PS4 with the given files (without compile the kernel by your own)

# Setup (releases)
1. Download all files from the releases section of this repo.
2. Download Proxmox from the [Download](https://ps4linux.com/proxmox-ve-ps4-beta-virtualisation/) section of ps4linux.com website.
3. Create a PS4-bootable external hard drive. I highly recommend follow along this [method](https://ps4linux.com/run-ps4-linux-without-installing/).
4. Once you got the both partitions on the external hard drive (50MB with bzImage & initramfs.cpio.gz and the Proxmox one), unzip the given `5.15.15-02378-g999e4d75141f-dirty.zip` from the release section on the following Proxmox path: `/lib/modules/`.
5. Jailbreak the PS4 as you usually do and load the Linux payload. Proxmox will boot automatically.
6. Setup the network on Proxmox, this can be done following along this [video](https://www.youtube.com/watch?time_continue=663&v=82dbk2yCcQc).

# Compile the kernel
If you want to compile the kernel by yourself, you can download it from [here](https://github.com/codedwrench/ps4-linux/) and copy the config file of this repo.
If you are not experienced doing this (me neither :P), you can read [this](https://ps4linux.com/compile-ps4-linux-kernel-tutorial/) guide.

# Recommended sources
- PS4 Linux (noob404) [website](https://ps4linux.com)
- Modded Warfare [Youtube](https://www.youtube.com/watch?v=yVFbo23BCK4&list=PLn7ji3VsPy3Gryq_sCOMp6H87jXywCMPI)
