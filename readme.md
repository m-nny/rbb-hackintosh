> Based on Laptop Vanilla [guide](https://dortania.github.io/vanilla-laptop-guide/preparations/opencore-efi.html)

## Hardware
> TODO    

## Used files

> full list in `packages.list`

## Changelog

0. Added OpenCore
1. Remove pre-installed drives + tools.
   > Note: `AudioDxe.efi` and `CrScreenshotDxe.efi` are not in guide, so i deleted them.
2. Added `kext` and some `efi`. Full list in `packages.list`
3. ACPI
   - extraced DSDT with `SSDTTime`
   - Found device path from installed Windows 10 Device Manager
   -

### Found device paths

| Device                                       | Bios Path             |
| -------------------------------------------- | --------------------- |
| Intel(R) UHD Graphics 630                    | `\_SB.PCI0.GFX0`      |
| NVIDIA GeForce GTX 1060 with Max-Q Design    | `\_SB.PCI0.PEG0.PEGP` |
| Microsoft ACPI-Compliant Embedded Controller | `\_SB.PCI0.LPCB.EC0`  |
| Intel Processor                              | `\_SB.PR00`           |

￼
