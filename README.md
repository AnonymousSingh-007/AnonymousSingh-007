# Samratth Singh · @AnonymousSingh-007

> *Security researcher at the intersection of adversarial AI and offensive tooling.*
> *I study how systems fail — and build the things that find out.*

**📍 Pune, India · B.Tech CS (Cybersecurity) · Open to research collabs & security roles**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samratth-singh-0b9b29279)
[![Hack The Box](https://img.shields.io/badge/HTB-Top%205%25-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://www.hackthebox.com)
[![Email](https://img.shields.io/badge/Open%20to%20Collabs-Let's%20Talk-blueviolet?style=flat)](#)

---

## What I work on

I research **adversarial AI and LLM security** — specifically how language models fail under adversarial pressure, and how to build systems that don't.

On the applied side I build **offensive and defensive security tooling**: attack-surface enumerators, behavioral biometrics, phishing infrastructure detection, and multi-agent tactical simulations.

Published researcher. Currently studying how RF-denied and high-dropout environments break swarm coordination in multi-agent systems, and building training regimes that are robust to it.

> *Privacy is a myth. But I'll try to exploit it anyway.*

---

## 📄 Research

| Paper | Venue | Year | Status |
|---|---|---|---|
| ICEM: A Taxonomy Framework for LLM Jailbreaking and Prompt Injection | NCTAAI 4.0 | 2024 | ✅ Published · 🏆 Best Paper Award |
| MIMIC: Hybrid LSTM + DDPM for Realistic Mouse Motion Synthesis & Behavioral Evasion | — | 2025 | ✅ Completed |
| Communication-Robust MARL for Adversarial Swarm Environments | Target: IJRR / Pattern Recognition | 2025–26 | 🔬 Active |

---

## 🛠️ Featured Projects

### [T.E.M.P.E.S.T](https://github.com/AnonymousSingh-007/T.E.M.P.E.S.T) — Windows Attack Surface Enumerator
Read-only PowerShell enumerator with unsupervised ML anomaly detection and HTML dashboard output. Built for red team recon without touching disk offensively.
`PowerShell` `Python` `ML` `Red Team`

### [MIMIC](https://github.com/AnonymousSingh-007/MIMIC) — Behavioral Evasion via Synthetic Mouse Dynamics
Hybrid LSTM + DDPM framework that synthesizes realistic mouse motion to evade behavioral biometrics systems. Combines generative modeling with adversarial evasion.
`Python` `PyTorch` `DDPM` `Adversarial ML`

### [RAV3N-sec](https://github.com/AnonymousSingh-007/RAV3N-sec) — AI-Ready Static Vulnerability Scanner
Fast, local static analyzer combining Regex + AST to detect 30+ security vulnerability classes in Python code. Severity-graded with rich CLI output. No API calls. Runs entirely local.
`Python` `AST` `Static Analysis` `AppSec`

### [Phish_Byte](https://github.com/AnonymousSingh-007/Phish_Byte) — Graph-Based Phishing Infrastructure Detection
Phishing URL detection using graph-based feature extraction. Research extension applies quantum walk-based graph encoding and hyperedge anomaly detection for structural network analysis.
`Python` `Graph ML` `Quantum Walks` `Threat Intel`

---

## 🔬 Active Research

**Communication-Robust MARL for Adversarial Swarm Environments**

Most MARL research assumes perfect communication. Real drone swarms operate in RF-denied environments — links drop, latency spikes, topology shifts asymmetrically.

This work builds:
- A systematic comm-degradation benchmark across a dropout spectrum (0% → 80%), dynamic topology changes, and asymmetric link failures
- A comm-robust variant of MAPPO/QMIX explicitly trained under randomised dropout via communication curriculum

Implemented inside **ARKEN** — a battlefield intelligence platform with live Bayesian threat inference, SRTM terrain modeling, and a Palantir-inspired ops UI. Pure probabilistic ML. No LLM APIs.

*Why it matters: sim-to-real transfer for drone swarms breaks primarily on communication, not control. Quantifying that gap and proposing a curriculum that survives it addresses an open problem that robotics, defence AI, and distributed systems communities all care about.*

Target venues: **IJRR** · **Pattern Recognition**

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML & Research**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Security**

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-00549E?style=flat&logo=owasp&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-228B22?style=flat&logo=gnu&logoColor=white)
![SQLmap](https://img.shields.io/badge/SQLmap-CC0000?style=flat&logo=databricks&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-306998?style=flat&logo=python&logoColor=white)

**Frameworks**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

---

## Let's connect

I'm open to **research collaborations**, **red-team engagements**, and **masters opportunities** in adversarial AI and LLM security.

If you're working on something at the edge of AI and offensive security — reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samratth%20Singh-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samratth-singh-0b9b29279)
