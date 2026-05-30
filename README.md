<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Shehroz%20Kashif&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20GSoC%20'26%20%40%20Intel%20OpenVINO%20%7C%20LLM%20Systems%20%7C%20RAG%20Infrastructure&descAlignY=58&descSize=15&descColor=a78bfa&animation=fadeIn" width="100%"/>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&width=750&lines=GSoC+2026+%40+Intel+OpenVINO+%E2%80%94+5-Agent+Desktop+AI+System;12+Merged+PRs+%E2%80%94+Intel+%2F+Linux+Foundation+%2F+Harvard%2FMIT;Production+RAG+Pipelines+%C2%B7+GPU+Inference+%C2%B7+LLM+Fine-Tuning;GAN-Based+Hallucination+Mitigation+%E2%80%94+MERL+Research+Lab;Full+Hardware-to-Software+AI+Stack+Engineer" alt="Typing SVG" />
</a>

<br/><br/>

<!-- BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shehrozkashif)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)
[![GSoC](https://img.shields.io/badge/GSoC%202026-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://summerofcode.withgoogle.com/)
[![Location](https://img.shields.io/badge/Dubai%2C%20UAE%20%F0%9F%87%A6%F0%9F%87%AA-00C4CC?style=for-the-badge)](#)
[![Available](https://img.shields.io/badge/Immediately%20Available-22c55e?style=for-the-badge)](#)

</div>

---

## ⚡ Who Am I

> I build the **infrastructure that makes AI reliable at scale** — production RAG backends, quantized GPU inference pipelines, multi-agent systems, GAN-based hallucination mitigation, and the open standards those systems run on.

AI Engineer with **2.5+ years** of end-to-end ownership across the full AI/ML lifecycle: data ingestion, model training, GPU-optimized inference, RAG deployment, monitoring, and iteration in production. My open-source contributions are embedded in **Intel's production inference toolchain**, the **Linux Foundation's official RISC-V ISA specification**, and **Harvard/MIT's HNN-Core** — not toy patches, but production-grade engineering in world-class codebases.

Currently building a **5-agent GUI Desktop Automation system** at Intel via Google Summer of Code 2026, running entirely on-device with OpenVINO-optimized LLMs/VLMs at under 600ms step latency.

---

## 🚀 Current Focus

| Domain | What I'm Building |
|---|---|
| **GSoC '26 @ Intel OpenVINO** | 5-agent desktop automation pipeline — Router → Planning → UI Grounding → Action Execution → Reflection, over A2A + MCP. INT4 VLMs/LLMs, OVMS, sub-600ms latency |
| **RAG Infrastructure @ Skoop** | Production LangChain RAG · FAISS vector retrieval · agentic multi-step workflows · LLM reliability at enterprise scale |
| **Research (MERL Lab)** | Hallucination mitigation paper — multi-discriminator GANs + REINFORCE RL on LLaMA2 / Mistral 7B |
| **Intel NNCF (Open Source)** | Transpose-aware LoRA Correction · stateful KV-cache LLM compression · PyTorch frontend fixes |

---

## 🏢 Experience

### 🟣 Google Summer of Code 2026 — AI Engineer @ Intel (OpenVINO)
`May 2026 – September 2026 · Remote`

Selected globally to design and deploy a **privacy-preserving GUI Desktop Automation Agent** — fully local, zero data leaves the device.

- **5-agent architecture** over A2A protocol: Router → Planning → UI Grounding → Action Execution → Reflection, with an MCP server for native desktop control
- Deployed **Phi-3.5-Vision-INT4** (UI grounding via OVMS) + **DeepSeek-R1-Qwen-7B-INT4** (planning/reasoning)
- Applied KV caching, prefix caching, and WEIGHTLESS optimizations — **sub-600ms step latency** on consumer hardware
- Mentored directly by Intel engineers **Ethan Yang** and **Zhuo Wu**

---

### 🔵 AI Engineer — Skoop *(Walnut Creek, CA · Remote)*
`Apr 2026 – Present`

- Built production **LangChain RAG pipelines** with FAISS vector search for enterprise knowledge management — measurable improvement in LLM response accuracy, context-awareness, and hallucination reduction
- End-to-end data engineering: ingestion → semantic chunking → embedding → FAISS indexing → retrieval at scale
- Architected agentic AI workflows enabling autonomous multi-step task execution
- Owned **model monitoring and evaluation loops** — retrieval quality, response relevance, latency metrics

---

### 🟠 AI Engineer — TheOvalLabs *(Karachi · Remote)*
`Jan 2026 – Apr 2026`

- Built **Verimate** — AI platform automating UVM verification plan and testbench generation for RTL/chip designs (semiconductor sector)
- LangChain RAG + FAISS + Gemini API + GPU-accelerated local LLMs; measurable reduction in hardware verification engineering cycle time
- Designed scalable data pipelines (document cleaning, semantic chunking, embedding, FAISS indexing)

---

### 🔴 Open Source AI Engineer — Intel (OpenVINO / NNCF)
`Dec 2025 – Mar 2026 · Santa Clara, CA`

- Contributed **transpose-aware LoRA Correction** — correct handling of MatMul layers with transposed activation layouts in INT4/INT8 quantized LLMs
- Migrated LLM compression examples to OpenVINO **stateful inference flow**, eliminating manual KV-cache handling
- **3 merged PRs:** [#3814](https://github.com/openvinotoolkit/nncf/pull/3814) · [#3864](https://github.com/openvinotoolkit/nncf/pull/3864) · [#33803](https://github.com/openvinotoolkit/openvino/pull/33803)

---

### 🟢 Software Engineer — LFX Mentorship @ Linux Foundation (RISC-V International)
`Mar 2025 – Jun 2025 · Remote`

- **7 merged PRs** to the canonical machine-readable RISC-V ISA specification
- Implemented ISA extensions (Zilsd, Zclsd, Zcmop), Ruby tooling, CI/CD coverage automation via GitHub Actions
- Mentored by engineers from **Qualcomm, Ventana, and Synopsys**
- PRs: [#521](https://github.com/riscv-software-src/riscv-unified-db/pull/521) · [#530](https://github.com/riscv-software-src/riscv-unified-db/pull/530) · [#542](https://github.com/riscv-software-src/riscv-unified-db/pull/542) · [#577](https://github.com/riscv-software-src/riscv-unified-db/pull/577) · [#617](https://github.com/riscv/riscv-unified-db/pull/617) · [#654](https://github.com/riscv-software-src/riscv-unified-db/pull/654) · [#923](https://github.com/riscv-software-src/riscv-unified-db/pull/923)

---

### 🟡 Research Assistant — MERL Lab
`Jul 2023 – Dec 2025 · Karachi`

- Led **AI4Org**: multi-discriminator GAN + REINFORCE RL hallucination mitigation framework — fine-tuned TinyLlama / GPT-2 / LLaMA2 / Mistral 7B with PEFT/LoRA on dual AMD RX 7900 XTX
- Led **ArcheV**: first standardized LLM benchmark suite for RISC-V RV32I code — functional correctness, syntactic validity, ISA edge-case evaluation via llama.cpp
- Built **Vermithor**: 5-stage pipelined RV32I processor in Chisel (Scala) — hazard detection, data forwarding, Verilator verification
- Managed multi-GPU training infrastructure (RTX 2060 + dual AMD RX 7900 XTX)

---

## 🔀 Open Source — 12 Verified Merged PRs

<div align="center">

| Repository | Organization | Contributions |
|---|---|---|
| [riscv-unified-db](https://github.com/riscv/riscv-unified-db) | 🐧 Linux Foundation / RISC-V | **7 merged PRs** — ISA extensions, Ruby tooling, CI/CD coverage |
| [openvinotoolkit/nncf](https://github.com/openvinotoolkit/nncf) | 🔵 Intel | **2 merged PRs** — stateful LLM compression, transpose-aware LoRA |
| [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino) | 🔵 Intel | **1 merged PR** — PyTorch frontend fix (#33803) |
| [jonescompneurolab/hnn-core](https://github.com/jonescompneurolab/hnn-core) | 🔴 Harvard / MIT | **1 merged PR** — documentation improvements (#1001) |
| [merledu/ai4org](https://github.com/merledu/ai4org) | 🟡 MERL Lab | **1 merged PR** — GPU hallucination reduction pipeline |

</div>

> 🏆 **GSoC 2026:** Selected contributor building GUI Agent pipeline integrated into the Intel OpenVINO production ecosystem (May – Sep 2026)

---

## 🧠 Featured Projects

<details>
<summary><b>🤖 GSoC '26 — Privacy-Preserving GUI Desktop Automation Agent (Intel / OpenVINO)</b></summary>

Fully local, zero-cloud multi-agent desktop automation system. No data leaves the device.

**5-Agent Architecture over A2A Protocol:**
1. **Router** — intent classification and task dispatch
2. **Planning** — DeepSeek-R1-Qwen-7B-INT4 for multi-step reasoning
3. **UI Grounding** — Phi-3.5-Vision-INT4 for screen understanding via OVMS
4. **Action Execution** — MCP server for native cross-application system control
5. **Reflection** — quality evaluation and self-correction loop

**Optimizations:** INT4 quantization · KV caching · prefix caching · WEIGHTLESS · adaptive image history
**Result:** Sub-600ms step latency on consumer hardware

**Stack:** `OpenVINO` `OVMS` `VLMs` `LLMs` `A2A Protocol` `MCP` `PyQt` `INT4 Quantization` `Python`

</details>

<details>
<summary><b>🔬 AI4Org — GAN-based Hallucination Mitigation for Private LLMs</b></summary>

> **[github.com/merledu/ai4org](https://github.com/merledu/ai4org)**

Privacy-first framework that reduces LLM hallucinations entirely on-premise — no external APIs.

- Multi-discriminator GAN: generator fine-tunes responses, discriminator ensemble detects hallucinations
- REINFORCE RL optimization loop for policy gradient quality improvement
- FAISS semantic retrieval for grounded generation + INT4 quantization
- Fine-tuned: TinyLlama · GPT-2 · LLaMA2 · Mistral 7B via PEFT/LoRA/SFT
- Infrastructure: RTX 2060 + dual AMD RX 7900 XTX · gradient checkpointing · CI/CD

**Stack:** `PyTorch` `Transformers` `PEFT` `LoRA` `FAISS` `CUDA` `GANs` `REINFORCE RL`

</details>

<details>
<summary><b>⏱️ sktime-MCP — MCP Protocol Layer for Time-Series ML</b></summary>

MCP server exposing sktime's full forecasting and time-series ML API — enabling LLM agents to invoke production ML pipelines as structured tool calls.

- Bridges classical ML (Scikit-learn-compatible) and modern agentic AI architectures
- LLM agents can invoke sktime forecasting models as native tools

**Stack:** `Python` `MCP Protocol` `sktime` `Scikit-learn`

</details>

<details>
<summary><b>📊 ArcheV — First LLM Benchmark Suite for RISC-V RV32I</b></summary>

> **[github.com/merledu/ArcheV](https://github.com/merledu/ArcheV)**

The first standardized evaluation framework for LLM-generated RISC-V assembly code.

- Functional correctness · syntactic validity · ISA edge-case coverage
- llama.cpp local inference with structured prompt engineering
- Reproducible JSON I/O + Verilog simulation integration

**Stack:** `Python` `Verilog` `llama.cpp` `JSON`

</details>

<details>
<summary><b>⚙️ Verimate AI Engine — LLM-Powered Chip Verification Automation</b></summary>

AI platform automating UVM verification plan and testbench generation for RTL/chip designs in the semiconductor sector.

- End-to-end RAG pipeline: LangChain + FAISS + Gemini API + GPU-accelerated local LLMs
- Significant reduction in hardware verification engineering cycle time
- Production-grade data pipelines: cleaning → semantic chunking → embedding → FAISS indexing

**Stack:** `LangChain` `FAISS` `Gemini API` `PyTorch` `CUDA`

</details>

---

## 🛠️ Tech Stack

**AI / LLM Systems**

![RAG](https://img.shields.io/badge/RAG-0f172a?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-1e293b?style=flat-square)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white)
![NNCF](https://img.shields.io/badge/NNCF-0071C5?style=flat-square&logo=intel&logoColor=white)
![PEFT/LoRA](https://img.shields.io/badge/PEFT%20%2F%20LoRA-7c3aed?style=flat-square)
![GANs](https://img.shields.io/badge/GANs-be123c?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-0ea5e9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP%20Protocol-6366f1?style=flat-square)
![A2A](https://img.shields.io/badge/A2A%20Protocol-6366f1?style=flat-square)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat-square)

**GPU & ML Infrastructure**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![INT4/INT8](https://img.shields.io/badge/INT4%20%2F%20INT8%20Quantization-0f172a?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Cloud & MLOps**

![Azure](https://img.shields.io/badge/Azure%20AI%2FML-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Scala](https://img.shields.io/badge/Scala%20(Chisel)-DC322F?style=flat-square&logo=scala&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

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

🏆 **Awards:** Google Summer of Code 2026 — Intel/OpenVINO (globally competitive, Google-sponsored) · LFX Mentorship 2025 — Linux Foundation / RISC-V International (merit-based)

**IBM AI Engineer Professional Certificate** *(Coursera / IBM, 2025)*

| Course |
|---|
| Generative AI Applications with RAG and LangChain |
| Fundamentals of AI Agents Using RAG and LangChain |
| Generative AI Advanced Fine-Tuning for LLMs |
| Generative AI Engineering and Fine-Tuning Transformers |
| Deep Learning with PyTorch |
| AI Capstone Project with Deep Learning |
| Machine Learning with Python · Scalable Java Microservices (Google) |

---

## 🌍 UAE Employment Status

| | |
|---|---|
| 📍 **Location** | Dubai, UAE |
| 🪪 **Visa** | Valid 2-Year UAE Residence Visa |
| ⚡ **Availability** | Immediate Joiner — zero notice period |
| 🔄 **Work Auth** | Open to visa transfer, new sponsorship, or free-zone arrangements |
| 🏙️ **Relocation** | Open to Abu Dhabi, Sharjah, or any UAE emirate |

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![Email](https://img.shields.io/badge/Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow%20on%20GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shehrozkashif)

**Open to:** Production AI systems · LLM infrastructure · GPU optimization · Agentic AI · Open-source tooling · Research collaborations

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*"The gap between a model and a system is where most people give up. That's where I live."*

![Profile Views](https://komarev.com/ghpvc/?username=Shehrozkashif&color=7c3aed&style=flat-square&label=Profile+Views)

</div>
