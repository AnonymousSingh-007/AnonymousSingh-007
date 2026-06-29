<div align="center">

```
█▀▀ ▄▀█ █▀▄▀█ █▀█ ▄▀█ ▀█▀ ▀█▀ █░█
▄▄█ █▀█ █░▀░█ █▀▄ █▀█ ░█░ ░█░ █▀█
```

**`Adversarial Systems Researcher · DIAT / DRDO-affiliated · Red Teamer`**

*I study how intelligent systems are made to betray their purpose —*
*across language models, multi-agent coordination, and behavioral biometrics.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samratth-singh-0b9b29279)
[![HTB](https://img.shields.io/badge/HackTheBox-Top%205%25-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://www.hackthebox.com)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-SamSec007-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SamSec007)
[![Portfolio](https://img.shields.io/badge/Portfolio-anonymoussingh--007.github.io-blueviolet?style=flat&logo=github&logoColor=white)](https://anonymoussingh-007.github.io/Portfolio/)
[![CTF](https://img.shields.io/badge/CTF-14th%20National%20Rank-orange?style=flat&logo=hackthebox&logoColor=white)](#)

</div>

---

## ⚡ Active Research Status

| Project | Stage | Status | Target |
|---|---|---|---|
| 🔴 **EVELYN** — Quantum Graph Phishing Detection | Stage 2 · Quantum walks implementing | `🔄 Active` | IEEE S&P / USENIX |
| 🟡 **SWARN** — Comm-Robust MARL for Drone Swarms | Manuscript complete · Submission imminent | `📝 Submitting` | IEEE TNNLS |
| 🟢 **MIMIC** — LSTM+DDPM Behavioral Evasion | Complete · JSD=0.1478 · 100% evasion | `📨 Under Review` | IEEE TIFS |
| ✅ **ICEM** — LLM Jailbreak Taxonomy | Published · Best Paper · Best Presentation | `🏆 NCTAAI 4.0 · 2024` | NCTAAI 4.0 |

---

## 🧠 About

```python
researcher = {
    "name"       : "Samratth Singh",
    "affiliation": "DIAT · DRDO-affiliated · Pune",
    "degree"     : "B.Tech CS (Cybersecurity)",
    "focus"      : ["Adversarial AI", "LLM Red Teaming", "MARL Robustness",
                    "Behavioral Biometrics", "Quantum Graph Theory"],
    "published"  : True,
    "award"      : "Best Paper · Best Presentation · NCTAAI 4.0 · 2024",
    "htb_rank"   : "Top 5% Global",
    "ctf_rank"   : "14th National · Ciphathon",
    "status"     : "Open to research collabs · Masters opportunities · Red team roles",
}
```

> *Privacy is a myth. But I'll try to exploit it anyway.*

---

## 📄 Research

| Paper | Venue | Year | Status |
|---|---|---|---|
| ICEM: Taxonomy of LLM Jailbreaking & Prompt Injection | NCTAAI 4.0 | 2024 | ✅ Published · 🏆 Best Paper · Best Presentation |
| MIMIC: Hybrid LSTM+DDPM for Mouse Motion Synthesis & Behavioral Evasion | IEEE TIFS (target) | 2025 | 📨 Under Review |
| SWARN: Communication-Robust MARL for Adversarial Swarm Environments | IEEE TNNLS (target) | 2025–26 | 📝 Submitting |
| EVELYN: Quantum Walk Phishing Infrastructure Detection | IEEE S&P / USENIX (target) | 2026 | 🔄 Stage 2 · Quantum Walks |

---

## 🛠️ Systems Built

### [EVELYN](https://github.com/AnonymousSingh-007/EVELYN) — Quantum Graph Phishing Infrastructure Detection
> *They change their names. They can't change their shape.*

Continuous-time quantum walk on a phishing infrastructure hypergraph. Topology fingerprint φ(G) = |⟨j|e^{−iHt}|k⟩|² is invariant to domain names — detects campaign infrastructure by shape, not string. Zero-shot on new topologies. Provably superior to GNNs for this task.
`Python` `Quantum Walks` `NetworkX` `DBSCAN` `Graph ML`

### [MARL-Research / SWARN](https://github.com/AnonymousSingh-007/MARL-Research) — Comm-Robust Drone Swarm RL
> *Most MARL assumes perfect comms. Real swarms don't get that.*

1,050-run benchmark identifying QMIX's structural blindness to communication state. Two-process fix: frozen QMIX explorer + KL-anchored Navigator. +13.0 detection points under chase jammer. 46 passing tests. Paper-grade figures generated.
`PyTorch` `QMIX` `PPO` `MARL` `CUDA`

### [MIMIC](https://github.com/AnonymousSingh-007/M.I.M.I.C.) — Behavioral Evasion via Synthetic Mouse Dynamics
> *The model that fooled every bot detector it met.*

Hybrid LSTM+DDPM framework synthesizing human-like mouse motion trajectories. JSD = 0.1478 (near-perfect human distribution match). 100% bot-detector evasion rate. 212,568-sample custom behavioral dataset.
`Python` `PyTorch` `DDPM` `LSTM` `Adversarial ML`

### [T.E.M.P.E.S.T](https://github.com/AnonymousSingh-007/T.E.M.P.E.S.T) — Windows Attack Surface Enumerator
Read-only PowerShell enumerator. Collects services, ports, autostart vectors, firewall rules, scheduled tasks, browser extensions. Optional unsupervised ML anomaly scoring. HTML dashboard output.
`PowerShell` `Python` `Isolation Forest` `Red Team`

### [RAV3N-sec](https://github.com/AnonymousSingh-007/RAV3N-sec) — Static Vulnerability Scanner
AST + Regex hybrid detecting 30+ vulnerability classes in Python. Severity-graded (HIGH/MED/LOW). Rich CLI. Runs entirely local — no API calls, no cloud.
`Python` `AST` `Typer` `Rich` `AppSec`

### [Phish_Byte](https://github.com/AnonymousSingh-007/Phish_Byte) — Cascading MLP Email Phishing Detector
> *9,000× smaller than DistilBERT. Hits F1 0.948. Explains every verdict.*

From-scratch PyTorch MLP trained on 29 hand-engineered features — no pretrained weights, no transformer backbone. Cascading inference: rule scorers short-circuit obvious phishing in ~1ms, MLP handles ambiguous cases in ~3ms. Per-feature attribution on every decision. Deployed on HuggingFace.

| Metric | Value |
|---|---|
| F1 Score | **0.948** |
| Accuracy | 94.4% |
| Parameters | **12,545** (vs 66M DistilBERT) |
| Throughput | **1,527 emails/sec** GPU |
| Model size | ~50 KB |

[![HuggingFace](https://img.shields.io/badge/Model-SamSec007%2Fphishbyte-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SamSec007/phishbyte)
`Python` `PyTorch` `Safetensors` `Explainable AI` `Email Security`

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
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Security**

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-00549E?style=flat&logo=owasp&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-306998?style=flat&logo=python&logoColor=white)

**Frameworks**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AnonymousSingh-007&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=9FEF00&icon_color=9FEF00&text_color=ffffff&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AnonymousSingh-007&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=9FEF00&text_color=ffffff)

![GitHub Streak](https://streak-stats.demolab.com?user=AnonymousSingh-007&theme=dark&hide_border=true&background=0d1117&stroke=9FEF00&ring=9FEF00&fire=FF6B35&currStreakLabel=9FEF00)

</div>

---

## 🎵 Now Playing

[![Spotify](https://img.shields.io/badge/Spotify-Now%20Playing-1DB954?style=flat&logo=spotify&logoColor=white)](https://open.spotify.com/search/Dark%20Knight%20Rustage)

> 🎧 **Dark Knight** — Rustage *(on loop during EVELYN quantum walks)*

---

## 🗓️ Timeline

```
Aug 2024 ── GitHub account created
Oct 2024 ── SPH1NX · P.R.I.S.M · Phish_Byte shipped
Dec 2024 ── 🏆 Best Paper + Best Presentation · NCTAAI 4.0
Jan 2025 ── T.E.M.P.E.S.T v1 complete (PowerShell + ML)
Feb 2025 ── S.I.F.E.R · Sparakthon project
Mar 2025 ── Research Intern @ ICAR
May 2025 ── Research Intern @ DIAT · DRDO-affiliated ← active
Jun 2025 ── MARL-Research Phase A: 1,050-run benchmark complete
Sep 2025 ── RAV3N-sec shipped (AST+Regex vulnerability scanner)
Nov 2025 ── MIMIC complete · JSD=0.1478 · 100% bot evasion
Jan 2026 ── MARL Phase D: Navigator+QMIX · +13pts under chase jammer
Feb 2026 ── EVELYN initiated · Quantum graph phishing detection
Jun 2026 ── SWARN manuscript complete · submitting to IEEE TNNLS
Jun 2026 ── EVELYN Stage 2 · quantum walk implementation underway
Jun 2026 ── Phish_Byte model deployed on HuggingFace · F1 0.948 · 12.5k params
2026 ───── IEEE TNNLS (SWARN) · IEEE TIFS (MIMIC) · targeting IEEE S&P (EVELYN)
```

---

## 🤝 Let's connect

Open to **research collaborations**, **red-team engagements**, and **masters opportunities** in adversarial AI and LLM security. If you're working at the edge of AI and offensive security — reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samratth%20Singh-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samratth-singh-0b9b29279)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-SamSec007-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/SamSec007)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-blueviolet?style=flat&logo=github&logoColor=white)](https://anonymoussingh-007.github.io/Portfolio/)

<div align="center">

*`// system: AnonymousSingh-007 · status: hunting for the structural failure condition`*

</div>
