![Avalanche Android Kernel](docs/assets/banner.png)

# Avalanche Kernel

Avalanche is a custom Android kernel for the Xiaomi Redmi Note 8 and Redmi
Note 8T (`ginkgo` and `willow`), built on the OpenELA-maintained Linux 4.14.357
kernel and using the
[FlopKernel-Series trinket kernel](https://github.com/FlopKernel-Series/flop_trinket-mi_kernel)
as its device-specific baseline. Avalanche is developed and maintained
independently, with credit to FlopKernel-Series, Flopster101, and previous
contributors for the inherited Qualcomm Trinket and ginkgo/willow support.

## Highlights

- KernelSU Next with SUSFS support
- Optional ReSukiSU and XXKSU variants
- Vanilla builds without integrated root access
- Clang and LLVM support with ThinLTO
- AnyKernel3-compatible flashable packages

## Supported Devices

- Xiaomi Redmi Note 8 (`ginkgo`)
- Xiaomi Redmi Note 8T (`willow`)

## Credits

Avalanche Kernel is based on
[FlopKernel-Series/flop_trinket-mi_kernel](https://github.com/FlopKernel-Series/flop_trinket-mi_kernel).
Full credit goes to FlopKernel-Series, Flopster101, and every FloppyKernel
contributor for the original kernel tree and device work.

Additional credit belongs to the Linux kernel community, OpenELA, Qualcomm,
Xiaomi, KernelSU Next, SUSFS, ReSukiSU, XXKSU, and AnyKernel3 contributors.

## License

This project is distributed under the GNU General Public License v2. See
[`COPYING`](COPYING) for the complete license text.
