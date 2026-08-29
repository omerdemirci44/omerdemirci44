<h1 align="center">Hi, I'm Ömer Talha Demirci 👋</h1>

<h3 align="center">
Application Security • Offensive Security • Security Engineering
</h3>

<p align="center">
Computer Engineering graduate from Istanbul Technical University
</p>

<p align="center">
  <a href="mailto:omertdemirci44@gmail.com">
    <img src="https://img.shields.io/badge/Email-omertdemirci44%40gmail.com-red?style=flat-square&logo=gmail" />
  </a>
  <a href="https://www.linkedin.com/in/omer-talha-demirci-104932220/">
    <img src="https://img.shields.io/badge/LinkedIn-Ömer%20Talha%20Demirci-blue?style=flat-square&logo=linkedin" />
  </a>
  <a href="https://github.com/omerdemirci44">
    <img src="https://img.shields.io/badge/GitHub-omerdemirci44-black?style=flat-square&logo=github" />
  </a>
  <a href="https://substack.com/@blacksmith44">
    <img src="https://img.shields.io/badge/Substack-Siber%20Güvenlik%20Bülteni-orange?style=flat-square&logo=substack" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm a Computer Engineering graduate from **Istanbul Technical University**, focused on **Application Security, Offensive Security, Secure SDLC, and security automation**.

I enjoy working at the intersection of **software engineering and security** — from vulnerability analysis, penetration testing, and secure code review to **SBOM/SAST-based security workflows, AI-assisted evaluation, and security tooling**.

Alongside security, I build projects across **AI/ML, systems programming, computer vision, information retrieval, and backend engineering**.

### Main interests

- Application Security & Secure Code Review
- Offensive Security & Penetration Testing
- Secure SDLC / DevSecOps
- Vulnerability Analysis & Validation
- SBOM, SAST & CVE Analysis
- Network Security & Traffic Analysis
- AI-assisted Security Analysis
- Security Automation

---

## 🧭 Current Focus

