# thexin7

🇹🇼 Taiwan

This profile documents independent, authorized research and engineering practice in Windows kernel security, sandbox isolation, hypervisor research (VT-x/EPT, AMD-V/SVM), reverse engineering, and anti-cheat security.

Some projects reproduce attacker and anti-analysis techniques in controlled lab environments so their behavior can be measured, detected, and mitigated. Public repositories are personal research and study material; they do not by themselves establish employment or ownership of upstream work.

---

### What I'm into

- Kernel / hypervisor internals (WDM, KMDF, EPT, SVM)
- How cheats and anti-analysis techniques affect a client, and what detection can realistically see
- Sandbox and isolation attack surface on Windows
- Suspicious-driver triage and reverse engineering

Personal research only — not speaking for any employer.

---

### 🧪 Featured original work — [MalDrvAnalyzer](https://github.com/thexin7/MalDrvAnalyzer)

My own public project: a **C++ Windows driver-analysis and process-introspection toolkit** used in my professional anti-cheat and product-security work. It walks loaded drivers, classifies suspicious kernel routines, and inspects processes to build **detection telemetry and validation tests** — strictly for authorized defensive analysis on corporate, isolated-lab infrastructure.

It deliberately studies how offensive techniques present to defenders (callback tampering, DKOM, token manipulation, hypervisor-assisted concealment, sandbox escape) so the observable behavior can be **detected, verified, and mitigated**. I do **not** publish offensive tooling or attack third-party systems: the output is detections, mitigations, and hardening guidance.

Related defensive writing lives in [kernel-cve-analysis](https://github.com/thexin7/kernel-cve-analysis): **analysis notes** on publicly-disclosed Windows kernel EoP issues (afd.sys, cng.sys, appid.sys BYOVD) from an anti-cheat / EDR telemetry and hardening standpoint. Consolidated into this public repo in August 2026.

### Projects

| Attribution              | Repo                                                                        | Scope                                  |
| ------------------------ | --------------------------------------------------------------------------- | -------------------------------------- |
| Original project         | [MalDrvAnalyzer](https://github.com/thexin7/MalDrvAnalyzer)                 | Suspicious-driver triage and kernel RE |
| Defensive analysis notes | [kernel-cve-analysis](https://github.com/thexin7/kernel-cve-analysis)       | Defensive analysis of public kernel CVEs |
| Study/reference mirror   | [SandboxiePlus](https://github.com/thexin7/SandboxiePlus)                   | Process isolation research             |
| Study/reference mirror   | [Sandboxie-Classic](https://github.com/thexin7/Sandboxie-Classic)           | Classic Sandboxie lineage study        |
| Study/reference mirror   | [Sandbox-AttackSurface](https://github.com/thexin7/Sandbox-AttackSurface)   | Sandbox attack-surface analysis        |
| Study/reference mirror   | [HyperHide-Research](https://github.com/thexin7/HyperHide-Research)         | Hypervisor anti-anti-debug study       |
| Study/reference mirror   | [SimpleSvmHook-Research](https://github.com/thexin7/SimpleSvmHook-Research) | AMD SVM hypervisor and hooks study     |
| Study/reference mirror   | [EPT-Hook-Check](https://github.com/thexin7/EPT-Hook-Check)                 | EPT hook detection and integrity study |

<p>
  <a href="https://github.com/thexin7/SandboxiePlus"><img src="https://github-readme-stats.shion.dev/api/pin/?username=thexin7&repo=SandboxiePlus&theme=tokyonight&hide_border=true" height="140" /></a>
  <a href="https://github.com/thexin7/Sandbox-AttackSurface"><img src="https://github-readme-stats.shion.dev/api/pin/?username=thexin7&repo=Sandbox-AttackSurface&theme=tokyonight&hide_border=true" height="140" /></a>
</p>
<p>
  <a href="https://github.com/thexin7/HyperHide-Research"><img src="https://github-readme-stats.shion.dev/api/pin/?username=thexin7&repo=HyperHide-Research&theme=tokyonight&hide_border=true" height="140" /></a>
  <a href="https://github.com/thexin7/SimpleSvmHook-Research"><img src="https://github-readme-stats.shion.dev/api/pin/?username=thexin7&repo=SimpleSvmHook-Research&theme=tokyonight&hide_border=true" height="140" /></a>
</p>

---

### Stack

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![x86/x64](https://img.shields.io/badge/x86%2Fx64_Assembly-525252?style=flat)
![WDM/KMDF](https://img.shields.io/badge/Windows_Kernel-WDM%2FKMDF-0078D4?style=flat&logo=windows&logoColor=white)
![VT-x/EPT](https://img.shields.io/badge/Hypervisor-VT--x%2FEPT%2FSVM-0071C5?style=flat&logo=intel&logoColor=white)
![Anti-Cheat](https://img.shields.io/badge/Anti--Cheat_Security-critical?style=flat)
![IDA](https://img.shields.io/badge/IDA_Pro-4B0082?style=flat)
![WinDbg](https://img.shields.io/badge/WinDbg-0078D4?style=flat&logo=windows&logoColor=white)

---

### Right now

- EPT view switching and hook detection ideas
- Windows sandbox / isolation edges
- Anti-cheat questions on the client side
- Repeatable reverse-engineering workflows with IDA and WinDbg

---

### Contact

[github.com/thexin7](https://github.com/thexin7)
