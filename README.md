# Samratth Singh · @AnonymousSingh-007

**Security Researcher · Adversarial AI · Red Teamer**  
Pune · B.Tech Computer Science (Cybersecurity)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samratth-singh-0b9b29279)
[![Hack The Box](https://img.shields.io/badge/HTB_Academy-Top_5%25_Global-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://academy.hackthebox.com)
[![CTF](https://img.shields.io/badge/Ciphathon_2026-14th_National-6E40C9?style=flat-square)](https://github.com/AnonymousSingh-007)
[![NCTAAI](https://img.shields.io/badge/NCTAAI_4.0-Best_Paper_Award-FFB300?style=flat-square)](https://github.com/AnonymousSingh-007)

---

## About

I research adversarial AI and LLM security — specifically how language models fail under adversarial pressure, and how to build systems that don't. On the applied side I build offensive and defensive security tooling: attack-surface enumerators, behavioral biometrics, phishing detection, and multi-agent tactical simulations.

Published researcher (Best Paper · NCTAAI 4.0). Currently working on communication-aware MARL under degraded real-world constraints — studying how RF-denied and high-dropout environments break swarm coordination, and building training regimes that are robust to it.

> Privacy is a myth, but I'll try to exploit it anyway.

---

## 📄 Research

| Paper | Venue | Year | Status |
|---|---|---|---|
| **ICEM: A Taxonomy Framework for LLM Jailbreaking and Prompt Injection** | NCTAAI 4.0 | 2024 | ✅ Published · 🏆 Best Paper Award |
| **MIMIC: Hybrid LSTM + DDPM Framework for Realistic Mouse Motion Synthesis and Behavioral Evasion** | — | 2025 | ✅ Completed |
| **Communication-Robust MARL for Adversarial Swarm Environments** | Target: IJRR / Pattern Recognition | 2025–26 | 🔬 Active |

---

## 🔬 Active Research

### Communication-aware MARL under degraded constraints

Most MARL research assumes perfect communication. Real drone swarms operate in RF-denied environments — links drop, latency spikes, topology shifts asymmetrically. This work asks: how does degraded communication change which algorithm wins, and can a policy be trained to be robust to it?

**What's being built:**
- A systematic comm-degradation benchmark across a dropout spectrum (0% → 80%), dynamic topology changes, and asymmetric link failures
- A comm-robust variant of MAPPO/QMIX explicitly trained under randomised dropout via communication curriculum
- The contribution is both the benchmark (quantifying degradation on swarm search) and the method (robust training regime)

Implemented inside [ARKEN](https://github.com/AnonymousSingh-007) — a battlefield intelligence platform with live Bayesian threat inference, SRTM terrain modeling, and a Palantir Gotham-inspired ops UI. No LLM APIs. Pure probabilistic ML.

**Why this matters:** Sim-to-real transfer for drone swarms breaks primarily on communication, not control. A paper that quantifies the gap and proposes a training curriculum that survives it addresses an open problem that robotics, defence AI, and distributed systems communities all care about.

**Target venues:** International Journal of Robotics Research (robustness + real-world applicability) · Pattern Recognition (comm-robust features as representation learning)

---

### Quantum-inspired phishing infrastructure detection

Applying quantum walk-based graph encoding and hyperedge anomaly detection to classify phishing URL infrastructure at the graph topology level — moving beyond URL feature extraction into structural network analysis. Extends [Phish_Byte](https://github.com/AnonymousSingh-007).

---

## 🛠️ Projects

| Project | What it does | Stack |
|---|---|---|
| [**T.E.M.P.E.S.T**](https://github.com/AnonymousSingh-007/T.E.M.P.E.S.T) | Read-only Windows attack-surface enumerator · unsupervised ML anomaly detection · HTML dashboard output | PowerShell · Python |
| [**S.I.F.E.R**](https://github.com/AnonymousSingh-007) | Behavioral biometrics system with iterative feedback · mouse dynamics · keystroke analysis | Python |
| [**Phish_Byte**](https://github.com/AnonymousSingh-007) | Phishing URL detection · graph-based feature extraction · quantum walk research extension | Python · ML |
| [**SPH1NX**](https://github.com/AnonymousSingh-007/SPH1NX) | Network scan detector for TCP Null/UDP scans · JARVIS-style voice alerts · real-time dashboard | Python · Scapy |
| [**P.R.I.S.M**](https://github.com/AnonymousSingh-007/P.R.I.S.M) | Port response identifier & service mapper | Python |

---

## 💻 Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**ML & Research**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Security**  
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=gnometerminal&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square&logo=owasp&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-228B22?style=flat-square&logo=linux&logoColor=white)
![SQLmap](https://img.shields.io/badge/SQLmap-FFD700?style=flat-square&logo=databricks&logoColor=black)

**Frameworks**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=AnonymousSingh-007&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnonymousSingh-007&layout=compact&theme=dark&hide_border=true&langs_count=6" height="150"/>
</p>

---

*Open to research collaborations, red-team engagements, and masters opportunities in adversarial AI and LLM security.*  
*Reach me via [LinkedIn](https://www.linkedin.com/in/samratth-singh-0b9b29279)*
