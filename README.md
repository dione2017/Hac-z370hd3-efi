# Hackintosh

This is an [opencore](https://dortania.github.io/OpenCore-Install-Guide/) EFI to build macOS Monterey 12.3.1 width Gigabyte Z370-HD3 series motherboards and Intel 8th series cpus.

Useage:

1. Build a Monterey installer with a usb.  The recomand methods: on [macos](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html), on [windows](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html), on [linux](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html).
2. Download the EFI Folder.
3. Mount you usb installer efi partition and put all the EFI folder into the top of the efi partition. Pay attention, there must be only one folder named "EFI" in the top of the efi partition .
4. Take off the usb installer and insert to your other computer. Then come into the bios settings and set the main booter as the usb.
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

Disable your

# My device Informations

Here are my main device infos.

- MacOS Monterey 12.3.1
- Intel i7-8700
- Intel UHD 630
- Gigabyte Z370-HD3
- 1 X 16 GB DDR4 @ 3200 Mhz
- m.2 ssd
- BCM943602CS for wifi and bluetooth.
- Dell p2418d 1440p monitor

I have made the Hackintosh running macOS Monterey12.3.1 for about one month and everything looks great. Including the most attentive points:

* auto/manual sleep and wake up
* Cpu auto turbo.
* Ethernet
* wifi and bluetooth and airdrop
* uhd630 graph and sounds.
* Apple ID and icloud
* Mouse(usb) and keyboard(usb)

# Cautions

Making a Hacintosh is illegal，this is just for intersting, not for commercial using. I have been used MacBook Pro for above 7 years. A Macintosh computer is mostly sutiable for our works as for it is stable enough and legal.

My English is very poor, really not being unconfident...

Please, If  you find the mistakes of my words or grammers, Tell me. 

If you have some problems, you could contact me, too.



