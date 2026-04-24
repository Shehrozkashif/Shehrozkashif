<div align="center">

# Shehroz Kashif

**AI Infrastructure Engineer · LLM Systems · GPU-Accelerated ML · RISC-V**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shehroz-kashif)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Shehrozkashif)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sharooz57@gmail.com)
[![Location](https://img.shields.io/badge/Dubai%2C%20UAE-00C4CC?style=flat&logo=googlemaps&logoColor=white)](#)

</div>

---

## About Me

I build **production-grade AI systems** — from GPU-accelerated LLM inference backends and RAG pipelines to privacy-first hallucination mitigation frameworks and agentic desktop automation.

What sets me apart is depth across the **full hardware-to-software stack**: I've designed pipelined RISC-V processors in Chisel, optimized CUDA inference for quantized LLMs, and shipped open-source contributions into Linux Foundation and Intel repos — all while pursuing my BSc in Software Engineering.

Currently:
- **AI Infrastructure Engineer (Intern)** @ [Skoop](https://myskoop.com) — GPU-accelerated RAG backends, agentic AI systems
- **Research** — Publishing on GAN-based hallucination mitigation for private LLMs

---

## Current Focus

| Area | What I'm Working On |
|---|---|
| LLM Infra | GPU inference backends — quantization, batching, FAISS RAG |
| Research | Hallucination mitigation paper (AI4Org, GAN + REINFORCE RL) |
| Open Source | Intel NNCF/OpenVINO — LoRA correction, PyTorch frontend fixes |

---

## Experience

**AI Infrastructure Engineer (Intern)** — *Skoop, Walnut Creek CA (Remote)*
`Apr 2026 – Present`
- Deploying GPU-accelerated LLM inference backends via REST APIs
- Building production RAG systems: ingestion → chunking → FAISS embedding → retrieval
- Developing multi-step agentic AI systems over containerized backend services

**AI Engineer** — *The Oval Labs, Karachi (Remote)*
`Jan 2026 – Apr 2026`
- Built **Verimate** — an automated UVM verification platform for chip designs
- Deployed INT4/INT8-quantized LLMs on CUDA clusters via local GPU servers
- Architected end-to-end RAG pipelines with FAISS vector retrieval + LangChain + Gemini API
- Reduced per-query latency via quantization, batching, and memory optimization

**Software Engineer — LFX Mentorship** — *RISC-V International / Linux Foundation (Remote)*
`Mar 2025 – Jun 2025`
- Contributed to **[riscv-unified-db](https://github.com/riscv/riscv-unified-db)** — the canonical machine-readable RISC-V ISA specification (167 stars)
- Landed **6 merged PRs**: new ISA extensions (Zilsd, Zclsd, Zcmop), CI test coverage, schema fixes
- Mentored by engineers from Qualcomm, Ventana, and Synopsys
- Automated formal specification workflows (Python, Ruby, Bash, YAML, GitHub Actions)

**Research Assistant — AI & Hardware** — *MERL (Micro Electronics Research Lab), Karachi*
`Jun 2023 – Dec 2025`
- Led **AI4Org**: GAN-based hallucination mitigation for private LLMs — multi-discriminator pipeline + REINFORCE RL, fine-tuned LLaMA2/Mistral 7B on dual AMD RX 7900 XTX
- Led **ArcheV**: LLM benchmark suite for RISC-V RV32I code — functional, syntactic, and edge-case evaluation via llama.cpp
- Built **Vermithor**: 5-stage pipelined RV32I processor in Chisel (Scala) with hazard detection, forwarding, and Verilator verification
- Managed multi-GPU training infrastructure (RTX 2060 + dual AMD RX 7900 XTX)

---

## Open Source — 9+ Merged PRs

| Repository | Organization | Contributions |
|---|---|---|
| [riscv-unified-db](https://github.com/riscv/riscv-unified-db) | Linux Foundation / RISC-V | 6 merged PRs — ISA extensions, CI coverage, schema fixes |
| [openvinotoolkit/nncf](https://github.com/openvinotoolkit/nncf) | Intel | 1 merged PR — stateful OpenVINO models in LLM compression |
| [jonescompneurolab/hnn-core](https://github.com/jonescompneurolab/hnn-core) | Harvard / MIT | 1 merged PR — docstring improvements |
| [merledu/ai4org](https://github.com/merledu/ai4org) | MERL Lab | 1 merged PR — GPU hallucination reduction pipeline |

**Under review:** OpenVINO PR #33803 (PyTorch frontend fix), NNCF PR #3864 (LoRA transpose_a support)

---

## Featured Projects

<details>
<summary><b>AI4Org — GAN-based Hallucination Mitigation for Private LLMs</b></summary>

**[github.com/merledu/ai4org](https://github.com/merledu/ai4org)**

- Privacy-first GAN framework: generator fine-tunes LLM responses, discriminator detects hallucinations
- Multi-discriminator pipeline with REINFORCE RL optimization loop
- Fine-tuned TinyLlama, GPT-2, LLaMA2, Mistral 7B using PEFT/LoRA/SFT
- FAISS retrieval integration, automated Q&A data generation, INT4 quantization
- Trained on RTX 2060 + dual AMD RX 7900 XTX with gradient checkpointing
- Production-grade: CI/CD, logging, automated testing, design reviews
- Planning research paper publication

**Stack:** PyTorch · Transformers · PEFT · LoRA · FAISS · CUDA · GANs · REINFORCE RL

</details>

<details>
<summary><b>ArcheV — LLM Benchmark Suite for RISC-V RV32I</b></summary>

**[github.com/merledu/ArcheV](https://github.com/merledu/ArcheV)**

- Standardized evaluation framework for LLM-generated RISC-V assembly code
- Evaluates functional correctness, syntactic validity, and ISA edge-case handling
- llama.cpp local inference with structured prompt engineering pipelines
- Reproducible JSON I/O, Verilog simulation, published and presented at lab level

**Stack:** Python · Verilog · llama.cpp · JSON

</details>

<details>
<summary><b>Vermithor — 5-Stage Pipelined RISC-V Processor</b></summary>

- Full RV32I single-cycle and 5-stage pipelined implementations in Chisel (Scala)
- Hazard detection, data forwarding, stall generation
- Verified via Verilator simulation, standards-compliant and fully documented

**Stack:** Chisel · Scala · Verilator · RISC-V RV32I

</details>

---

## Tech Stack

**AI / LLM Systems**
`RAG` `FAISS` `LLM Fine-tuning` `PEFT / LoRA / SFT` `GANs` `Hallucination Mitigation` `Prompt Engineering` `Agentic AI` `MCP` `A2A Protocol` `LangChain` `llama.cpp` `OpenVINO` `NNCF` `Gemini API`

**GPU & ML Infrastructure**
`PyTorch` `TensorFlow` `Hugging Face Transformers` `CUDA` `INT4/INT8 Quantization` `Mixed Precision` `Gradient Checkpointing` `VRAM Optimization` `Multi-GPU Training` `OVMS`

**Languages**
`Python` `Scala (Chisel)` `C++` `Ruby` `Java` `JavaScript` `Verilog` `Shell/Bash` `YAML`

**Hardware & EDA**
`RISC-V ISA (RV32I)` `Chisel HDL` `Verilator` `UVM Verification` `HPC Architecture`

**DevOps & Infrastructure**
`Docker` `Linux` `GitHub Actions` `CI/CD` `REST APIs` `pytest` `Git`

---

## Education & Certifications

**BSc Software Engineering** — UIT University, Karachi · Feb 2022 – Feb 2026

| Certification | Issuer |
|---|---|
| Machine Learning with Python | IBM |
| Deep Learning & Neural Networks with Keras | IBM |
| Scalable Java Microservices with Spring Boot & Spring Cloud | Google |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Shehrozkashif&show_icons=true&theme=tokyonight&hide_border=true" height="155"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Shehrozkashif&theme=tokyonight&hide_border=true" height="155"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shehrozkashif&layout=compact&theme=tokyonight&hide_border=true" height="130"/>
</p>

---

## Connect

- **LinkedIn:** [linkedin.com/in/shehroz-kashif](https://linkedin.com/in/shehroz-kashif)
- **Email:** sharooz57@gmail.com
- **Location:** Dubai, UAE · GST (UTC+04:00) · Open to relocation

---

*Open to collaborations in production AI systems, LLM infrastructure, GPU optimization, and open-source tooling.*
