# ===================================================
#                                                   #
#      Build and Run Toolchain for EPOS RISC-V      #
#                                                   #
#  Author: Enzo Coelho Albornoz                     #
#  License: GPLv3                                   #
# ===================================================

# Import Alpine
FROM alpine:3
# Install Debug Tools (GDB, GDB-Multiarch)
RUN apk add --no-cache gdb-multiarch
# Install Emulation Tools (QEMU RISC-V )
RUN apk add --no-cache qemu-system-riscv64
# Install Building Tools (GCC, G++, Make, Ack)
RUN apk add --no-cache ack findutils make g++ gcc-riscv-none-elf