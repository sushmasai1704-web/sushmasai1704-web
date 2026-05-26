# M Sai Sushma — Hardware Engineer & AI Safety Researcher

🔧 RTL Design · Formal Verification · AI Safety · Published Researcher

Final-year ECE student (RGMCET, JNTUA) with a peer-reviewed publication in analog mixed-signal design and deep experience in formal verification (k-induction, BMC, SVA assertions). Currently applying formal methods thinking to LLM safety research — bridging hardware verification rigour with AI alignment problems.

📧 sushmasai1704@gmail.com · 📍 Anantapur, India · [LinkedIn](https://linkedin.com/in/sai-sushma-m) · [GitHub](https://github.com/sushmasai1704-web)

---

## Publication

**"A Ripple-Free Low-Noise Bandgap Reference Circuit Using PNP Bipolars in 90nm CMOS"**
Peer-reviewed research · 2026 · Notable for an undergraduate project at this stage.
Designed in Cadence Virtuoso (GPDK 90nm CMOS) · <2 mV drift across −40°C to +120°C.

---

## Skills

| Domain | Tools & Technologies |
|--------|----------------------|
| RTL Design | SystemVerilog, Verilog, RISC-V RV32I, FSM design |
| Formal Verification | SymbiYosys, SVA, Z3 SMT Solver, k-induction, BMC, counterexample-driven debug |
| Physical Design | OpenLane, OpenROAD, Magic, KLayout, Sky130A 130nm PDK |
| Analog / Mixed-Signal | Cadence Virtuoso, GPDK 90nm CMOS, bandgap references, PNP bipolars |
| Protocols | AXI4, AXI4-Lite |
| Simulation | Icarus Verilog, Verilator 5.x, GTKWave, OSS CAD Suite |
| Instrumentation | LabVIEW, MATLAB (FFT/PSD), oscilloscopes, signal analysers |
| AI Safety & ML | Python, scikit-learn, Groq API, LLM jailbreak detection, formal property checking |
| Software | C, C++, Git, Linux/Ubuntu, LaTeX |

---

## Featured Projects

| Project | Description | Tools |
|---------|-------------|-------|
| [llm-jailbreak-detector](https://github.com/sushmasai1704-web/llm-jailbreak-detector) | Hybrid LLM jailbreak detector — formal property checking (BMC-style) + Groq LLM semantic layer. 100% accuracy, zero API cost for rule-covered cases. Formal methods applied to AI safety. | Python · Groq API |
| [pwm-3phase-controller](https://github.com/sushmasai1704-web/pwm-3phase-controller) | 3-phase PWM RTL→GDSII on Sky130A — 0 DRC errors, LVS clean, 9 properties proved by k-induction | OpenLane · Magic · KLayout · SymbiYosys |
| [riscv_pipeline_cpu](https://github.com/sushmasai1704-web/riscv_pipeline_cpu) | 5-stage pipelined RV32I CPU — full forwarding, hazard detection, BHT+BTB branch predictor, CPI 1.78 | Verilog · Icarus Verilog |
| [fv-axi4lite-slave](https://github.com/sushmasai1704-web/fv-axi4lite-slave) | Formally verified AXI4-Lite slave IP — 8 SVA temporal assertions, uncovered silent data-corruption bug invisible to 1000+ simulation cycles, proof closure via k-induction (depth 20) | SymbiYosys · Z3 · SystemVerilog |
| [fv-arbiter](https://github.com/sushmasai1704-web/fv-arbiter) | Formally verified 4-requester round-robin arbiter — 6 SVA properties: reset safety, one-hot grant, grant-implies-request | SymbiYosys · Z3 |
| [systolic_array](https://github.com/sushmasai1704-web/systolic_array) | Systolic array for matrix multiplication — ML hardware accelerator | SystemVerilog |
| [PCB-Fault-Classifier](https://github.com/sushmasai1704-web/PCB-Fault-Classifier) | ML-based PCB fault detection — 94% accuracy, automates voltage-capture diagnosis in <5ms | Python · scikit-learn |

---

## RTL to GDSII — PWM Controller on Sky130A 130nm

![PWM Layout](https://raw.githubusercontent.com/sushmasai1704-web/pwm-3phase-controller/main/screenshots/pwm_layout_klayout.png)

*Full RTL→GDSII flow: synthesis → floorplan → placement → routing → DRC/LVS clean.*

---

## What Makes My Profile Unusual

Most ECE students specialise in either hardware or software. My background spans:

- **Formal verification** (hardware) → **AI safety** (LLM jailbreak detection) — same rigorous property-based thinking, different domain
- **Analog design** (bandgap circuit, published) → **ML** (PCB fault classifier) — mixed-signal to data-driven
- **RTL/CPU design** (RISC-V) → **AI accelerators** (systolic array) — silicon to ML systems

I approach every problem the way a verification engineer would: define the properties, find the counterexamples, prove correctness.

---

## Leadership

**VLSI Design Club, RGMCET** — Conducted workshops on DFT, physical design flows, DRC/LVS, and tape-out preparation for 60+ junior students.

---

*Open to research residencies, internships, and full-time roles in AI safety, VLSI design, and hardware-software co-design.*
