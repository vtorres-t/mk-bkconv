# Downloaded file name meaning

All binaries produced by this repository follow this format:

mk-bkconv_<operating-system>_<cpu-architecture>

Example:

mk-bkconv_windows_amd64.exe

This means:
- operating system = Windows
- CPU architecture = 64-bit x86

Below is the meaning of each operating system and architecture suffix.

---

## Operating system part

windows  → Microsoft Windows  
linux    → GNU/Linux  
darwin   → macOS  
freebsd  → FreeBSD  
openbsd  → OpenBSD  
netbsd   → NetBSD  

Note:
For macOS, the operating system name used by Go is "darwin".

---

## CPU architecture part

amd64   → 64-bit Intel / AMD processors (x86-64)
386     → 32-bit Intel / AMD processors (x86)
arm64   → 64-bit ARM processors (for example Apple Silicon, many phones, SBCs)
arm     → 32-bit ARM processors (older ARM boards and devices)
ppc64le → 64-bit IBM POWER (little-endian)
s390x   → IBM Z mainframe systems
riscv64 → 64-bit RISC-V processors

---

## Common examples

mk-bkconv_windows_amd64.exe  
→ Windows on a normal modern 64-bit PC.

mk-bkconv_darwin_arm64  
→ macOS on Apple Silicon (M1, M2, M3, etc.).

mk-bkconv_darwin_amd64  
→ macOS on older Intel Macs.

mk-bkconv_linux_amd64  
→ Linux on a normal 64-bit PC or server.

mk-bkconv_linux_arm64  
→ Linux on 64-bit ARM devices (for example Raspberry Pi 4/5 running 64-bit OS).

---

## Which file should I download?

Most users only need one of these:

Windows PC:
→ mk-bkconv_windows_amd64.exe

Modern Mac (Apple Silicon):
→ mk-bkconv_darwin_arm64

Older Intel Mac:
→ mk-bkconv_darwin_amd64

Most Linux PCs:
→ mk-bkconv_linux_amd64