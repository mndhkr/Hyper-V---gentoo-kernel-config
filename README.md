# gentoo-sources-config-hyperv
.config file to compile gentoo-sources for Microsoft's Hyper-V\
Kernel version:  6.1.57-gentoo-x86_64

# Settings activated
Hyper-V's settings activated into kernel: (Y)

```
CONFIG_X86_HV_CALLBACK_VECTOR=y
CONFIG_UIO_HV_GENERIC=y

CONFIG_HYPERVISOR_GUEST=y
CONFIG_HYPERV_VSOCKETS=y
CONFIG_PCI_HYPERV=y
CONFIG_PCI_HYPERV_INTERFACE=y
CONFIG_SYS_HYPERVISOR=y
CONFIG_HYPERV_STORAGE=y
CONFIG_HYPERV_NET=y
CONFIG_HYPERV_KEYBOARD=y
CONFIG_DRM_HYPERV=y
CONFIG_FB_HYPERV=y
CONFIG_HID_HYPERV_MOUSE=y
CONFIG_HYPERV=y
CONFIG_HYPERV_TIMER=y
CONFIG_HYPERV_UTILS=y
CONFIG_HYPERV_BALLOON=y
CONFIG_HYPERV_IOMMU=y
```

# Filesystems support (Y)
Filesystems: MSDOS, VFAT, NTFS (rw), exFAT, ISO 9660, UDF, ext4, btrfs

# Reference
[Hyper-V - Gentoo Wiki](https://wiki.gentoo.org/wiki/Hyper-V)
