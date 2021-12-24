# bios-settings-for-linux
Notes on bios settings for linux 

Example: Lenovo Thinkbook G3

## Pre-installation BIOS set up
- Boot into BIOS by pressing F1 at splash screen
- Config -> Storage -> Controller mode -> AHCI
- Security -> Secure boot -> OFF
- Config -> Display -> Graphic device -> Hybrid

## Insert Linux boot USB 
- Boot into Boot menu list by pressing F12 at splash screen
- Choose e.g. install Ubuntu, from GRUB menu

----- 
## For system with nvidia graphic card
- Select 'Install third-party software'
- At Terminal, run
```
ubuntu-drivers devices
sudo ubuntu-drivers autoinstall
sudo reboot
```

- Verify driver is loaded
```
nvidia-smi
```


ENDS
