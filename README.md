# Hi there 👋 I'm Kirthana Senthil

I'm an **Electronics and Communication Engineering student** at **VIT Chennai** and a **Samsung ISWDP Fellow**. My core technical focus centers on **Digital VLSI Design, Verification (DV), and ASIC Implementation**, complemented by hands-on engineering across **Embedded Systems, Edge AI, and Full-Stack Software Development**.

I build systems across the entire stack: from **transistor-level TCAD device modeling and RTL-to-GDSII ASIC flows**, to **embedded microcontroller firmware, custom multi-layer PCBs, and applied machine learning pipelines**.

---

### ⚡ Primary Silicon & Architecture Highlights

* **ASIC Implementation (RTL-to-GDSII):** Designed and hardened an 8×8 INT4 weight-stationary systolic array (64 MAC PEs) to GDSII on SkyWater 130nm using OpenLane; closed GLS setup/hold timing and power-tie-offs, verified with `cocotb`[cite: 14].
* **UVM Verification IP:** Developed a complete UVM 1.2 testbench for AXI4 interconnects with dual master/slave agents, constrained-random stimulus, and self-checking scoreboards (21/21 regression tests passed)[cite: 14].
* **Processor Architecture:** Implemented a synthesizable 5-stage in-order RV32I RISC-V pipelined processor with hazard detection, forwarding units, branch flushing, and an accompanying assembler[cite: 14].
* **In-Memory Compute:** Replicating PICO-RAM, a 65nm PVT-insensitive analog CIM SRAM macro for charge-domain MAC processing in Cadence Virtuoso and Spectre[cite: 11, 14].

---

## 🛠️ Technical Stack

**VLSI Design & Physical Implementation (Core Focus)**
* **HDL & Verification:** SystemVerilog, Verilog HDL, UVM 1.2, SVA (Assertions), cocotb, Constrained-Random Testing, Coverage Driven Verification[cite: 14]
* **EDA & Tooling:** Cadence Virtuoso, Spectre, AMD Xilinx Vivado (xsim), Icarus Verilog, OpenLane, QFlow[cite: 11, 14]
* **Physical Design & Device:** ASIC Flow (Synthesis, Floorplanning, CTS, PnR, STA), DRC/LVS, Synopsys TCAD Sentaurus, LTspice[cite: 11, 14]
* **Nodes & Technologies:** SkyWater 130nm, TSMC 65nm, TFET Device Modeling[cite: 11, 14]

**Embedded Hardware & Systems**
* **Microcontrollers & Architecture:** ESP32, STM32, ARM Cortex-M, 8051, Arduino[cite: 11, 13]
* **Protocols & Busses:** AXI4, APB, SPI, I²C, UART[cite: 11, 14]
* **Hardware & PCB:** 4-Layer PCB Design (KiCad, Altium Designer), Sensor Interfacing, Signal Integrity (<2% crosstalk optimization)[cite: 11, 14]
* **Industrial Systems:** Siemens SINUMERIK 840D, FANUC CNCs, PLC-CNC M-code integration[cite: 11, 14]

**Software, Machine Learning & Algorithms**
* **Languages:** Python, Embedded C, C, Java, MATLAB[cite: 11, 13, 14]
* **AI/ML & Edge AI:** TinyML, TensorFlow/Keras, XGBoost, SVM, Scikit-learn, MFCC Feature Extraction[cite: 11, 13]
* **Computer Vision & NLP:** YOLOv11, OpenCV, OCR Bill Processing, Large Language Models (LLM) Integration[cite: 12, 13]
* **Full-Stack & Cloud:** REST APIs, AWS Cloud fundamentals (SageMaker), NS-3 Network Simulation[cite: 7, 12, 13]

---

## 🔬 Key Projects