- 🔐 Building and improving **security analysis and automation tools**
- 🧪 Developing **SBOM + SAST based release-gate workflows**
- 🛡️ Practicing **penetration testing, secure code review, and vulnerability validation**
- 🤖 Exploring **AI-assisted code and security evaluation**
- 🌐 Strengthening **network and offensive security fundamentals**
- ✍️ Writing cybersecurity notes on [Substack](https://substack.com/@blacksmith44)

---

# 🚀 Featured Projects

## 🔐 SBOM + SAST Analyzer

A modular security analysis system designed to combine **SBOM parsing, vulnerability enrichment, risk scoring, and structured security reporting** into a single workflow.

The project focuses on turning fragmented dependency and vulnerability data into actionable security-review output.

**Highlights**

- SBOM parsing and dependency normalization
- CVE-oriented vulnerability enrichment
- Risk-based finding prioritization
- HTML / PDF / structured reporting
- Modular security-analysis pipeline
- Designed with Secure SDLC and release-gate use cases in mind

**Tech / Domains:**  
`Python` • `Application Security` • `SBOM` • `SAST` • `CVE Analysis` • `Vulnerability Management`

🔗 [Project Overview](https://github.com/omerdemirci44/sbom_sast_analyzer_overview)

---

## 🧠 Local Wikipedia RAG Assistant

A fully local **Retrieval-Augmented Generation system** that answers questions using Wikipedia-derived knowledge while keeping embeddings, vector storage, retrieval, and LLM generation on the local machine.

The pipeline ingests Wikipedia pages, cleans and chunks text, creates local embeddings, performs vector retrieval, and generates grounded answers using Ollama.

**Highlights**

- Wikipedia ingestion and text preprocessing
- Custom chunking pipeline
- Local embeddings with `nomic-embed-text`
- Persistent vector storage with Chroma
- Metadata-aware retrieval
- Local LLM generation with Ollama
- Streamlit chat interface
- CLI and automated pipeline support
- Explicit handling of unsupported questions

**Tech:**  
`Python` • `Ollama` • `Chroma` • `RAG` • `Streamlit` • `Embeddings` • `Information Retrieval`

🔗 [Repository](https://github.com/omerdemirci44/blg483e-local-wikipedia-rag)

---

## 🕷️ Localhost Web Crawler & Search Engine

A modular crawler and search system built around **BFS crawling, durable SQLite state, HTML parsing, indexing, search, and a lightweight localhost web interface**.

The application maintains crawl state across jobs, normalizes and deduplicates URLs, indexes extracted page content, and exposes search and crawl-status capabilities through both CLI and web interfaces.

**Highlights**

- Strict breadth-first web crawling
- URL normalization and deduplication
- Durable crawl state with SQLite
- HTML parsing and content indexing
- Deterministic lexical search
- Crawl status and event tracking
- CLI + localhost web UI
- Background crawl execution
- End-to-end integration testing
- Multi-agent development workflow

**Tech:**  
`Python` • `SQLite` • `HTTP` • `HTML Parsing` • `Search` • `Concurrency` • `Software Architecture`

🔗 [Repository](https://github.com/omerdemirci44/itu-crawler-project-multi-agent)

---

## 👁️ BLG453E Computer Vision

A curated collection of Computer Vision projects covering **image processing, object/shape analysis, facial morphing, optical-flow tracking, vision-based automation, and grounded segmentation**.

**Projects include**

- Gamma correction and image transformations
- HSV-based color segmentation
- Shape detection and counting
- Facial morphing with Delaunay triangulation
- Lucas-Kanade optical-flow hand tracking
- Vision-based game automation
- GroundingDINO + SAM2 segmentation pipeline

**Tech:**  
`Python` • `OpenCV` • `NumPy` • `Dlib` • `Optical Flow` • `GroundingDINO` • `SAM2`

🔗 [Repository](https://github.com/omerdemirci44/BLG453E-Computer-Vision)

---

# 🧩 Selected Engineering Projects

## 🏆 Learning From Data — Term Project

A multi-class machine-learning project organized as an İTÜ BLG454E competition.

The solution finished **#1 on the private leaderboard** with:

**macro-F1: 0.9888**

The project focuses on multi-view feature processing, classification, evaluation, and reproducible experimentation.

**Tech:**  
`Python` • `Machine Learning` • `Feature Engineering` • `Classification` • `Model Evaluation`

🔗 [Repository](https://github.com/omerdemirci44/itu-blg454e-learning_from_data-term_project)

---

## ⚙️ Operating Systems Projects

Three C-based systems programming projects developed for BLG312E:

### Preemptive Priority Scheduler
Process scheduling using:

- `fork` / `exec`
- UNIX signals
- priorities
- arrival times
- remaining execution time

### Multithreaded Stock & Payment Simulation
Concurrent simulation using:

- POSIX threads
- mutexes
- condition variables
- timeouts
- concurrency-safe logging

### MiniFS
A simplified user-space filesystem supporting operations such as:

- `mkfs`
- `mkdir`
- `create`
- `read`
- `write`
- `ls`
- `delete`
- `rmdir`

**Tech:**  
`C` • `Linux` • `POSIX` • `pthreads` • `Processes` • `Concurrency` • `File Systems`

🔗 [Repository](https://github.com/omerdemirci44/itu-blg312e-operating_system-homeworks-c-codes)

---

## 🔧 ARM Microprocessor Systems

Low-level coursework focused on **ARM Cortex-M0+ assembly, C/assembly integration, stack/register discipline, interrupts, and memory-oriented programming**.

Projects include:

- Recursive ARM/Thumb merge sort
- SysTick-driven memory canvas
- C vs Assembly linked-list sorting benchmark

**Tech:**  
`ARM Assembly` • `C` • `Cortex-M0+` • `SysTick` • `Embedded Systems` • `CMSIS`

🔗 [Repository](https://github.com/omerdemirci44/blg212e-microprocessor-systems)

---

## 📈 Algorithmic Trading System

A modular Python-based algorithmic trading and backtesting architecture designed around reusable strategy components and reproducible experiments.

**Highlights**

- Modular strategy framework
- Shared deterministic indicators
- Structured execution logic
- Stop-loss / take-profit / trade-management controls
- Reproducible backtesting workflow
- Separation of data, signals, execution, and risk logic

**Tech:**  
`Python` • `Backtesting` • `Trading Systems` • `Risk Management` • `Software Architecture`

🔗 [Project Overview](https://github.com/omerdemirci44/bot-trading-overview)

---

## 🛠️ Tech Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/ARM%20Assembly-111827?style=flat-square" />
</p>

### Security

<p>
  <img src="https://img.shields.io/badge/Application%20Security-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Secure%20Code%20Review-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/OWASP-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/SBOM%20%2F%20SAST-111827?style=flat-square" />
</p>

### Security & Systems Tools

<p>
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-004575?style=flat-square" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

### Data, AI & Engineering

<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square" />
</p>

---

## 🧪 Experience Highlights

- Application security testing and vulnerability validation
- Secure code review and remediation follow-up
- Penetration testing and re-test workflows
- Vulnerability triage and technical security reporting
- Secure release readiness and Secure SDLC practices
- Network troubleshooting in firewall and access-point environments
- Packet capture and network traffic analysis
- AI-generated code evaluation and structured technical review
- Security automation and engineering-focused tooling

---

## ✍️ Writing

I write about **cybersecurity, security engineering, and technical learning** on Substack:

📌 [Siber Güvenlik Bülteni — Substack](https://substack.com/@blacksmith44)

---

## 📫 Contact

- 📧 Email: **omertdemirci44@gmail.com**
- 💼 LinkedIn: [linkedin.com/in/omer-talha-demirci-104932220](https://www.linkedin.com/in/omer-talha-demirci-104932220/)
- 🐙 GitHub: [github.com/omerdemirci44](https://github.com/omerdemirci44)
- ✍️ Substack: [substack.com/@blacksmith44](https://substack.com/@blacksmith44)

---

<p align="center">
  <i>Security engineering at the intersection of software, automation, and offensive thinking.</i>
</p>
