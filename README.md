# bios-settings-for-linux
Notes on bios settings for installing linux. 

## Pre-installation BIOS settings
- On splash screen press F1, boot into BIOS
- Config -> Storage -> Controller mode -> AHCI
- Security -> Secure boot -> OFF
- Config -> Display -> Graphic device -> Hybrid 

## Insert Linux boot USB 
- On splash screen press F12, boot into 'Boot menu list'
- From GRUB menu, choose e.g. install Ubuntu

--- 
## Extra
### For system with nvidia graphic card
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
