# bios-settings-for-linux
Notes on bios settings for installing linux. 

## Pre-installation BIOS settings
- Boot into BIOS by pressing F1 on splash screen
- Config -> Storage -> Controller mode -> AHCI
- Security -> Secure boot -> OFF
- Config -> Display -> Graphic device -> Hybrid

## Insert Linux boot USB 
- Boot into Boot menu list by pressing F12 on splash screen
- Choose e.g. install Ubuntu, from GRUB menu

--- 
<table><tr><td>
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
</td></tr></table>

ENDS
