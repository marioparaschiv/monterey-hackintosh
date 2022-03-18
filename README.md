# Hackintosh
The EFI required for my Monterey 12.3 Hackintosh.

### System Specification
- i5 9600K 
- 16GB of DDR4 at 2666MHz
- Realtek Gaming GbE Family Controller
- NVIDIA GeForce GTX 1060 6GB (Disabled, iGPU is used since NVIDIA cards aren't compatible)
- OpenCore 0.7.9

### What works
- Audio (Headphones & Monitor)
- Ethernet Adapter
- iGPU
- dGPU disabling
- iGPU BusID patching

### What doesn't work
- PCIe WiFi adapter
- Possibly other stuff, I can't recall.
