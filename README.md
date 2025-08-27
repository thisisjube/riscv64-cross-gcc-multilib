# RISC-V GNU Toolchain (Prebuilt, Multilib)

This repository provides **prebuilt binaries** of the [RISC-V GNU Toolchain](https://github.com/riscv-collab/riscv-gnu-toolchain) for **Linux (glibc-based systems)**.

The toolchain has been built with the `--enable-multilib` option, allowing you to target multiple RISC-V variants (such as `rv32` and `rv64`) from a single installation.

For more details on multilib builds, see the official [installation guide](https://github.com/riscv-collab/riscv-gnu-toolchain?tab=readme-ov-file#installation-newliblinux-multilib).

---

## Installation

Download and extract the latest release:

```bash
wget https://github.com/thisisjube/riscv64-cross-gcc-multilib/releases/download/riscv-gnu-toolchain-multilib-4f2083a/riscv-toolchain-multilib.tar.gz
tar -xvf riscv64-toolchain.tar.xz -C /opt/
export PATH=/opt/riscv/bin:$PATH
