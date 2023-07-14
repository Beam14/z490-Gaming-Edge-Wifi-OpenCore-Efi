# z490-Gaming-Edge-Wifi-OpenCore-Efi

Specs - 

- MSI z490 Gaming Edge Wifi (Latest Bios)
- I7 10700k
- 32GB Ram
- Intel AX210 Wifi Card
- Samsung 970 Evo
- RTX 3060 (Disabled)
  






Whats Working

- Intel AX210 Wifi + Bluetooth Ventura
- Dolby Atmos + Lossless (No dGPU Required)
- All USB
- Motherboard DisplayPort Port
- Sleep/Wake
- Accelerated Graphics
- 2.5Gbit Lan


What Not Working

- Full DRM Support (Requires AMD GPU) Also Install Chrome or Alternative that uses Chromium
- Handoff


Notes

Make own SMBios (iMacPro1,1) using GenSMBIOS
Make sure CFG Lock and Secure Boot is disabled in bios before trying to boot (CFG Lock is in Advanced - OC - CPU Features)
There might be more settings you'll need to change in bios but this is all i needed for me to boot but read OpenCore Bios Settings for Comet Lake to get the best understanding of what you will need to do (This is not a guide this is just for being able to boot and having a functional macOS install/boot.
