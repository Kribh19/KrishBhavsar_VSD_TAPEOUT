# KrishBhavsar_VSD_TAPEOUT

## VSD SoC Design Program - Day 0: Development Environment Setup

This repository documents **Day 0** of the **VSD SoC Design and Physical Design Program** by VLSI System Design (VSD). The focus is on establishing a complete development environment for RTL-to-GDSII ASIC flows using open-source EDA tools.

---

## Overview

Day 0 covers the foundational setup required to run open-source ASIC design tools in a virtualized Linux environment. This includes:

- Setting up a hypervisor and Linux virtual machine
- Installing and configuring core EDA toolchain components
- Verifying tool installations for subsequent design work

---

## Environment Configuration

### Virtualization Setup

| Component | Configuration |
|-----------|-------------|
| **Hypervisor** | Oracle VirtualBox |
| **Guest OS** | Ubuntu 20.04 LTS |
| **RAM** | 6 GB |
| **vCPUs** | 4 |

The VM is provisioned with sufficient resources to handle compute-intensive EDA tasks such as synthesis, floorplanning, and place-and-route operations.

### Toolchain Installed

| Tool | Purpose |
|------|--------|
| **Yosys** | RTL synthesis framework for converting Verilog to gate-level netlists |
| **Icarus Verilog (iverilog)** | HDL simulation and compilation tool for pre-synthesis verification |
| **GTKWave** | Waveform viewer for debugging simulation outputs (.vcd files) |

---

## Tool Workflow

```
RTL Design (Verilog)
       ↓
Icarus Verilog → Simulate & Verify (VCD output)
       ↓
GTKWave → Visualize Waveforms
       ↓
Yosys → Synthesize to Gate-Level Netlist
```

---

## Screenshots

- **DAY0-0.png** — Initial setup overview
- **DAY0-1.png** — VM configuration
- **DAY0-2.png** — Ubuntu environment ready
- **DAY0-3.png** — Tool installation verification
- **DAY0-4.png** — Version checks
- **DAY0-5.png** — Final environment status

---

## Key Learnings

- Successfully configured a virtualized Linux environment for EDA work
- Installed and validated the complete open-source ASIC toolchain
- Understood the role of each tool in the RTL-to-GDSII flow
- Prepared the system for subsequent RTL design and simulation tasks

---

## Next Steps

- **Week 1**: RTL design and simulation using the 2:1 MUX example
- **Week 2**: SoC-level functional modeling and verification
- **Later stages**: Physical design using OpenLANE and Sky130 PDK

---

## Author

**Krish Bhavsar**  
Electronics & Communication Engineering  
[GitHub: @Kribh19](https://github.com/Kribh19)  
bhavsar.krish33@gmail.com
