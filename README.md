# Hackintosh

This is an [opencore](https://dortania.github.io/OpenCore-Install-Guide/) EFI config to build macOS Monterey 12.3.1 width Gigabyte Z370-HD3 series motherboards and Intel 8th series cpus.

Useage:

1. Build a Monterey installer with a usb.  The recomand methods: on [macos](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html), on [windows](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html), on [linux](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html).
2. Download the EFI config.
3. Mount you usb installer efi partition and put all the EFI folder into the top of the efi partition. Pay attention, there must be only one folder named "EFI" in the top of the efi partition .
4. Take off the usb installer and insert to your computer waited to be booted. Then come into the bios settings and set the main booter as the usb installer.
5. Bios settings
   * Enable fast boot
   * Enable secure boot
   * Enable serial port
   * Disable vt-d
   * Disable csm
   * Enable Above 4G decoding
   * Enable Hyper-Threading
   * Enable EHCI/XHCI Hand-off
   * OS type: Windows 8/10
   * DVMT Pre-Allocated(iGPU Memory): 128MB
   * SATA Mode: AHCI
   * Initial display output: IGFX
   * Enable platform power management
6. Restart your computer. when the opencore boot gui react displays, first you should unlock the cfglock with the [CFGlock.efi](https://www.tonymacx86.com/threads/guide-unlocking-cfg-with-opencore-and-cfglock-efi.305163/)  (has been puted into EFI->OC->Tools folder, just use), then select the install option to start a install. Just wait and see a miracle!!!

# My device Informations

Here are my main device infos.

- MacOS Monterey 12.3.1
- Intel i7-8700
- Intel UHD 630
- Gigabyte Z370-HD3
- 2 X 16 GB DDR4 @ 3600 Mhz
- m.2 ssd
- AMD rx6600xt 8gb(not official)
- BCM943602CS adapter card for wifi and bluetooth.
- Dell p2418d 1440p monitor

MacOS Monterey12.3.1 installed to my computer about one and a half month sine 2022.3.29 and everything works well, including the most attentive points:

* auto/manual sleep and wake up
* Cpu auto turbo.
* Ethernet
* wifi and bluetooth and airdrop
* uhd630 graph and sounds.
* AMD rx6600xt card
* Apple ID and icloud
* Mouse(usb) and keyboard(usb)

# Cautions

Making a Hacintosh is illegal，this is just for intersting, not for commercial using. I have been used MacBook Pro for above 7 years. A Macintosh computer is mostly sutiable for our works as for it is stable enough and legal.

Contacting me if you have some problems.
