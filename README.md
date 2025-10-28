# ECE 391 Flake

A Nix flake for UIUC's ECE 391 (Computer Systems Engineering) class.

Heavily inspired by [riscv-qemu-toolchain](https://github.com/RoshanAH/riscv-qemu-toolchain), with some notable deviations:
- Software versions are matched with course-provided tooling
  - `binutils` - 2.42
  - `gcc` - 13.2.0
  - `glibc` - 2.34
  - `gdb` - 14.1
- `clangd` works, and properly uses the custom RISC-V stdlib
