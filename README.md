# Avalanche Kernel

Avalanche is an Android kernel for the Xiaomi Redmi Note 8 and Redmi Note 8T
(`ginkgo` and `willow`), based on Linux 4.14 for the Qualcomm Trinket platform.

## Features

- KernelSU Next with SUSFS support
- Optional ReSukiSU and XXKSU variants
- Vanilla builds without an integrated root solution
- AnyKernel3 flashable packages
- Clang and LLVM build support

## Building

Run the build from the root of the kernel tree. The build script can download
its default toolchain, or it can use an existing Clang toolchain through
`CLANG_TYPE=custom` and `CUST_DIR`.

```bash
# Vanilla
bash do_build.sh ginkgo c

# KernelSU Next
bash do_build.sh ginkgo kc

# Existing Clang toolchain
CLANG_TYPE=custom CUST_DIR=/path/to/clang bash do_build.sh ginkgo kc
```

On Ubuntu, automatic dependency installation can be explicitly enabled with
`INSTALL_DEPS=1`. Uploads are disabled unless an upload option is passed.
DroidSpaces container support is opt-in through `DROIDSPACES=1`.

Build artifacts are written to the parent workspace as
`Avalanche_<version>-<variant>-ginkgo-<timestamp>.zip`.

## Credits

Avalanche builds on the work of the Linux kernel community, Qualcomm, Xiaomi,
the FloppyKernel contributors, KernelSU Next, SUSFS, and AnyKernel3.

## License

This project is distributed under the GNU General Public License v2. See
`COPYING` for the complete license text.
