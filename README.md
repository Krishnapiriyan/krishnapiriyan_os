# krishnapiriyan_os
A simple real-mode OS in assembly displaying a welcome message.



---

Overview

This is my first attempt to build an operating system from scratch to understand how low-level software works, including:

- BIOS interrupt handling
- Boot sector structure
- x86 Assembly basics

---
Tools Used

- **Ubuntu 24.04 via WSL**
- **NASM** (Netwide Assembler)
- **QEMU** (Quick Emulator)

---
📂 Folder Structure
krishnapiriyan-os/
├── bootloader.asm # Source code (Assembly)
├── bootloader.bin # Compiled bootable binary


---

How to Run

1. Install Dependencies
sudo apt update
sudo apt install nasm qemu

3. Clone the Repository
git clone https://github.com/yourusername/krishnapiriyan-os.git
cd krishnapiriyan-os

4. Assemble the Bootloader
nasm -f bin bootloader.asm -o bootloader.bin

5. Run It in QEMU
qemu-system-x86_64 -drive format=raw,file=bootloader.bin
hello, welcome krishnapiriyan os




