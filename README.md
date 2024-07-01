---

<div align="center">
  <h3>🧑‍💻 Monterey Hackintosh</h3>
  <p>Hackintosh EFI made for running a i5-9600K on macOS Monterey 12.3.</p>
</div>

---

## Specification
- i5 9600K 
- 16GB of DDR4 at 2666MHz
- Realtek Gaming GbE Family Controller
- NVIDIA GeForce GTX 1060 6GB (Disabled, iGPU is used since NVIDIA cards aren't compatible)
- Gigabyte H310M S2H
- OpenCore 0.7.9

## Functional Features
- Audio (Headphones & Monitor)
- Ethernet Adapter
- iGPU
- dGPU disabling
- Motherbord BusID patching for the iGPU
- Framebuffer patching for the iGPU

## Non-Functional Features
- PCIe WiFi adapter
- Possibly other stuff, I can't recall.