### 💽 Digital VLSI & Computer Architecture
* **SkyWater 130nm ASIC Implementation:** Hardened an INT4 systolic array core to clean GDSII via OpenLane with complete gate-level simulation closure[cite: 14].
* **AXI4 UVM Verification IP:** Parameterized UVM 1.2 testbench for AXI4 write/read channels with burst mode support (FIXED, INCR, WRAP) and automated scoreboarding[cite: 14].
* **RV32I 5-Stage Pipelined Core:** Custom Verilog RISC-V processor featuring EX/MEM hazard forwarding and load-use interlocks verified across 11 testbenches[cite: 14].
* **Dynamic Partial Reconfiguration (DFX):** RTL predictive prefetch controller and runtime region mapper designed for Xilinx Zynq/UltraScale+[cite: 14].

### ⚡ Embedded Systems & Core ECE
* **EDUCERE (Edge AI Speech Emotion Classifier):** Real-time emotion classification deployed on an ESP32 using MFCC extraction and TinyML SVM (92% accuracy, 210 ms latency, 38 KB RAM footprint)[cite: 11].
* **Smart Neuropathy Detection Device:** Handheld diagnostic screening device running an ESP32 edge classifier on fused vibration, thermal, and GSR signals at an ultra-low BOM (~INR 1,700)[cite: 11, 14].
* **4-Layer Biomedical Acquisition Board:** Mixed-signal hardware prototype developed at Chakaralaya Analytics with rigorous DRC/LVS validation to limit crosstalk below 2%[cite: 11, 14].

### 💻 Software Engineering & Applied AI
* **FinSight (Financial Intelligence Platform):** Full-stack OCR and NLP platform built at NUS processing 1,350+ multi-format receipts with 91% categorization accuracy and integrated LLM forecasting[cite: 11, 13].
* **4G/5G Dynamic IoT Network Scheduler:** Machine learning-based radio resource allocation model in Python and NS-3 yielding a 23% boost in bandwidth efficiency and 18% lower packet delay[cite: 11, 13].
* **Doomscrolling Posture & Behavior Analysis:** Computer vision pipeline integrating YOLOv11 pose tracking and temporal behavior detection (93–100% accuracy)[cite: 12, 13].

---

## 🏢 Work Experience & Research

* **Heavy Vehicles Factory, Avadi** — *Engineering Intern (May 2026 – Jun 2026)*: Mapped PLC-CNC safety interlocks and evaluated automatic fire suppression control loops on the T-90 Bhishma combat platform[cite: 11, 14].
* **Chakaralaya Analytics** — *Hardware Engineering Intern (Oct 2025 – Aug 2026)*: Owned end-to-end multi-layer biomedical PCB design, schematic capture, and analog signal routing[cite: 11, 14].
* **Centre for Nanoelectronics & VLSI Design, VIT** — *Research Intern (May 2025 – Aug 2025)*: Simulated InAs-Si TFETs in TCAD Sentaurus (SS < 60 mV/dec) and generated compact SPICE models for low-power CNN accelerators[cite: 11, 14].
* **National University of Singapore (NUS)** — *Academic Research Intern (Jun 2025)*: Graduated with Merit in Big Data & Deep Learning while engineering document-intelligence pipelines[cite: 6, 11].

---

## 📜 Key Certifications

* **Samsung ISWDP Student Fellowship:** Semiconductor physics, TCAD simulation, and fabrication process workflows (IISc Bangalore, Samsung SSIR, Synopsys)[cite: 1, 14].
* **Physical Design Training:** ASIC flow, CTS, routing, and timing closure on an SPI master controller using QFlow (Maven Silicon)[cite: 14].
* **VLSI Circuits and Systems:** Analog and Digital Modules (CEP, IIT Kharagpur)[cite: 2].
* **PCB Design & Electronics Fundamentals:** Altium Circuit Maker multi-layer design (Udemy)[cite: 4, 14].

---

## 📫 Connect With Me

* 💼 **LinkedIn:** [linkedin.com/in/kirthana-senthil-7733b828b](https://www.linkedin.com/in/kirthana-senthil-7733b828b)
* 🌐 **Portfolio:** [k1thhh.github.io](https://k1thhh.github.io/)
* 📧 **Email:** [kirthana1612005@gmail.com](mailto:kirthana1612005@gmail.com)
