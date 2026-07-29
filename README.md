# 🚀 Approximate Tensor Processing Unit (APTPU)
### ASIC RTL-to-GDSII Implementation for Energy-Efficient AI Hardware Acceleration

<p align="center">

![ASIC](https://img.shields.io/badge/ASIC-Implementation-blue?style=for-the-badge)
![Verilog](https://img.shields.io/badge/Verilog-HDL-success?style=for-the-badge)
![Cadence](https://img.shields.io/badge/Cadence-EDA-red?style=for-the-badge)
![Technology](https://img.shields.io/badge/Technology-180nm-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Tapeout_Ready-brightgreen?style=for-the-badge)
</p>

---

# 📌 About the Project

The **Approximate Tensor Processing Unit (APTPU)** is an ASIC-based AI accelerator designed to efficiently execute tensor and matrix computations using **Approximate Computing** techniques. The objective of this project is to achieve high computational throughput while reducing silicon area, power consumption, and hardware complexity.

This project demonstrates the complete **RTL-to-GDSII ASIC Implementation Flow** using industrial EDA tools.

The implementation is based on the architecture proposed in the referenced IEEE publication and includes several architectural optimizations performed during this project.

---

# ✨ Project Objectives

- Design an ASIC-based AI Hardware Accelerator
- Reduce Hardware Complexity
- Improve Throughput
- Minimize Power Consumption
- Complete Full RTL-to-GDSII Flow
- Gain Hands-on Experience with Industrial EDA Tools

---

---

# 📂 Quick Navigation

| 📄 Resource | 📋 Description | 🔗 Access |
|:------------|:---------------|:---------:|
| 📘 **Project Report** | Complete project report with architecture, implementation flow, synthesis, physical design, verification, and results. | **[View Report](APTPU_REPORT2_p.pdf)** |
| 📝 **Project Description** | Overview of the Approximate Tensor Processing Unit (APTPU), design methodology, architecture, ASIC implementation flow, and key project highlights. | **[Read Description](description.png)** |
| 🧩 **Final Tapeout Layout** | Final GDSII tapeout layout showing pad ring, core area, routing, and physical implementation of the ASIC. | **[View Layout](final_layout.jpeg)** |

---

# 🏗️ Architecture Highlights

✅ Approximate Computing Architecture

✅ 12 × 12 Approximate Processing Element (APE) Systolic Array

✅ IFMAP FIFO

✅ Weight FIFO

✅ Controller FSM

✅ Output Feature Map (OFMAP) Interface

✅ Optimized ASIC Datapath

---

# 📈 Design Improvements

Compared with the reference architecture:

| Feature | Original | Implemented |
|----------|-----------|-------------|
| Systolic Array | 28 × 28 | 12 x 12 |
| Total I/O Pins | 102 | 41 |
| ASIC Optimization | Basic | Optimized |
| Implementation | Reference | Complete RTL → GDSII |

---

# ⚙️ ASIC Design Specifications

| Parameter | Value |
|------------|--------|
| Technology | 180 nm CMOS |
| Chip Size | 3 mm × 3 mm |
| Core Area | 1,707,278 |
| Cell Count | 278356 |
| Total I/O Pins | 41 |
| Timing Status | PASS |
| Routing Overflow | 0% |
| WNS | +8.418 ns |
| TNS | 0 ns |

---

# 🔄 Complete ASIC Design Flow

---

⭐ RTL Functional Verification

The RTL design of the APTPU was functionally verified using **Cadence SimVision**. The simulation validates the controller FSM, IFMAP and Weight loading, systolic array operation, and OFMAP generation.

👉 Click here to [View Waveform](waveform.png)

---

⚙️ Logic Synthesis

Logic synthesis was completed using **Cadence Genus**, converting the RTL into an optimized gate-level netlist while satisfying area and timing constraints.

👉 Click here to [View Synthetic report](syntheticrpt.png)

---

✅ Logical Equivalence Check (LEC)

The synthesized netlist was verified against the RTL using **Cadence Conformal LEC**, ensuring complete functional equivalence.

👉 Click here to [View Lec report](lec.png)

---

 🏢 Floorplanning

The floorplan defines the chip boundary, core area, pad ring, and placement region before physical implementation.

👉 Click here to [View Floorplan layout](fp.png)

---

⚡ Power Planning

Power rings and power stripes were inserted to provide stable power distribution throughout the chip.

👉 Click here to [View Powerplan Layout](pp.png)

---

📍 Standard Cell Placement

Standard cells were placed and optimized to minimize congestion and improve timing performance.

👉 Click here to [View Placement layout](placement.png)

---

🌳 Clock Tree Synthesis (CTS)

Clock buffers and routing were inserted to minimize clock skew and insertion delay.

👉 Click here to [View CTS layout](cts.png)

---

🛣️ Routing

Global and detailed routing connected all signal paths while maintaining design rule compliance and timing closure.

👉 Click here to [View Routing layout](route.png)

---

📈 Timing Analysis

Post-route timing analysis confirms positive slack and successful timing closure.

👉 Click here to [View Timing report](timing.png)

---

💎 Final Tapeout Layout

The final GDSII layout includes the I/O pad ring, power network, routing layers, and optimized standard cell placement, making the design fabrication-ready.

👉 Click here to [View Tapeout layout](tp.png)

---

# 🛠️ EDA Tools

- Verilog HDL
- Cadence SimVision
- Synopsys SpyGlass
- Cadence Genus
- Cadence Conformal LEC
- Cadence Innovus
- Cadence Virtuoso

---

# 🎯 Applications

- Artificial Intelligence Inference
- Edge AI Computing
- Embedded AI Systems
- Computer Vision
- Smart Surveillance
- Robotics
- Autonomous Systems
- Medical Image Analysis
- IoT Intelligence

---

# 📌 Repository Note

This repository showcases the ASIC implementation of an Approximate Tensor Processing Unit (APTPU).

The project focuses on the complete RTL-to-GDSII implementation flow and demonstrates practical VLSI physical design methodology using Cadence and Synopsys EDA tools.

**RTL source code is intentionally not included in this repository.**

---

# ⭐ Support

If you found this project helpful or interesting,

⭐ **Please consider giving this repository a Star!**

It motivates future VLSI and ASIC open-source documentation.

---

# 👨‍💻 Author

## **Kowshin**

**Electronics and Communication Engineering (ECE)**

**Aspiring VLSI Design Engineer**

📍 Tamil Nadu, India

*"Passionate about Digital Design, RTL Development, ASIC Physical Design, and AI Hardware Accelerators."*

---
