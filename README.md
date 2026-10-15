<div align="center">

<img
  src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=00FF41&center=true&vCenter=true&width=600&height=45&lines=access+granted;skandar+hadrich;a.k.a.+0xmrerror;malware+analysis+%2F+reverse+engineering;breaks+things%2C+then+documents+them"
  alt="Skandar Hadrich — malware analysis, reverse engineering, SOC automation"
/>

<p>
  <a href="https://0xmrerror.me"><img src="https://img.shields.io/badge/site-0xmrerror.me-00FF41?style=for-the-badge&labelColor=0d1117" alt="Website: 0xmrerror.me" /></a>
  <a href="https://www.linkedin.com/in/skandar-hadrich-128221369/"><img src="https://img.shields.io/badge/linkedin-skandar__hadrich-00FF41?style=for-the-badge&labelColor=0d1117" alt="LinkedIn: skandar hadrich" /></a>
  <a href="mailto:skandar.hadrich@etudiant-enit.utm.tn"><img src="https://img.shields.io/badge/email-skandar.hadrich-00FF41?style=for-the-badge&labelColor=0d1117" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=skandarhadrich-cell&label=IP_LOGS&color=00ff41&style=for-the-badge" alt="Profile views" />
</p>

</div>

```console
$ whoami --verbose

  operator      : skandarhadrich-cell
  callsign      : 0xmrerror
  role          : malware analysis, reverse engineering, SOC automation
  focus         : nested-VM sandboxes, eBPF hypervisor telemetry, ML for security
  affiliation   : ENIT — ICT Engineering, Tunis
  ranking       : top 1% TryHackMe globally · 77th, HTB University CTF 2025
  currently     : a 9-stage pipeline that detonates samples so you don't have to
  seeking       : 6-month security internship from February 2027
  status        : learning in public, permanently

$ _
```

---

## Current Operations

