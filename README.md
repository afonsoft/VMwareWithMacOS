# How to Install macOS on VMware in Windows PC

Note:- Please Enable VT-X or AMD-V Virtualization technology from your BIOS Settings.

### Steps to Install macOS Big Sur on VMware on Windows
1. Download the prerequisites
2. Install the Prerequisites
3. Unlock VMware to Install macOS Big Sur
4. Create a New Virtual Machine
5. Edit macOS Big Sur VMX File
6. Start macOS Big Sur Virtual Machine
7. Complete Basic macOS Account Settings

#### Download VMware Workstation Pro 16 or VMware Player 16.
- [VMware Workstation 16 Pro](https://www.vmware.com/au/products/workstation-pro/workstation-pro-evaluation.html)
- [VMware Player 16](https://www.vmware.com/au/products/workstation-player/workstation-player-evaluation.html)

#### Download the macOS Unlocker V3 for VMware
- [Download – GitHub (latest Version)](https://github.com/paolo-projects/unlocker)
- Download from this repository

#### Create or Download macOS Big Sur Beta ISO
 -[macOS Big Sur Beta ISO](https://www.wikigain.com/install-macos-big-sur-on-vmware-windows-pc/)

## tutorials
- https://buildsometech.medium.com/how-to-install-macos-on-vmware-in-windows-pc-mojave-a79329e057db
- https://www.wikigain.com/install-macos-big-sur-on-vmware-windows-pc/

#### Add Config Key in VMX Fil
Note:- Please make sure, before doing this advanced configuration the Vmware workstation must be closed. Or I recommend you to please restart your PC before Adding Config Key in VMX File.
Now Open the folder where you have set up your virtual machine. And in that folder, you will find a white color file of the extension .vmx . Now Open that VMware virtual machine configuration file using Notepad.

```
mainMem.useNamedFile = "FALSE"
prefvmx.minVmMemPct = "100"
vhv.allow = "TRUE" 
smbios.reflectHost = "TRUE"
hw.model = "MacBookPro14,3"
smc.version = "0"
monitor.virtual_exec = hardware
monitor.virtual_mmu = hardware
```

Edit VMware config file
 C:\ProgramData\VMware\VMware Workstation\config.ini
 ```
 mks.gl.allowBlacklistedDrivers = "TRUE"
vhv.allow = "TRUE"
prefvmx.useRecommendedLockedMemorySize = "FALSE"
prefvmx.allVMMemoryLimit = "4096"
 ```
 ##### For steps four, five, six and seven.
 - [Link 1](https://www.wikigain.com/install-macos-big-sur-on-vmware-windows-pc/)
 - [Link 2](https://medium.com/@buildsometech/how-to-install-macos-on-vmware-in-windows-pc-mojave-a79329e057db)
 
 
 
