# Awesome-Cybersecurity-Training-Reverse-Engineering

## Top Cybersecurity Training & Reverse Engineering Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Hands-On Labs, Reverse Engineering Toolchains & Cyber Range Exercises*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cybersecurity Training & Reverse Engineering**. These tools enable security analysts, penetration testers, and SOC teams to develop practical skills through hands-on labs, live-fire exercises, and reverse engineering toolchains—from individual practice environments to enterprise-grade cyber ranges.

**Examples** include Mandiant Advantage, OffSec Proving Grounds, Hack The Box Enterprise, TryHackMe Business, Cybrary for Business, Immersive Labs, SANS OnDemand, RangeForce, SimSpace, and Pentester Academy (the category leaders).

**Open-source emphasis**: This section is heavily expanded with major active projects for self-hosting, reverse engineering toolchains, and open training platforms—ideal for security practitioners, educators, and organizations seeking transparent, vendor-independent cybersecurity training.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The dedicated global cybersecurity training and cyber range market is estimated at **$7.0B–$7.7B** (growing at an estimated 16.8%–18.6% CAGR, within a macro security services sector surpassing $300B). The sector is **moderately fragmented**: high enterprise concentration exists at the top among certification/defense conglomerates (SANS, Google/Mandiant, Cyberbit), while intense fragmentation continues across mid-market and niche spaces with specialized interactive lab platforms (Hack The Box, TryHackMe, SimSpace, Immersive Labs) competing for workforce reskilling and live-fire cyber drill demand.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description & Core Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Mandiant Advantage](https://www.mandiant.com/advantage)** | **$5.4B** (Acquired by Google; ~$483M LTM revenue) | Custom enterprise starting ~$200,000/yr (or ~$650/hr for discrete assessment units) | Free Community Threat Intelligence tier (limited threat actor profiles, IOCs, and CVE views) plus 14-day higher-tier feature evaluation | Comprehensive threat intelligence, attack surface management, and Mandiant Academy / ThreatSpace cyber range simulations. |
| **[SANS OnDemand](https://www.sans.org/)** | **~$360M** est. annual revenue (Privately held, employee-owned) | Starting **$5,000–$7,000** per self-paced course (includes 4 months / 120 days access) | No free full-course tier; provides 55+ free course preview modules/excerpts (SEC275, SEC301, SEC401, FOR500) | The premier gold-standard cybersecurity certification and training catalog, with GIAC exam pathways and NetWars cyber challenges. |
| **[Immersive Labs](https://www.immersivelabs.com/)** | **$250M–$500M** valuation (~$90M est. annual revenue; $180M+ funded) | Annual contracts starting at **~$4,820/yr** (median enterprise deployments ~$44,250/yr) | 3-month (90 days) free enterprise evaluation trial (free access to selected entry paths via Cyber Million program) | People-centric cyber resilience with AI-powered Lab Builder, practical organization tool validations, and crisis drills. |
| **[Hack The Box Enterprise](https://www.hackthebox.com/)** | **$250M–$500M** valuation (~$10M–$50M ARR; $70M+ funded) | Individual VIP+ at **$25/mo** ($223/yr); Academy tiers start at **$10/mo**; Team Build tier starts at **$250/seat/mo** | Permanent free tier with limited active machines and 24 hours/mo Pwnbox access; Dedicated enterprise labs offer demo trial on request | Dedicated corporate labs, customizable machine uploads, isolated attack surfaces, MITRE ATT&CK alignment, and talent recruiting. |
| **[SimSpace](https://simspace.com/)** | **~$100M+** valuation ($50M+ ARR trajectory; $109M+ funded) | Enterprise cyber ranges starting at **~$25,000/yr** (modular use-case based pricing) | No self-serve trial; offers custom proof-of-concept / guided live-fire range demo trial upon sales qualification | High-fidelity digital-twin cyber ranges with L1–L3 attack emulation, ARIA automated range generation, and live-fire defense drills. |
| **[Cybrary for Business](https://www.cybrary.it/)** | **~$100M** valuation ($52M+ funded) | Teams plan starting at **$79/mo** (billed annually) | 7-day free trial for individual/team access; permanent free tier with basic baseline assessments and limited course catalog | Skill gap baselining, Cyber Risk Impact scoring, CVE threat actor simulations (APT35, APT41), and custom learning paths. |
| **[RangeForce (Cyberbit)](https://www.cyberbit.com/rangeforce/)** | **~$100M+** combined valuation ($40M+ VC prior to Sep 2025 acquisition by Cyberbit) | Entry enterprise packages starting at **~$3,000–$5,000/yr** | Permanent free edition with solo hands-on skills labs and introductory threat mitigation modules | Live-fire SOC team readiness exercises (host of NATO Locked Shields), solo cloud labs, and blue team breach scenarios. |
| **[OffSec Proving Grounds](https://www.offsec.com/products/proving-grounds/)** | **~$20M–$50M** est. revenue (Acquired by Leeds Equity Partners, 2024) | PG Practice at **$19/mo** or **$199/yr**; Learn One at **$2,599/yr** | PG Play permanent free tier with 50+ VulnHub machines capped at 3 daily hours (1 concurrent machine) | Realistic hands-on penetration testing labs, retired OSCP+ exam machines, and in-browser Kali Linux attack stations. |
| **[TryHackMe Business](https://tryhackme.com/)** | **~$10M+** ARR (Self-sustained/bootstrapped) | Individual Premium starts at **$14/mo** ($126/yr); EDU licenses at **$30/seat/mo**; Business custom quotes (min. 5 seats) | Permanent free account with access to hundreds of free introductory rooms and 1 hour/day in-browser AttackBox access | Gamified cybersecurity training with guided paths, custom CTF builders, cloud labs, and team progress analytics. |
| **[Pentester Academy](https://www.pentesteracademy.com/)** | **Sub-$20M** (Acquired by INE in 2021) | Annual subscription starting at **$249/yr**; Bootcamp cohorts from **$299–$499** | Free community taster labs (90+ browser-based terminal labs via AttackDefense / INE Skill Dive) | On-demand bootcamps and 2,000+ browser-based labs covering OWASP Top 10, Active Directory attacks, and x86/x64 assembly. |

## Open-Source GitHub Projects

| Project | Stars | Focus Area | Description |
| :--- | :--- | :--- | :--- |
| **[x64dbg](https://github.com/x64dbg/x64dbg)** | [![GitHub stars](https://img.shields.io/github/stars/x64dbg/x64dbg?style=social&color=white)](https://github.com/x64dbg/x64dbg/stargazers) | Dynamic Analysis & Debugging | An open-source x64/x32 debugger for Windows. Features an intuitive Qt GUI, TitanEngine abstraction, scriptable automation, and an extensive plugin ecosystem. |
| **[Ghidra](https://github.com/NationalSecurityAgency/ghidra)** | [![GitHub stars](https://img.shields.io/github/stars/NationalSecurityAgency/ghidra?style=social&color=white)](https://github.com/NationalSecurityAgency/ghidra/stargazers) | Static Analysis & Decompilation | NSA's software reverse engineering framework (Apache-2.0). The industry-standard open-source RE suite including disassembler, decompiler, graphing, and Java/Python scripting. |
| **[radare2](https://github.com/radareorg/radare2)** | [![GitHub stars](https://img.shields.io/github/stars/radareorg/radare2?style=social&color=white)](https://github.com/radareorg/radare2/stargazers) | Multi-Architecture RE Framework | Portable reverse engineering framework and commandline toolset. Supports disassembly, debugging, binary patching, and forensics across dozens of architectures and OSes. |
| **[Cutter](https://github.com/rizinorg/cutter)** | [![GitHub stars](https://img.shields.io/github/stars/rizinorg/cutter?style=social&color=white)](https://github.com/rizinorg/cutter/stargazers) | GUI for Reverse Engineering | Free and open-source RE platform powered by Rizin. Features an advanced decompiler (Ghidra decompiler integration), graph views, hex editor, and Python plugin support. |
| **[pwntools](https://github.com/Gallopsled/pwntools)** | [![GitHub stars](https://img.shields.io/github/stars/Gallopsled/pwntools?style=social&color=white)](https://github.com/Gallopsled/pwntools/stargazers) | CTF & Exploit Development | CTF framework and exploit development library in Python. Designed for rapid prototyping, binary patching, ELF manipulation, ROP chain generation, and remote socket interaction. |
| **[Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)** | [![GitHub stars](https://img.shields.io/github/stars/redcanaryco/atomic-red-team?style=social&color=white)](https://github.com/redcanaryco/atomic-red-team/stargazers) | Adversary Emulation & Cyber Range | Library of simple, open-source automated tests mapped directly to the MITRE ATT&CK framework, allowing security teams to test controls and train defenders against real tactics. |
| **[pwndbg](https://github.com/pwndbg/pwndbg)** | [![GitHub stars](https://img.shields.io/github/stars/pwndbg/pwndbg?style=social&color=white)](https://github.com/pwndbg/pwndbg/stargazers) | Exploit Engineering & GDB Plug-in | Python GDB plug-in making debugging with GDB intuitive for reverse engineers and exploit developers, with heap introspection, context displays, and memory analysis. |
| **[FLARE VM](https://github.com/mandiant/flare-vm)** | [![GitHub stars](https://img.shields.io/github/stars/mandiant/flare-vm?style=social&color=white)](https://github.com/mandiant/flare-vm/stargazers) | Malware Analysis Ecosystem | Fully customizable, Windows-based security distribution for malware analysis, reverse engineering, and incident response created and maintained by Mandiant. |
| **[angr](https://github.com/angr/angr)** | [![GitHub stars](https://img.shields.io/github/stars/angr/angr?style=social&color=white)](https://github.com/angr/angr/stargazers) | Symbolic Execution & Binary Analysis | Python framework for analyzing binaries. Combines static and dynamic symbolic execution (concolic analysis) for automated vulnerability discovery and deobfuscation. |
| **[GEF](https://github.com/hugsy/gef)** | [![GitHub stars](https://img.shields.io/github/stars/hugsy/gef?style=social&color=white)](https://github.com/hugsy/gef/stargazers) | GDB Exploit Framework | Multi-architecture GDB extension designed for dynamic binary analysis, exploit writers, and reverse engineers with visual memory inspection and architecture registers. |
| **[Commando VM](https://github.com/mandiant/commando-vm)** | [![GitHub stars](https://img.shields.io/github/stars/mandiant/commando-vm?style=social&color=white)](https://github.com/mandiant/commando-vm/stargazers) | Red Team & Penetration Testing | Windows-based penetration testing virtual machine distribution using Chocolatey packages, delivering a complete penetration testing and red teaming environment. |
| **[CALDERA](https://github.com/mitre/caldera)** | [![GitHub stars](https://img.shields.io/github/stars/mitre/caldera?style=social&color=white)](https://github.com/mitre/caldera/stargazers) | Automated Cyber Range & Emulation | Scalable automated adversary emulation platform built on the MITRE ATT&CK framework by MITRE, designed for autonomous blue team training and security testing. |
| **[CTFd](https://github.com/CTFd/CTFd)** | [![GitHub stars](https://img.shields.io/github/stars/CTFd/CTFd?style=social&color=white)](https://github.com/CTFd/CTFd/stargazers) | Cyber Training & CTF Platform | The leading open-source capture-the-flag platform. Easy to deploy, highly customizable with plugins and themes, used globally for cybersecurity training competitions. |
| **[capa](https://github.com/mandiant/capa)** | [![GitHub stars](https://img.shields.io/github/stars/mandiant/capa?style=social&color=white)](https://github.com/mandiant/capa/stargazers) | Capability Detection & Triage | Mandiant's open-source tool that identifies capabilities in executable files using community-curated rules, automatically telling you what a program can do (e.g., inject code, steal credentials). |
| **[Cuckoo Sandbox](https://github.com/cuckoosandbox/cuckoo)** | [![GitHub stars](https://img.shields.io/github/stars/cuckoosandbox/cuckoo?style=social&color=white)](https://github.com/cuckoosandbox/cuckoo/stargazers) | Automated Malware Sandbox | Leading automated malware analysis system. Throws suspicious files into isolated VM sandboxes and produces comprehensive behavioral execution traces. |
| **[Volatility 3](https://github.com/volatilityfoundation/volatility3)** | [![GitHub stars](https://img.shields.io/github/stars/volatilityfoundation/volatility3?style=social&color=white)](https://github.com/volatilityfoundation/volatility3/stargazers) | Memory Forensics & Incident Response | The world's most widely used memory forensics framework for extracting digital artifacts from volatile RAM memory samples of Windows, Linux, and macOS systems. |
| **[Rizin](https://github.com/rizinorg/rizin)** | [![GitHub stars](https://img.shields.io/github/stars/rizinorg/rizin?style=social&color=white)](https://github.com/rizinorg/rizin/stargazers) | Binary Analysis Engine | UNIX-like reverse engineering framework and commandline toolset, focused on usability, clean APIs, and modular disassembler/debugger integration. |
| **[Autopsy](https://github.com/sleuthkit/autopsy)** | [![GitHub stars](https://img.shields.io/github/stars/sleuthkit/autopsy?style=social&color=white)](https://github.com/sleuthkit/autopsy/stargazers) | Digital Forensics Training Platform | Premier end-to-end digital forensics platform and graphical interface to The Sleuth Kit. Used by law enforcement, military, and corporate examiners worldwide. |
| **[mcsema](https://github.com/trailofbits/mcsema)** | [![GitHub stars](https://img.shields.io/github/stars/trailofbits/mcsema?style=social&color=white)](https://github.com/trailofbits/mcsema/stargazers) | Binary Translation & Lifting | Framework for lifting machine code to LLVM bitcode. Translates x86, amd64, and AArch64 program binaries into LLVM IR for binary analysis and transformation. |
| **[Manalyze](https://github.com/JusticeRage/Manalyze)** | [![GitHub stars](https://img.shields.io/github/stars/JusticeRage/Manalyze?style=social&color=white)](https://github.com/JusticeRage/Manalyze/stargazers) | Static PE Malware Analyzer | Static code analyzer for PE executables that extracts strings, finds cryptographic algorithms, detects packers, and queries ClamAV and VirusTotal. |
| **[SentinelForge CTF](https://github.com/chadeckles/sentinelforgectf)** | [![GitHub stars](https://img.shields.io/github/stars/chadeckles/sentinelforgectf?style=social&color=white)](https://github.com/chadeckles/sentinelforgectf/stargazers) | Cloud & DevSecOps CTF | Self-hosted CTF platform focused on cloud security (Azure misconfigurations), container escapes, IaC flaws, and DevSecOps challenges with 5-minute Docker Compose setup. |
| **[PyX64Dbg](https://github.com/yoav-shamay/pyx64dbg)** | [![GitHub stars](https://img.shields.io/github/stars/yoav-shamay/pyx64dbg?style=social&color=white)](https://github.com/yoav-shamay/pyx64dbg/stargazers) | Pythonic Debugger for Linux | Python-based debugger for x86-64 Linux binaries using `ptrace` and `/proc`. Features a clean Python automation API, PySide6 GUI, and IPython CLI. |

### Additional Notable Platforms & Ecosystem Resources

- **[Übungszentrum Netzverteidigung 2.0 (BSI)](https://opencode.de)** — German Federal Office for Information Security (BSI) open-source cybersecurity training system and CAVE IaC range engine published on **OpenCode**.
- **[VulnHub](https://www.vulnhub.com/)** — Premier catalog of community-created vulnerable machines and images for hands-on offensive/defensive practice.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cybersecurity training and reverse engineering tools must be used **lawfully and ethically**. **Reverse engineering proprietary software may violate license agreements**; always verify authorization before analyzing third-party binaries.
- **Open-source reverse engineering is mature and production-grade.** Tools like Ghidra, x64dbg, Rizin/Cutter, and radare2 provide industry-grade disassembly, decompilation, and debugging capabilities.
- **Government-backed and open-source training infrastructure is widely accessible.** Platforms like BSI's Übungszentrum Netzverteidigung 2.0 and CTFd enable transparent, self-hosted cyber defense drills for teams of any size.
- **The training platform landscape serves diverse skill levels and budgets.** From community-accessible labs like TryHackMe and Hack The Box to high-fidelity live-fire simulation cyber ranges like SimSpace and RangeForce/Cyberbit.
- Training environments containing vulnerable machines or malware samples must be strictly network-isolated and sandboxed.

---

**Made for security analysts, penetration testers, and organizations building transparent cybersecurity training solutions.**  
Let's make Cybersecurity Training & Reverse Engineering more open, data-driven, and hands-on.
