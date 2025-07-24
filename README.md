# ⚡ A New Carry Look-Ahead Adder (CLA) Architecture Optimized for Speed and Energy

## 📌 Project Overview

This project presents a novel Carry Look-Ahead Adder (CLA) architecture optimized for **speed**, **power efficiency**, and **area utilization**. The proposed design introduces a **non-uniform-sized CLA structure**, balancing performance trade-offs using variable module sizes. The implementation was carried out using the **Electric EDA tool** and simulated for performance metrics including delay, area, and power.

## 🧠 Motivation

Traditional CLA designs using uniform-sized modules suffer from scalability issues, especially with increasing bit-widths. By introducing **non-uniform module sizes**, this project aims to reduce the **critical path delay** and **power consumption**, making it more suitable for modern digital systems such as CPUs, GPUs, and DSPs.

## 🔧 Tools and Technologies

- **Electric VLSI Design System**
- **CMOS 45nm Standard Cell Library**
- **Manual Layout Design and Simulation**
- **Custom Gate-Level Design (AND, OR, XOR, NAND, NOR)**

## 🧱 Components Designed

- Custom logic gates (2-input and 3-input NAND/NOR, XOR, etc.)
- CLA modules: 2-bit, 4-bit, 6-bit, 8-bit
- 32-bit CLA architectures:
  - Uniform (e.g., 4×8-bit CLA, 8×4-bit CLA)
  - Non-uniform (e.g., 2×8-bit + 3×4-bit + 2×2-bit CLA)

## 📊 Key Results

| Metric              | Traditional CLA | Proposed NCLA |
|---------------------|------------------|----------------|
| Delay               | Higher            | ✅ Reduced      |
| Power Dissipation   | Moderate          | ✅ Lower        |
| Area Utilization    | Similar           | ✅ Efficient    |
| Energy Efficiency   | Moderate          | ✅ Improved     |

- The **NCLA achieved a critical path delay as low as 0.99 ns**.
- **Up to 20.2% reduction in energy** compared to Kogge-Stone adder.
- **Area usage maintained** at ~37,440 μm² across implementations.

## 📈 Performance Comparison

Multiple CLA configurations were tested, with consistent improvements in the **delay-power trade-off** in non-uniform designs without a significant increase in area.

## 📚 References

Key references and datasets are listed in the report. Main sources include IEEE Xplore, IJCRT, and ResearchGate publications on CLA, CSLA, and hybrid adder architectures.


## 📅 Course

ENCS333 – VLSI Design  


---
