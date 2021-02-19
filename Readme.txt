https://medium.com/@buildsometech/how-to-install-macos-on-vmware-in-windows-pc-mojave-a79329e057db


https://www.wikigain.com/install-macos-big-sur-on-vmware-windows-pc/

Driver de Video
https://sourceforge.net/projects/vmsvga2/
https://www.insanelymac.com/forum/topic/302424-yosemite-on-vmware-unusable/

Edit VMX File for xCode
mainMem.useNamedFile = "FALSE"
prefvmx.minVmMemPct = "100"
vhv.allow = "TRUE" 

Edit macOS Big Sur VMX File


smbios.reflectHost = "TRUE"
hw.model = "MacBookPro14,3"
smc.version = "0"
monitor.virtual_exec = hardware
monitor.virtual_mmu = hardware


C:\ProgramData\VMware\VMware Workstation\config.ini

mks.gl.allowBlacklistedDrivers = "TRUE"
vhv.allow = "TRUE"
prefvmx.useRecommendedLockedMemorySize = "FALSE"
prefvmx.allVMMemoryLimit = "4096"