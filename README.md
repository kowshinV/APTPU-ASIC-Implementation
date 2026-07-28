# 🚀 Approximate Tensor Processing Unit (APTPU) – ASIC Implementation
---
RTL-to-GDSII Implementation of an Approximate Computing Based Tensor Processing Unit (APTPU) for Energy-Efficient AI Hardware Acceleration
---
## 📖 Project Overview

This repository presents the complete ASIC implementation of an Approximate Tensor Processing Unit (APTPU) developed as part of an advanced VLSI design project.

The design is based on the APTPU architecture proposed in the referenced IEEE publication and has been modified and optimized for ASIC implementation. The project demonstrates the complete RTL → Verification → Synthesis → Physical Design → Tapeout flow using industry-standard Cadence and Synopsys EDA tools.
---
## Major architectural optimizations include:

✅ Reduced Systolic Array from 28 × 28 to 12 × 12
✅ Reduced I/O Pins from 110 to 62
✅ Successfully completed the complete ASIC implementation within 10 Days
📑 Project Documentation
📘 Project Report

👉 Click here to view the complete project report

📄 Project Report

📝 Project Description

👉 Click here to learn about the complete project, architecture, design methodology, ASIC flow, implementation details, and final results.

📚 Project Description

🖼️ Final Tapeout Layout

👉 Click here to view the final ASIC tapeout layout generated after completing the physical design flow.

🧩 Final Tapeout Layout

🏗️ Complete ASIC Design Flow

The project follows the complete industrial RTL-to-GDSII implementation flow.

RTL Design
      │
      ▼
Functional Verification
      │
      ▼
SpyGlass (Lint • CDC • RDC)
      │
      ▼
Logic Synthesis
      │
      ▼
Logical Equivalence Check (LEC)
      │
      ▼
Floorplanning
      │
      ▼
Power Planning
      │
      ▼
Placement
      │
      ▼
Clock Tree Synthesis (CTS)
      │
      ▼
Routing
      │
      ▼
Physical Verification
      │
      ▼
Final Tapeout (GDSII)
⚙️ Design Specifications
Parameter	Specification
Technology	180 nm CMOS
Chip Size	5 mm × 5 mm
Core Area	~9,000,000 μm²
Standard Cells	~300,000
Total I/O Pins	62
Systolic Array	12 × 12 APE Array
RTL Language	Verilog HDL
🛠️ Tools Used
Verilog HDL
Cadence SimVision
Synopsys SpyGlass
Cadence Genus
Cadence Conformal LEC
Cadence Innovus
Cadence Virtuoso
📂 Repository Structure
APTPU-ASIC-Implementation
│
├── 📄 Project_Report.pdf
│
├── 📁 Images
│     ├── Architecture.png
│     ├── Simulation.png
│     ├── Synthesis.png
│     ├── Floorplan.png
│     ├── Placement.png
│     ├── CTS.png
│     ├── Routing.png
│     ├── GDS_Layout.png
│     └── Final_Tapeout.png
│
└── README.md
🎯 Applications
🤖 AI Inference Acceleration
📷 Computer Vision
🚗 Autonomous & Robotics Systems
📡 Edge AI Devices
🌐 Embedded AI & IoT
🏥 Medical Image Processing
🎥 Smart Surveillance
📌 Note

This repository showcases the ASIC implementation and project documentation of the Approximate Tensor Processing Unit (APTPU).
The architecture is based on the referenced IEEE publication and includes design optimizations performed during this project.
RTL source code is not included in this repository.

📚 Reference

IEEE Publication

Approximate Computing Based Tensor Processing Unit (APTPU)

(Include the complete IEEE citation or DOI here.)

⭐ If you found this project interesting, consider giving it a star!
