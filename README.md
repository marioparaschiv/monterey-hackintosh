# Hackintosh
The EFI required for my Monterey 12.3 Hackintosh.

### System Specification
- i5 9600K 
- 16GB of DDR4 at 2666MHz
- Realtek Gaming GbE Family Controller
- NVIDIA GeForce GTX 1060 6GB (Disabled, iGPU is used since NVIDIA cards aren't compatible)
- Gigabyte H310M S2H
- OpenCore 0.7.9

### What works
- Audio (Headphones & Monitor)
- Ethernet Adapter
- iGPU
- dGPU disabling
- Motherbord BusID patching for the iGPU
- Framebuffer patching for the iGPU

### What doesn't work
- PCIe WiFi adapter
- Possibly other stuff, I can't recall.
