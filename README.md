# thexin7

🇹🇼 Taiwan · [thexix996@gmail.com](mailto:thexix996@gmail.com)

I work on Windows internals: kernel drivers, sandbox/isolation, hypervisors (VT-x/EPT, AMD-V/SVM), reverse engineering, and defensive anti-cheat for PC clients.

Repos here are mostly notes and experiments from that work — reading drivers, tracing isolation edges, and poking at hypervisor tricks until the behavior makes sense.

Tools I actually use: IDA, WinDbg, x64dbg, and Claude Code.

---

### What I'm into

- Kernel / hypervisor guts (WDM, KMDF, EPT, SVM)
- How cheats abuse the client, and what detection can realistically see
- Sandbox and isolation attack surface on Windows
- Malicious / suspicious driver triage

Personal research only — not speaking for any employer.

---

### Projects

| Focus | Repo | Notes |
|------|------|--------|
| Driver triage | [MalDrvAnalyzer](https://github.com/thexin7/MalDrvAnalyzer) | Analyzer for suspicious drivers |
| Classic sandbox | [Sandboxie-Classic](https://github.com/thexin7/Sandboxie-Classic) | Process isolation research |
| Attack surface | [Sandbox-AttackSurface](https://github.com/thexin7/Sandbox-AttackSurface) | Tooling around sandbox edges |
| Hypervisor RE | [HyperHide-Research](https://github.com/thexin7/HyperHide-Research) | Anti-anti-debug via hypervisor |
| AMD SVM | [SimpleSvmHook-Research](https://github.com/thexin7/SimpleSvmHook-Research) | Small research hypervisor / hooks |
| EPT hooks | [EPT-Hook-Check](https://github.com/thexin7/EPT-Hook-Check) | Looking for EPT hooks |

<p>
  <a href="https://github.com/thexin7/MalDrvAnalyzer"><img src="https://github-readme-stats.shion.dev/api/pin/?username=thexin7&repo=MalDrvAnalyzer&theme=tokyonight&hide_border=true" height="140" /></a>
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
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat)
![IDA](https://img.shields.io/badge/IDA_Pro-4B0082?style=flat)
![WinDbg](https://img.shields.io/badge/WinDbg-0078D4?style=flat&logo=windows&logoColor=white)

---

### Right now

- EPT view switching and hook detection ideas
- Windows sandbox / isolation edges
- Anti-cheat questions on the client side
- Faster RE loops with Claude Code + WinDbg MCP

---

### Contact

| | |
|--|--|
| GitHub | [github.com/thexin7](https://github.com/thexin7) |
| Email | [thexix996@gmail.com](mailto:thexix996@gmail.com) |
| Location | Taiwan |
