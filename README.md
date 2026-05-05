# Low Power Optimized 7T SRAM Design using Stacking Effect

## Description
This project focuses on designing and optimizing a 7T SRAM cell using the stacking effect to reduce power consumption and improve stability. The design is implemented using Cadence tools for simulation and analysis.

The stacking technique reduces leakage power by increasing threshold voltage and minimizing drain voltage, making the design suitable for low-power AI and IoT applications.

---

## Objective
- Reduce leakage power in SRAM cells
- Improve read/write stability
- Enhance energy efficiency for AI and IoT devices

---

## Problem Statement
- High leakage power in 6T SRAM
- Poor read stability in conventional SRAM
- Need for energy-efficient memory for AI and IoT systems

---

## Proposed Methodology
- Use stacking effect in CMOS transistors
- Increase threshold voltage (Vth) to reduce leakage
- Reduce drain voltage (Vds) to minimize static power
- Suppress subthreshold and gate leakage currents

---

## Tools Used
- Cadence Virtuoso
- Spectre Simulator
- gpdk45 nm technology

---

## Design Process
1. Create SRAM schematic in Cadence
2. Design 7T SRAM cell using CMOS transistors
3. Configure bit-lines, word-lines, and power supply
4. Perform DC and transient analysis
5. Measure delay and power consumption

---

## Results

### Power Comparison (45nm Technology)
- 6T SRAM (without stacking): 131.3 µW
- 6T SRAM (with stacking): 79.48 µW
- 7T SRAM (without stacking): 72.83 µW
- 7T SRAM (with stacking): **22.55 µW**

Significant power reduction achieved (~50%)

---

### Delay Analysis
- 7T with stacking: 46.89 ps
- 7T without stacking: 46.61 ps

No major delay increase while reducing power

---

## Features
- Low power consumption
- Reduced leakage current
- Improved stability
- Suitable for AI and IoT applications

---

## Applications
- AI accelerators
- IoT edge devices
- Low-power embedded systems
- Memory design in VLSI circuits

---

## Conclusion
The optimized 7T SRAM using stacking effect achieves significant power reduction while maintaining performance. This makes it suitable for next-generation AI and IoT systems where energy efficiency is critical.

---

## Future Scope
- Integration with advanced technology nodes
- Hybrid memory architectures
- Further optimization using AI-based design techniques
