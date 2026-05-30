<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Shehroz%20Kashif&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Infrastructure%20Engineer%20%7C%20LLM%20Systems%20%7C%20GSoC%20'26%20%40%20Intel%20OpenVINO&descAlignY=58&descSize=16&descColor=a78bfa&animation=fadeIn" width="100%"/>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=Building+Production+LLM+Infrastructure+%F0%9F%A7%A0;GSoC+2026+%40+Intel+OpenVINO+%E2%9C%94;9%2B+Merged+PRs+across+Intel+%2F+Linux+Foundation+%2F+Harvard;GPU+Inference+%E2%80%A2+RAG+Pipelines+%E2%80%A2+GAN+Hallucination+Mitigation;Full+Hardware-to-Software+AI+Stack+Engineer" alt="Typing SVG" />
</a>

<br/><br/>

<!-- BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shehrozkashif)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)
[![Location](https://img.shields.io/badge/Dubai%2C%20UAE-00C4CC?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![GSoC](https://img.shields.io/badge/GSoC%202026-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://summerofcode.withgoogle.com/)

</div>

---

## ⚡ Who Am I

> I build the **infrastructure that makes AI reliable** — production RAG backends, quantized GPU inference, hallucination mitigation frameworks, and the open standards those systems run on.

I operate across the **full hardware-to-software stack**: from designing 5-stage pipelined RISC-V processors in Chisel and optimizing CUDA inference for quantized LLMs, to shipping GAN-based hallucination mitigation frameworks and contributing to Intel's production inference toolchain — all while finishing my BSc in Software Engineering.

My open-source work is embedded in the **Linux Foundation's official RISC-V ISA specification**, **Intel's OpenVINO/NNCF** weight compression framework, and **Harvard/MIT's HNN-Core** — not toy contributions, but production patches that ship to millions.

---

## 🚀 Current Focus

| Domain | What I'm Building |
|---|---|
| **GSoC '26 @ Intel OpenVINO** | Multi-agent GUI desktop automation — VLMs + LLMs, INT4 quantization, KV caching, OpenVINO NPU/GPU/CPU execution |
| **RAG Infrastructure @ Skoop** | GPU-accelerated inference backends · FAISS vector retrieval · LLM reliability at scale |
| **Research (MERL Lab)** | Hallucination mitigation paper — multi-discriminator GANs + REINFORCE RL on LLaMA2 / Mistral 7B |
| **Intel NNCF (Open Source)** | Transpose-aware LoRA Correction · stateful KV-cache LLM compression |

---

## 🏢 Experience

### 🟣 Google Summer of Code 2026 — AI Engineer @ Intel (OpenVINO)
`May 2026 – Present · Seattle, WA`

Selected for **GSoC 2026** to build a **GUI-based multi-agent desktop automation system** powered by Vision-Language Models and LLMs, running fully **local and privacy-preserving** via OpenVINO.

- Designed end-to-end multi-agent architecture: screen perception → LLM reasoning → real-time system action execution across applications
- Integrated OpenVINO-optimized inference with **INT4 quantization**, **KV caching**, **adaptive image history**, and **OVMS** for CPU/GPU/NPU execution
- Built PyQt-based desktop interface with live screen monitoring, execution logs, and system control
- Sub-600ms end-to-end action latency on consumer hardware

---

### 🔵 AI Engineer Intern — Skoop *(Walnut Creek, CA · Remote)*
`Apr 2026 – May 2026`

- Built production RAG pipelines: ingestion → chunking → FAISS embedding → retrieval, deployed over REST APIs
- Developed multi-step agentic AI systems over containerized GPU backends
- Reduced per-query latency via quantization, batching, and memory optimization

---

### 🟠 AI Engineer — TheOvalLabs *(Karachi · Remote)*
`Jan 2026 – Apr 2026`

- Built **Verimate** — AI-powered UVM verification platform for RTL/chip designs
- Architected end-to-end RAG pipeline: **LangChain + FAISS + Gemini API + local GPU inference**
- Deployed INT4/INT8-quantized LLMs on CUDA clusters with optimized batching

---

### 🔴 Open Source AI Engineer — Intel (OpenVINO / NNCF)
`Dec 2025 – Mar 2026 · Santa Clara, CA`

- Contributed **transpose-aware LoRA Correction** for quantized LLM inference (MatMul layers with transposed activations)
- Migrated LLM compression examples to OpenVINO **stateful inference flow**, removing manual KV-cache handling
- Resolved CI failures, reviewer feedback, and cross-environment integration issues
- **[PR #3814](https://github.com/openvinotoolkit/nncf/pull/3814)** · **[PR #3864](https://github.com/openvinotoolkit/nncf/pull/3864)** (under review)

---

### 🟢 Software Engineer — LFX Mentorship @ Linux Foundation (RISC-V International)
`Mar 2025 – Jun 2025 · North Carolina (Remote)`

- Contributed to **[riscv-unified-db](https://github.com/riscv/riscv-unified-db)** — the canonical, machine-readable RISC-V ISA specification (167+ ⭐)
- Landed **6 merged PRs**: Zilsd/Zclsd extensions, Zcmop compressed MOP instructions, CI test coverage, schema fixes, IDL corrections
- Mentored by engineers from **Qualcomm, Ventana, and Synopsys**
- Automated formal ISA specification workflows: Python · Ruby · Bash · YAML · GitHub Actions

---

### 🟡 Research Assistant — MERL Lab (Micro Electronics Research Lab)
`Jul 2023 – Dec 2025 · Karachi`

- Led **AI4Org**: GAN-based hallucination mitigation framework — multi-discriminator pipeline + REINFORCE RL, fine-tuned LLaMA2 / Mistral 7B / TinyLlama on dual AMD RX 7900 XTX
- Built **ArcheV**: first standardized LLM benchmark suite for RISC-V RV32I code — functional, syntactic, and edge-case evaluation via llama.cpp
- Built **Vermithor**: 5-stage pipelined RV32I processor in Chisel with hazard detection, forwarding, and Verilator verification
- Managed multi-GPU training infrastructure (RTX 2060 + dual AMD RX 7900 XTX)

---

## 🔀 Open Source — 9+ Merged PRs

<div align="center">

| Repository | Organization | Contributions |
|---|---|---|
| [riscv-unified-db](https://github.com/riscv/riscv-unified-db) | 🐧 Linux Foundation / RISC-V | **6 merged PRs** — ISA extensions, CI coverage, schema fixes |
| [openvinotoolkit/nncf](https://github.com/openvinotoolkit/nncf) | 🔵 Intel | **1 merged PR** — stateful OpenVINO models in LLM compression |
| [jonescompneurolab/hnn-core](https://github.com/jonescompneurolab/hnn-core) | 🔴 Harvard / MIT | **1 merged PR** — docstring and documentation improvements |
| [merledu/ai4org](https://github.com/merledu/ai4org) | 🟡 MERL Lab | **1 merged PR** — GPU hallucination reduction pipeline |

</div>

> 🔄 **Under Review:** OpenVINO PR #33803 (PyTorch frontend fix) · NNCF PR #3864 (LoRA transpose_a support)

---

## 🧠 Featured Projects

<details>
<summary><b>🔬 AI4Org — GAN-based Hallucination Mitigation for Private LLMs</b></summary>

> **[github.com/merledu/ai4org](https://github.com/merledu/ai4org)**

A **privacy-first, production-grade framework** that reduces LLM hallucinations without relying on external APIs — keeping all data on-premise.

**Architecture:**
- Generator fine-tunes LLM responses; multi-discriminator ensemble detects hallucinations
- REINFORCE RL optimization loop for policy gradient-based quality improvement
- FAISS semantic retrieval for grounded generation
- INT4 quantization for efficient inference on consumer GPUs

**Models Fine-tuned:** TinyLlama · GPT-2 · LLaMA2 · Mistral 7B via PEFT/LoRA/SFT

**Infrastructure:** RTX 2060 + dual AMD RX 7900 XTX · gradient checkpointing · CI/CD · automated testing

**Stack:** `PyTorch` `Transformers` `PEFT` `LoRA` `FAISS` `CUDA` `GANs` `REINFORCE RL`

</details>

<details>
<summary><b>📊 ArcheV — First LLM Benchmark Suite for RISC-V RV32I</b></summary>

> **[github.com/merledu/ArcheV](https://github.com/merledu/ArcheV)**

The **first standardized evaluation framework** for assessing LLM-generated RISC-V assembly code quality.

- Evaluates functional correctness, syntactic validity, and ISA edge-case handling
- llama.cpp local inference with structured prompt engineering pipelines
- Reproducible JSON I/O with Verilog simulation integration

**Stack:** `Python` `Verilog` `llama.cpp` `JSON`

</details>

<details>
<summary><b>⚙️ GSoC '26 — Multi-Agent Desktop Automation (OpenVINO @ Intel)</b></summary>

**Privacy-preserving, fully local GUI automation agent** using Vision-Language Models + LLMs.

- Multi-agent architecture: screen perception → natural language reasoning → cross-app action execution
- OpenVINO-optimized VLM inference at **sub-600ms** end-to-end latency
- INT4 quantization · KV caching · adaptive image history · OVMS deployment
- PyQt desktop UI with live screen monitoring and execution logs

**Stack:** `OpenVINO` `VLMs` `LLMs` `PyQt` `INT4 Quantization` `OVMS` `Python`

</details>

<details>
<summary><b>🖥️ Vermithor — 5-Stage Pipelined RISC-V Processor</b></summary>

Full **RV32I single-cycle and 5-stage pipelined** CPU implementations in Chisel (Scala).

- Hazard detection, data forwarding, stall generation
- Verified via Verilator simulation · standards-compliant · fully documented

**Stack:** `Chisel` `Scala` `Verilator` `RISC-V RV32I`

</details>

---

## 🛠️ Tech Stack

**AI / LLM Systems**

![RAG](https://img.shields.io/badge/RAG-0f172a?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-1e293b?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white)
![NNCF](https://img.shields.io/badge/NNCF-0071C5?style=flat-square&logo=intel&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat-square)
![PEFT](https://img.shields.io/badge/PEFT%20%2F%20LoRA-7c3aed?style=flat-square)
![GANs](https://img.shields.io/badge/GANs-be123c?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-0ea5e9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-6366f1?style=flat-square)

**GPU & ML Infrastructure**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![INT4/INT8](https://img.shields.io/badge/INT4%20%2F%20INT8%20Quantization-0f172a?style=flat-square)
![Multi-GPU](https://img.shields.io/badge/Multi--GPU%20Training-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Scala](https://img.shields.io/badge/Scala%20(Chisel)-DC322F?style=flat-square&logo=scala&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-512BD4?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![REST APIs](https://img.shields.io/badge/REST%20APIs-0f172a?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Hardware & EDA**

![RISC-V](https://img.shields.io/badge/RISC--V%20RV32I-283593?style=flat-square)
![Chisel HDL](https://img.shields.io/badge/Chisel%20HDL-DC322F?style=flat-square)
![Verilator](https://img.shields.io/badge/Verilator-1e3a5f?style=flat-square)
![UVM](https://img.shields.io/badge/UVM%20Verification-4a1d96?style=flat-square)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Shehrozkashif&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=e2e8f0&ring_color=7c3aed" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Shehrozkashif&theme=midnight-purple&hide_border=true&background=0d1117&ring=7c3aed&fire=a78bfa&currStreakLabel=a78bfa" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shehrozkashif&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=e2e8f0" height="135"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Shehrozkashif&bg_color=0d1117&color=a78bfa&line=7c3aed&point=ffffff&area=true&hide_border=true" width="95%"/>
</div>

---

## 🎓 Education & Certifications

**BSc Software Engineering** — UIT University, Karachi · Feb 2022 – Feb 2026

| Certification | Issuer |
|---|---|
| Machine Learning with Python | IBM |
| Deep Learning & Neural Networks with Keras | IBM |
| Scalable Java Microservices with Spring Boot & Spring Cloud | Google |

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![GitHub](https://img.shields.io/badge/Follow%20on%20GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shehrozkashif)
[![Email](https://img.shields.io/badge/Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)

**Open to:** Production AI system collaborations · LLM infrastructure · GPU optimization · Open-source tooling · Research partnerships

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*"The gap between a model and a system is where most people give up. That's where I live."*

![Profile Views](https://komarev.com/ghpvc/?username=Shehrozkashif&color=7c3aed&style=flat-square&label=Profile+Views)

</div>
