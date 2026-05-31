<!--
**dtejaswarreddy10/dtejaswarreddy10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

# 👋 Hi, I'm Tejeswara Reddy Dudyala  

🚀 **Digital RTL Design Engineer | Verification & AI-EDA Specialist | BITS Pilani M.Tech Scholar**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tejeswara-reddy-dudyala-74784821b)
[![Portfolio](https://img.shields.io/badge/Portfolio-00F2FE?style=for-the-badge&logo=react&logoColor=black)](https://dtejaswarreddy10.github.io/tejeswarareddydudyala)
[![Email](https://img.shields.io/badge/Email-dtejaswarreddy10%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dtejaswarreddy10@gmail.com)

---

### 💡 About Me
I am a Digital RTL Design and Verification Engineer with **2.7+ years of professional silicon design experience** — currently building **RTL and AI-powered verification automation at AMD** (via ACL Digital). 

My expertise spans **FSM-based RTL design**, **UVM-based functional verification environments**, **high-speed protocols (AMBA APB, Ethernet, DVB-S2/S2X)**, and **AI/agentic workflows for EDA/DV productivity**. I am also pursuing my **M.Tech in VLSI Design & Microelectronics from BITS Pilani**.

---

### 🔭 Current Focus & Endeavors
- 🧬 **At AMD:** Author RTL and write test plans/functional verification environments; built an AI agent to review test plans for edge-case coverage gaps and an automated regression-execution/notification framework.
- 🎓 **M.Tech Scholar:** Enhancing my core understanding of microelectronics and advanced VLSI architectures at **BITS Pilani**.
- 🧠 **Hardware-AI Co-Design:** Building localized **In-Memory Computing (IMC)** architectures and hardware accelerators on FPGAs.

---

### 🧠 Technical Toolbox

| Category | Technologies / Tools |
| :--- | :--- |
| **HDL / HDVL** | Verilog, VHDL, SystemVerilog, UVM |
| **EDA & Simulators** | Vivado, QuestaSim, Synopsys VCS, Cadence Xcelium, Riviera-PRO, OneSpin |
| **Protocols** | AMBA APB3, APB-Ethernet 10/100, DVB-S2, DVB-S2X, UART (Familiar with: AXI4, SPI, DMA, FIFO) |
| **Design Concepts** | FSM Design, CDC Analysis, Linting, Clock Gating, RTL Synthesis, ASIC Flow Basics, Spec-to-RTL |
| **AI & Automation** | Claude Code CLI, Agentic Workflows for Verification, Regression Orchestration |
| **Scripting & Tooling** | Python, TCL (LLM-assisted scripting), Git, Perforce, Bash |
| **FPGAs & Hardware** | Zedboard (Zynq-7020), ZC702, Adalm-Pluto, FMCOMMS4 |

---

### 📁 Key Featured Projects

#### ⚡ IMC Tile — INT8 Transformer Attention on Zedboard (2026)
* **Description:** Designed and verified a weight-stationary INT8 GEMM tile on Zynq-7020 PL executing the output projection attention head of `prajjwal1/bert-tiny` bit-exactly.
* **Architecture:** 16 parallel DSP48E1 MACs with custom INT32 accumulation, 128-bit wide BRAM weight streaming, and a 12-state Moore FSM (LOAD/LATCH pipeline with 4-cycle execution).
* **Observed Performance:** Validated 100% bit-exactly vs custom golden software models using Vivado ILA/VIO. Executes attention head in 1,059 cycles (~10.59 µs @ 100 MHz).
* *Tags: Verilog, SystemVerilog, DSP48, BRAM, Moore FSM, Zedboard, Vivado*

#### 📡 DVB-S2 & DVB-S2X Transmitter IP Development
* **Description:** Key designer for the upgrade of transmitter blocks from DVB-S2 to DVB-S2X at Krisemi Design Technologies. 
* **Key Modules:** Designed the FSM-based Mode Adaptation module and an 8-bit customized CRC calculator. Upgraded Frame Length Enforcer, LDPC, and PL framing blocks.
* *Tags: Verilog, FSM, DVB-S2X, CRC, Vivado Sim*

#### 🧮 2x2 Output-Stationary Systolic Array
* **Description:** Implemented a parameterized 2x2 integer matrix multiplication systolic array. Designed core Multiplication & Accumulator Unit (MAU) processing elements (PE) using output-stationary wavefront propagation.
* *Tags: Verilog, Systolic Array, MAC, Vivado xsim*

#### 🖥️ MIPS & RISC-V Processor Architectures
* **Description:** Built a 32-bit single-cycle processor and a 5-stage pipelined processor (IF/ID/EXE/MEM/WB) in Verilog, integrating hazard detection, data forwarding logic, ALU, register file, and control unit.
* *Tags: Verilog, Pipelining, Hazards, QuestaSim*

#### 🔌 APB-based 10/100 Ethernet Protocol Verification (SV/UVM)
* **Description:** Built an IP-level SystemVerilog/UVM verification environment for a 10/100 Ethernet Controller. Produced full verification plans, coverage models, assertions (ABV), and functional testing scenarios.
* *Tags: SystemVerilog, UVM, Ethernet IP, ABV, Coverage*

---

### 💼 Professional Journey

* **Design Engineer** | **ACL Digital (Client: AMD)**  
  *Hyderabad (Nov 2025 – Present)*
  * Digital logic design, verification planning, and owning regression test suites.
  * Designed AI agents for regression automation, automated reporting/email alerts, and automated markdown-to-system-testplan edge-case reviews.

* **RTL Design Engineer** | **Krisemi Design Technologies**  
  *Bengaluru (Jan 2024 – July 2025)*
  * Micro-architected, coded, and verified FSM-based digital logic modules for DVB-S2/S2X protocols.

* **Design Verification Trainee** | **MosChip Institute of Silicon Systems**  
  *Hyderabad (Jun 2023 – Nov 2023)*
  * Built block and system-level SV/UVM testbenches for AMBA APB3 and APB-Ethernet IPs.

---

### 🎓 Education

* **M.Tech in VLSI Design & Microelectronics**  
  *Birla Institute of Technology & Science, Pilani (WILP)* | *Jan 2025 – Dec 2026 (Ongoing)*
* **B.Tech in Electrical & Electronics Engineering**  
  *R V R & J C College of Engineering, Guntur, AP* | *Aug 2019 – Apr 2023*  
  * **CGPA:** 9.13 / 10

---

### 🎯 Core Interests
* 🧠 **AI-for-EDA workflows:** Creating multi-agent systems to accelerate functional DV.
* 🚀 **Edge AI:** Silicon architectures custom-optimized for transformer inference.
* 🏸 Playing Badminton & keeping up with hardware tech boundaries.

---

> "Designing efficient hardware is not just about logic — it’s about logic that works flawlessly every single clock cycle."

⭐ *If you find my projects resourceful, feel free to give them a star!*
