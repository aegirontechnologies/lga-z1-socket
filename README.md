![Open Hardware Project](https://img.shields.io/badge/Open-Hardware-blue)


## 🚨 Help Wanted – AEGIS Dev Kit + LGA-Z1 Socket

We’re seeking collaborators to support our open hardware CPU and motherboard platform.

**Open Needs:**
- CPU socket layout and verification (LGA-Z1)
- DDR5/PCIe board validation (KiCad or equivalent)
- Firmware developers (U-Boot, coreboot for ARMv9)
- Documentation formatting + open licensing reviews

📫 Contact: aegirontechnologies@gmail.com

---

### 🛠 GitHub Issue 1: CPU Socket Layout & Verification (LGA-Z1)

**Summary:**  
We’re seeking support on the electrical and mechanical validation of the LGA-Z1 CPU socket, targeting 1,100–2,200 pins depending on CPU tier.

**Tasks:**
- Review early LGA-Z1 socket layout (pad pitch, footprint size)
- Validate against DDR5, PCIe Gen4 signal integrity requirements
- Create preliminary KiCad or DXF footprint if possible

**Ideal Contributor:**  
Hardware/mechanical engineer or layout designer with experience in custom socket, BGA/LGA, or CPU board design.

---

### 💾 GitHub Issue 2: DDR5 + PCIe Gen4 Layout Design Review

**Summary:**  
We’re looking for contributors with experience in DDR5 memory layout and PCIe Gen4 signal integrity to validate and co-design portions of the AEGIS Libre Dev Kit motherboard.

**Tasks:**
- Review or help route DDR5 dual-channel memory
- Validate PCIe Gen4 x16 lane design and power integrity
- Suggest best practices or link to open layout examples

**Ideal Contributor:**  
Experienced PCB layout engineer familiar with high-speed signals, DDR5 layout rules, or PCIe Gen4 board-level design.

---

### 🧬 GitHub Issue 3: Platform Firmware Support (coreboot/U-Boot for ARMv9)

**Summary:**  
We're seeking firmware developers to help bring up bootloader and platform firmware support for the AEGIS CPU family (ARMv9-based).

**Tasks:**
- Port or configure U-Boot and/or coreboot for AEGIS Libre (12-core)
- Develop early-stage bring-up scripts and debug output
- Create a reproducible build environment for firmware

**Ideal Contributor:**  
Low-level firmware developer or embedded Linux hacker familiar with ARM SoC bring-up, U-Boot, or coreboot internals.
