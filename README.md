<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Shehroz%20Kashif&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20GSoC%202026%20%40%20Intel%20OpenVINO%20%7C%20LFX%20%2725%20%40%20RISC-V%20International&descAlignY=60&descSize=14&descColor=c4b5fd&animation=fadeIn" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=C4B5FD&center=true&vCenter=true&width=800&lines=Quantization+%26+On-Device+Inference+%7C+INT4%2C+OpenVINO%2C+NNCF;12+Merged+PRs+%7C+Intel+%C2%B7+Linux+Foundation+%C2%B7+Harvard%2FMIT;GSoC+2026+%40+Intel+%7C+5-Agent+Local+Desktop+Automation" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Shehroz57)
[![GSoC](https://img.shields.io/badge/GSoC%202026%20%40%20Intel-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://summerofcode.withgoogle.com/)
[![LFX](https://img.shields.io/badge/LFX%20'25%20%40%20RISC--V-0094FF?style=for-the-badge&logo=linuxfoundation&logoColor=white)](https://mentorship.lfx.linuxfoundation.org/)

</div>

---

I build AI systems that run where the hardware actually is: INT4 quantization, on-device inference, and multi-agent pipelines with no cloud dependency.

My work sits between the model and the machine. On the software side that means weight compression and inference optimization inside Intel's OpenVINO and NNCF toolchain. On the hardware side it means RISC-V ISA specification work for the Linux Foundation, and RV32I processors written in Chisel.

**Right now:** Google Summer of Code 2026 contributor at Intel (OpenVINO), building a fully local 5-agent desktop automation system.
**Next:** open to founding and early-stage engineering roles in LLM inference, edge AI, and efficient ML.

<div align="center">

| | |
|:---:|:---|
| 🌐 | **Google Summer of Code 2026**, selected contributor, Intel / OpenVINO Toolkit |
| 🐧 | **LFX Mentorship 2025**, Linux Foundation / RISC-V International (merit based) |
| 🔀 | **12 merged PRs** into Intel, Linux Foundation, Harvard/MIT, and MERL Lab codebases |
| 🔬 | **3 research projects led** at MERL Lab: hallucination mitigation, LLM benchmarking, RV32I processor design |

</div>

---

## 🔬 Research

My research interest is making large models cheap enough to run on hardware people already own, and measuring honestly whether they still work after you shrink them.

### AI4Org, GAN-Based Hallucination Mitigation for Private LLMs
**Research Assistant, MERL Lab** · Jul 2023 to Dec 2025 · [merledu/ai4org](https://github.com/merledu/ai4org)

A fully on-premise framework for reducing LLM hallucination, with no external API calls at any stage.

- Multi-discriminator GAN pipeline paired with a REINFORCE reinforcement learning optimization loop
- FAISS semantic retrieval for grounded generation
- Fine-tuned TinyLlama, GPT-2, LLaMA-2, and Mistral-7B using PEFT, LoRA, and SFT
- Trained on dual AMD RX 7900 XTX with gradient checkpointing, plus CI/CD for reproducible runs

`PyTorch` `Transformers` `PEFT/LoRA` `FAISS` `GANs` `REINFORCE RL` `ROCm`

### ArcheV, LLM Benchmark Suite for RISC-V RV32I Assembly
**Research Assistant, MERL Lab** · [merledu/ArcheV](https://github.com/merledu/ArcheV)

A standardized evaluation framework for LLM-generated RISC-V assembly, built because general code benchmarks say almost nothing about whether a model understands an ISA.

- Scores functional correctness, syntactic validity, and ISA edge-case coverage
- Reproducible JSON output for cross-model comparison
- RTL-level verification of generated programs

`Python` `Verilog` `llama.cpp` `RISC-V`

### Vermithor and Vahgar, RV32I Processors in Chisel
[Vermithor](https://github.com/Shehrozkashif/Vermithor) (5-stage pipelined) · [Vahgar](https://github.com/Shehrozkashif/Vahgar) (single cycle)

RV32I cores written in Chisel (Scala), with hazard detection, forwarding, and Verilator-based verification.

`Chisel` `Scala` `Verilator` `RISC-V`

---

## 💼 Engineering

### 🟣 Google Summer of Code 2026, Contributor @ Intel (OpenVINO)
`May 2026 to Sep 2026` · Google-sponsored · Remote · Mentors: Ethan Yang, Zhuo Wu

Building a **privacy-preserving GUI desktop automation agent** that runs entirely on-device, with zero cloud dependency.

```
5-Agent Pipeline (A2A Protocol + MCP Server)
──────────────────────────────────────────────────────────────────
Router  →  Planning  →  UI Grounding  →  Action Exec  →  Reflection
           Qwen3        UI-TARS VLM      Native Win32    Self-correct
           INT4         INT4 via OVMS    input           retry loop
```

- INT4 weight compression, KV caching, and prefix caching for a sub-second per-step budget on consumer hardware
- Four one-way layers (`ui → core → agents → desktop`) so the desktop layer reports facts and never makes decisions
- 107 commits restructuring the project into a release-ready state

➡️ **[Shehrozkashif/OpenVINO-Autonomous-GUI-Agent](https://github.com/Shehrozkashif/OpenVINO-Autonomous-GUI-Agent)**

### 🔴 Open Source AI Engineer, Intel (OpenVINO / NNCF)
`Dec 2025 to Mar 2026` · Santa Clara, CA · Remote

- **Stateful LLM compression:** migrated OpenVINO's LLM compression examples to the default stateful inference flow, removing manual `past_key_values` handling ([nncf #3814](https://github.com/openvinotoolkit/nncf/pull/3814), merged)
- **Transpose-aware LoRA correction:** correct handling of MatMul layers with transposed activations in INT4/INT8 quantized LLMs, threading `act_ch_axis` through to LoRA so activation statistics are read on the right axis ([nncf #3845](https://github.com/openvinotoolkit/nncf/pull/3845), [nncf #3864](https://github.com/openvinotoolkit/nncf/pull/3864), in review)
- **PyTorch frontend:** proper support for the `prim::isinstance` operator ([openvino #33803](https://github.com/openvinotoolkit/openvino/pull/33803), in review)

### 🔵 AI Engineer, Skoop
`Apr 2026 to Jun 2026` · Walnut Creek, CA · Remote

- Production LangChain RAG pipelines with FAISS for enterprise knowledge management
- Full retrieval stack: ingestion, semantic chunking, embedding, FAISS indexing, retrieval
- Agentic workflows for autonomous multi-step task execution
- Owned model monitoring loops covering retrieval quality, relevance, and latency

> Proprietary codebase, private repository. Happy to walk through the architecture on a call.

### 🟠 AI Engineer, TheOvalLabs
`Jan 2026 to Apr 2026` · Remote

- Built **Verimate**, an AI platform that generates UVM verification plans and testbenches from RTL/chip designs, for the semiconductor sector
- LangChain, FAISS, Gemini API, and GPU-accelerated local LLMs
- Reduced the manual effort in the hardware verification cycle

> Proprietary codebase, private repository. Happy to walk through the architecture on a call.

### 🟢 Software Engineer, LFX Mentorship @ Linux Foundation / RISC-V International
`Mar 2025 to Jun 2025` · Remote · Mentored by engineers from Qualcomm, Ventana, and Synopsys

- **6 merged PRs** into the canonical machine-readable RISC-V ISA specification
- Implemented the **Zilsd**, **Zclsd**, and **Zcmop** extensions (load/store pair and compressed may-be-operation instructions for RV32)
- Ruby tooling, SimpleCov test coverage reporting, GitHub Actions CI, schema and IDL fixes
- Hypervisor-mode CSR contribution currently in review

---

## 🔀 Open Source

**12 merged pull requests** into production and research codebases, plus 4 currently in review.

<div align="center">

| Organization | Repository | Merged | In review | Contribution |
|:---|:---|:---:|:---:|:---|
| 🐧 **Linux Foundation / RISC-V** | [riscv-unified-db](https://github.com/riscv/riscv-unified-db) | **6** | 1 | Zilsd, Zclsd, Zcmop ISA extensions · Ruby tooling · CI coverage · schema and IDL fixes |
| 🔵 **Intel** | [nncf](https://github.com/openvinotoolkit/nncf) · [openvino](https://github.com/openvinotoolkit/openvino) | **1** | 3 | Stateful LLM compression · transpose-aware LoRA correction · PyTorch frontend |
| 🔴 **Harvard / MIT** | [hnn-core](https://github.com/jonescompneurolab/hnn-core) | **1** | 0 | API documentation for `_add_cell_type_bias` |
| 🟡 **MERL Lab** | [ai4org](https://github.com/merledu/ai4org) · [ArcheV](https://github.com/merledu/ArcheV) | **4** | 0 | Hallucination reduction pipeline · repo hardening · benchmark refactor |

</div>

<details>
<summary><b>All merged PRs</b></summary>
<br>

**RISC-V International** · [#521](https://github.com/riscv/riscv-unified-db/pull/521) RORW operand and IDL fix · [#530](https://github.com/riscv/riscv-unified-db/pull/530) Zcmop 16-bit MOP instructions · [#542](https://github.com/riscv/riscv-unified-db/pull/542) Zilsd extension · [#577](https://github.com/riscv/riscv-unified-db/pull/577) Zclsd extension · [#654](https://github.com/riscv/riscv-unified-db/pull/654) SimpleCov coverage reporting · [#923](https://github.com/riscv/riscv-unified-db/pull/923) CSR schema path fixes

**Intel** · [nncf #3814](https://github.com/openvinotoolkit/nncf/pull/3814) stateful OpenVINO models in LLM compression examples

**Harvard / MIT** · [hnn-core #1001](https://github.com/jonescompneurolab/hnn-core/pull/1001) docstrings for `_add_cell_type_bias`

**MERL Lab** · [ai4org #1](https://github.com/merledu/ai4org/pull/1) hallucination reduction pipeline · [ai4org #49](https://github.com/merledu/ai4org/pull/49) bug fixes, repo restructure, config hardening · [ai4org #50](https://github.com/merledu/ai4org/pull/50) pre-commit checks · [ArcheV #4](https://github.com/merledu/ArcheV/pull/4) repository refactor

</details>

---

## 🛠️ Tech Stack

**Inference and compression**
![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white)
![NNCF](https://img.shields.io/badge/NNCF-0071C5?style=flat-square&logo=intel&logoColor=white)
![INT4/INT8](https://img.shields.io/badge/INT4%20%2F%20INT8%20Quant-0f172a?style=flat-square)
![llama.cpp](https://img.shields.io/badge/llama.cpp-111827?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ROCm](https://img.shields.io/badge/ROCm-CC0000?style=flat-square&logo=amd&logoColor=white)

**LLM and agents**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT/LoRA](https://img.shields.io/badge/PEFT%20%2F%20LoRA-7c3aed?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-1e293b?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0f172a?style=flat-square)
![MCP](https://img.shields.io/badge/MCP%20Protocol-6366f1?style=flat-square)
![A2A](https://img.shields.io/badge/A2A%20Protocol-6366f1?style=flat-square)
![GANs](https://img.shields.io/badge/GANs-be123c?style=flat-square)

**Hardware and systems**
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![Chisel](https://img.shields.io/badge/Chisel-DC322F?style=flat-square&logo=scala&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog%20%2F%20Verilator-1f2937?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## 🎓 Education

**BSc Software Engineering**, UIT University, Karachi

**IBM AI Engineer Professional Certificate** (Coursera, 2025), covering RAG and LangChain applications, AI agents, advanced fine-tuning for LLMs, transformers, and deep learning with PyTorch

---

<div align="center">

### 📬 Let's talk

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![Email](https://img.shields.io/badge/Email%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)

**Open to:** founding and early-stage engineering · LLM inference and infrastructure · edge AI optimization · research collaboration

Based in the UAE. Open to remote, and to relocation.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=110&section=footer" width="100%"/>

*"The gap between a model and a system is where most people give up. That's where I live."*

![Profile Views](https://komarev.com/ghpvc/?username=Shehrozkashif&color=7c3aed&style=flat-square&label=Profile+Views)

</div>
