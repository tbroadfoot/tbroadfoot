# Dr. Thomas J. Broadfoot  –  VLSI / EDA / TRAP

Hi 👋 I’m **Thomas Broadfoot**, an electrical engineer turned tool-smith who loves turning *ideas into silicon*—and writing the CAD that makes it painless.

---

## What I’m Building

### 🧩 TRAP (Transistor-Level Programmable) Fabric  
A new class of dense, security-centric programmable logic.

* **10× higher LUT/mm²** than mainstream eFPGAs (12 nm silicon in hand)  
* **Transistor-level IC redaction** proven resilient to modern SAT attacks  
* **No weight SRAMs**—perfect for constant-propagated AI accelerators

### 🛠️ TRAP Design Suite  
End-to-end flow that drops TRAP macros straight into any ASIC tape-out.

| Stage | Tooling Highlights |
|-------|-------------------|
| **Verilog → Netlist** | Genus + custom constant-folding passes |
| **Partition & Placement** | ILP-guided hierarchical partitioner, simulated-annealing placer |
| **Routing** | Flat interconnect router tuned for pass-transistor delay |
| **Bitstream / GDS** | Python-driven generators → Tcl / Innovus scripts |

---

## Repos You’ll Find Here

| Repo | What’s Inside |
|------|---------------|
| `trap_tools2` | Core Python EDA stack: partitioner, placer, router, bitstream & layout generators |
| `trap_layout_lib` | Parameterized device-level generators for GF12 & (soon) TSMC 5 nm |
| `ai_demos_on_trap` | Fixed-weight MAC arrays + quantized models running on real TRAP silicon |
| `papers & slides` | Conference decks (HOST, GOMACTech), journal drafts, and thesis artifacts |

---

## Career Highlights

* **2× first-time-right** TRAP tape-outs (GF12)  
* Lead architect & maintainer of a **fully automated Verilog-to-GDS flow**  
* Contributor to open-source placement / routing research in flat-FPGA fabrics  
* **Ph.D. in VLSI & Hardware Security** – UT Dallas (2024)

---

## What I’m Exploring Next

* 3-D chiplet stacking for TRAP-based AI inference  
* Non-volatile switch options (FeFET) for zero-standby power fabrics  
* Static-timing analysis that understands pass-transistor networks

---

### Let’s Connect

* **Email**  `thomas.broadfoot@trap-ics.com`  
* **LinkedIn**  `linkedin.com/in/tbroadfoot`  
* **Website**  `trap-ics.com`

Thanks for stopping by—pull requests, issues, and nerd-outs always welcome! 🚀
