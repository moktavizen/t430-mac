# T430 Mac - OpenCore EFI

Download: https://github.com/moktavizen/t430-mac/releases

> [!WARNING]  
> Generate your SMBIOS data using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) before using this EFI!
> 
> See https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html#platforminfo

**Specs:**

```bash
Model: ThinkPad T430  
MacOS: Big Sur  
SMBIOS: MacBookPro11,2  
CPU: i7-3632QM Ivy Bridge  
GPU: Intel HD 4000  
RAM: 16GB  
Storage: 256GB SSD + 320GB HDD  
Ethernet: 82579LM  
WiFI: Intel 6205  
Bluetooth: BCM20702  
Audio: ALC3202
```

**What's Working:**

```bash
iGPU  
Display + Night Shift  
Ethernet  
WiFi  
Bluetooth  
USB  
Input (keyboard, trackpad)
Audio
```

**What's Not:**

```bash
Pop up "The disk you attached was not readable by this computer" after every start/boot
```
