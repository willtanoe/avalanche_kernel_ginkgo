![Avalanche Android Kernel](docs/assets/banner.png)

# Avalanche Kernel

Avalanche is an Android kernel for the Qualcomm Trinket platform, focused on
the Xiaomi Redmi Note 8 and Redmi Note 8T (`ginkgo` and `willow`). It is based
on Linux 4.14 with the extended OpenELA stable updates.

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
