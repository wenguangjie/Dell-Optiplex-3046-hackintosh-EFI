# Dell-Optiplex-3046-hackintosh-EFI

Dell Optiplex 3046 hardware configration:
CPU: Skylake-S Core I5 - 6500

GPU: Intel(R) HD Graphics 530

RAM: 8 GB DDR4

Audio card: Realtek ALC255 @ Intel Sunrise Point PCH

Ethernet: Realtek RTL8168/8111

Installation instruction:
Bios setting:

 Resert to default
 setting -> general -> Boot Sequence -> Boot List Option -> UEFI
 setting -> general -> Advanced Boot Options -> UNCHECK Enable legacy Option ROMS
 setting -> video -> promary display -> Intel HD Graphics
 setting -> secure boot -> secure boot enalbe -> disabled
 Setting -> virtualization support -> vt for Direct I/O -> UNCHECK Enable VT for Direct I/O
CFG Unlock:
 Tool: cfglock.efi (Included in the EFI)
 setup_var 0xAF 0x0

