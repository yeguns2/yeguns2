# Hi, I’m Yegun Shim 👋

I’m an **Undergraduate Computer Engineering major at UIUC**  
(*Expected Graduation: May 2027*).

I’m passionate about **Embedded Systems, System-on-Chip (SoC) design, FPGA development, and Deep Learning hardware**.  
I enjoy building systems end-to-end—starting from RTL and microarchitecture, all the way to software control, debugging, and performance evaluation on real hardware.

Most of my work so far has been **individually driven**, focusing on learning how real hardware behaves under **tight resource and performance constraints**.

---

## 🔧 Technical Interests & Skills
- **RTL / Hardware Design**: SystemVerilog, FSM-based microarchitecture, pipelining
- **SoC & Interconnects**: AXI4-Lite & AXI4-Full, memory-mapped control, burst transfers
- **FPGA Platforms**: MicroBlaze SoC, DDR-backed systems, Urbana FPGA board
- **Embedded Software**: C/C++ (bare-metal), HW/SW co-design
- **ML Acceleration**: CNN inference, quantization-aware design
- **Tools**: Vivado, simulation & waveform debugging, HW/SW verification

---

## 🚀 Featured Projects (Individual Work)

### 🏃‍♂️ School Run FPGA — 2.5D Endless Runner Game  
**ECE 385 Final Project | Individual**

A real-time **2.5D endless runner game** implemented on FPGA using a **MicroBlaze-based SoC** and custom hardware IP.

**Highlights**
- Designed a **custom HDMI renderer IP** (AXI-controlled, DDR-backed framebuffer)
- Implemented **double buffering** with BRAM line buffers for smooth real-time output
- Integrated **keyboard input, audio output, sprites, and UI overlays**
- Full **HW/SW co-design**: game logic in software, rendering acceleration in hardware

**Tech Stack**
| Area | Details |
|-----|--------|
| CPU | MicroBlaze |
| Interconnect | AXI4-Lite (control), AXI4-Full (memory) |
| Memory | External DDR + BRAM buffers |
| Output | HDMI |
| Language | SystemVerilog, C |

🔗 Repository: https://github.com/yeguns2/School_Run_FPGA

---

### 🧠 FPGA MNIST CNN Accelerator  
**Independent Project**

A custom **CNN inference accelerator** implemented in SystemVerilog for MNIST classification.

**Highlights**
- Built a full CNN pipeline with **convolution, activation, and pooling hardware**
- Used **line buffers and MAC arrays** for streaming computation
- Ran at **100 MHz** on the Urbana FPGA board
- Achieved **~3339× speedup** compared to a **MicroBlaze software (C) baseline**
- Designed under **strict FPGA resource constraints**

**Performance Snapshot**
| Metric | Value |
|------|-------|
| Clock Frequency | 100 MHz |
| Speedup | ~3339× vs MicroBlaze (C) |
| Platform | Urbana FPGA board |
| Scope | Fully individual implementation |

🔗 Repository: https://github.com/yeguns2/FPGA_MNIST_Accelerator

---

## 🤝 Team Projects 
This section will include collaborative projects
with clear descriptions of **my individual technical contributions**.

---

## 📫 Contact
- **Email**: yeguns2@illinois.edu  
- **LinkedIn**: https://www.linkedin.com/in/yegun-shim-0a659433b/  
- **Resume**:
  - https://github.com/yeguns2/yeguns2/blob/main/resume/Yegun_Shim_Resume.pdf
  - https://yeguns2.github.io/assets/Yegun_Shim_Resume.pdf

---

## 🌱 Currently Enjoying
- Designing AXI-based systems and understanding real memory bottlenecks  
- Comparing **HLS vs handwritten RTL** for accelerators  
- Learning how small microarchitectural choices affect real performance  

I enjoy learning by building and iterating on real hardware—feel free to reach out!