| | |
|:--|:--|
| **Building** | An end-to-end malware analysis pipeline — QEMU/KVM live detonation, host-side eBPF syscall tracing, Volatility3 VMI correlation, automated MITRE ATT&CK attribution |
| **Publishing** | Write-ups and CTF notes at [0xmrerror.me](https://0xmrerror.me) — the dead ends included |
| **Studying** | Detection engineering, adversarial ML, and the gap between a sample that runs and an alert that fires |
| **Open to** | A 6-month security internship starting February 2027 — systems security, binary analysis, or AI security |

---

## Arsenal

<div align="center">

**Offense and Defense**

<img src="https://skillicons.dev/icons?i=linux,bash,kali,git,vim&theme=dark" alt="Linux, Bash, Kali, Git, Vim" />

**Languages**

<img src="https://skillicons.dev/icons?i=python,cpp,c,cs,dotnet&theme=dark" alt="Python, C++, C, C#, .NET" />

**Automation and Intelligence**

<img src="https://skillicons.dev/icons?i=docker,ansible,pytorch&theme=dark" alt="Docker, Ansible, PyTorch" />

</div>

<details>
<summary><b>What that actually means in practice</b></summary>

<br />

| Domain | Where it has been applied |
|:--|:--|
| Reverse engineering | Ghidra, angr, GDB, Frida — stripped ELF/PE triage, symbolic CFG analysis, anti-debug defeat (PEB flags, timing checks, NtQueryInformationProcess) |
| Malware analysis | Nested QEMU/KVM detonation with concurrent eBPF tracing, Volatility3 VMI, Speakeasy emulation, C2 sinkholing with iptables + DNSChef + INetSim, anti-sandbox `KUSER_SHARED_DATA` patching |
| SOC / blue team | Wazuh SIEM, ELK, Shuffle SOAR, custom detection rules mapped to MITRE ATT&CK — 33,022 noisy events filtered down to 1 actionable incident |
| ML for security | Graph neural networks (GCN/GAT) for malicious-function localization, Double DQN for intrusion response, MinHash/LSH malware-family clustering |
| Systems | C/C++ and x86/ARM assembly when the answer is in memory, eBPF when it is in the kernel, Python when the deadline is today |

</details>

---

## Featured Work

| Project | What it does |
|:--|:--|
| [Nested-VM Malware Analysis Pipeline](https://github.com/skandarhadrich-cell/-Nested-VM-Malware-Analysis-Pipeline-with-eBPF-Monitoring) | 9-stage sandbox: static triage → live KVM detonation with eBPF + VMI telemetry → IOC extraction, threat-intel pivoting, ATT&CK mapping, PDF reports. Validated against AsyncRAT, AgentTesla and njRAT |
| [Open-Source SOC Automation](https://github.com/skandarhadrich-cell/Automation-of-Deployment-and-Detection-Engineering-in-an-Open-Source-SOC-Environment) | Wazuh + Shuffle SOAR deployed with Ansible/Docker; a Python suppression microservice cuts 33,022 noisy events down to a single incident |
| [RL Intrusion Detection & Response](https://github.com/skandarhadrich-cell/RL-Based-Intrusion-Detection-Project) | Double DQN with prioritized experience replay in a custom Gymnasium environment — six response actions, trained on CSE-CIC-IDS2018 telemetry |
| [CFG Localization via GNNs](https://github.com/skandarhadrich-cell/CFG-Function-Localization-via-Graph-Neural-Networks) | GCN/GAT node classification of malicious functions in control-flow graphs extracted from stripped binaries with headless Ghidra + angr |
| [HIDS/NIDS — ELK, Prometheus, Grafana](https://github.com/skandarhadrich-cell/Network-Intrusion-Detection-System-HIDS-NIDS-with-ELK-Stack-Prometheus-Grafana) | Full detection stack: host and network intrusion detection wired into ELK with Prometheus metrics and Grafana dashboards |
| [Village Under Attack](https://github.com/skandarhadrich-cell/Village-under-attack) | Real-time terminal strategy game in C++ — OOP, non-blocking I/O, NPC pathfinding, collision detection |

Full walkthroughs and CTF write-ups on the [website](https://0xmrerror.me).

---

## Telemetry

<div align="center">

<img
  src="https://ghchart.rshah.org/00FF41/skandarhadrich-cell"
  width="100%"
  alt="Contribution heatmap"
/>

<img
  src="https://streak-stats.demolab.com?user=skandarhadrich-cell&hide_border=true&border_radius=10&background=0D1117&ring=00FF41&fire=00FF41&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00FF41&sideLabels=FFFFFF&dates=8B949E&cardBorder=30363D&cardBg=0D1117"
  alt="Contribution streak"
/>

</div>

<!--
  GitHub stats cards go here once the public instance is back.
  The shared github-readme-stats.vercel.app instance is frequently paused (503),
  so it renders as a broken image for everyone. To restore:
    1. Fork https://github.com/anuraghazra/github-readme-stats
    2. Import the fork into Vercel, set a PAT_1 environment variable
    3. Swap the domain below, then delete these comment markers

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=skandarhadrich-cell&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=skandarhadrich-cell&layout=compact&locale=en&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="Most used languages" />
</div>
-->

---

## Establish Connection

<div align="center">

<a href="https://0xmrerror.me"><img src="https://img.shields.io/badge/Website-00FF41?style=for-the-badge&logo=googlechrome&logoColor=black&labelColor=0d1117" alt="Website: 0xmrerror.me" /></a>
<a href="https://www.linkedin.com/in/skandar-hadrich-128221369/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn: skandar hadrich" /></a>
<a href="mailto:skandar.hadrich@etudiant-enit.utm.tn"><img src="https://img.shields.io/badge/Email-00FF41?style=for-the-badge&logo=gmail&logoColor=black&labelColor=0d1117" alt="Email" /></a>

<br /><br />

<i>"I break websites and reverse binaries for a living — and write down exactly how."</i>

<sub>Available for a 6-month security internship from February 2027. The email is the fastest route.</sub>

</div>
