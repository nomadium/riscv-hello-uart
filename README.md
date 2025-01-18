# riscv-hello-uart
Minimal bare-metal RISC-V assembly code with UART output for execution in QEMU

For a more realistic but still minimal example, take a look at: https://github.com/nomadium/riscv-real-world-hello-uart

## Requirements
### Tools:
- riscv64-unknown-elf-gcc
- riscv64-unknown-elf-ld
- riscv64-unknown-elf-objcopy

### Building:
make

### Execution:
qemu-system-riscv64

## Building
make all

## Running
make run
