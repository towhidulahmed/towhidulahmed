# Towhidul Ahmed

**SOC Analyst | Blue Team Defender | Security Researcher**

M.Sc. in Electrical Engineering & IT (Security Focus) — Cologne, Germany

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/towhidulahmed)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%205%25-212C42?style=flat&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/ahmedtowhid00)
[![GitHub](https://img.shields.io/badge/GitHub-towhidulahmed-181717?style=flat&logo=github&logoColor=white)](https://github.com/towhidulahmed)
[![Website](https://img.shields.io/badge/towhid.info-333333?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAC3klEQVR42o1TW0tUYRRd33fmzMUZh9TR7CalY41jo6UZmdFoPXSl6EpFFES9Vb4U9FLHfkIQ9dxDJUZFYJBJQZIXSEgDC1PTROeSqeg4njMz5/t2D5akSLSeNnvvtTbsvTYwBxbUgpagFrRgERjYfBzUghZN0/jC+hKE5+8frmzqbfbHWbwq3Bcqcnvdz25eqH25ie2J/8WjeYGG6F1XR+fHA2JG2WmYqbLeqV6/Ad1t9Vgx9nQcet8scrZ4BrLXZdUvK0h/9PhU42cpJQNACgCU7QlslyprrMnfV5GRkbW68UejLZyIyOlkTPisfvJTMcJfo1k/w5M79Ujyku+Q1/7t3fe3OAGFA4BT2COGmE1aFaupkiqW8QySQvBCR6FlW26lEk5E+K4duyQbgaGPGtZEysgFgKA/yDgAXLHVDemzs6MTiTELiJjKFaYIBXnmOrR0tuB18xv09/dxf0mxRWc6OTLsnX92xqGB8xrFcMD+5cNEGzom28lkKaikYjw0DikFMj1uTMWmkUoKxelyMGe2rRcAcopziGvVGidI5LnXvh0I9eHTQDfZDRvSxpyYbp/BcrkGR/afRF6el4ykyUxmTsTSYz0A8OTEE8nrqiEB4GDF3iZnNN0M3Q8rP+9NUqx+BhQHUkkTZ46fwubyUpnw6OAFSlfzsfYfvy9OnLHbEhp4gauix1uQ3+5ZnwkYJMkQAAkImcL7tlaEhyPksqcjjTle/TaVMrcDAA3FDYwxRlVFVXdWleQyNdtKDpcDAIOqqhgcHaToRJRbdZtwDNlfAEA1quUCB2qaxomI36y/9mbLyQD5fN5kIOCj8gOlFLjsS5beKqId18sezDVj3s4LvM8Yk5P60MVQeKS1O9GzYqorJqUQQi1UVcRFxLmK3QCBoQ5L48+jtPY3bTx392jL1uMBKjnso9LbG4YrajdWLp7+TxHVouJ0w+7K8qu+8yVn83P+i7xYZGFyafIvxHo8VYERE38AAAAASUVORK5CYII=&logoColor=white)](https://www.towhid.info)

---

## About

SOC analyst with a focus on alert triage, log correlation, incident handling, and threat detection. Recent M.Sc. graduate with hands-on experience across SIEM operations, malware analysis, network forensics, and OT/embedded security.

My background spans reverse engineering firmware binaries, analyzing protocol-level vulnerabilities in embedded systems, and building detection signatures for known CVEs. I work primarily with Splunk, Elastic Stack, Wazuh, Ghidra, and Wireshark.

---

## Projects

### [OT Firmware Vulnerability Detection](https://github.com/towhidulahmed/ot-firmware-vulnerability-detection)
Detection system for identifying known CVEs in OT firmware binaries without source code access. Uses YARA signature scanning (76.7% accuracy, 0% false positives, <10ms per scan) and Control Flow Graph isomorphism for cross-architecture matching. Detected CVE-2015-4590 across ARM Cortex-M4 and Xtensa targets using Ghidra.

### [Keygen Reverse Engineering](https://github.com/towhidulahmed/keygen-reverse-engineering)
Reversed a stripped x86-64 ELF binary to recover its serial validation logic. Identified the algorithm in Ghidra and reimplemented it in C to generate valid serial keys from arbitrary email addresses.

### [1-Wire Protocol Analysis](https://github.com/towhidulahmed/1wire-decoder-analysis)
Captured and decoded communication between an electronic key and lock system using a logic analyzer. Built a Python decoder for the proprietary protocol, identified weaknesses in static identifiers and checksums, and demonstrated a practical replay attack.

### [Vulnerability Assessment Lab](https://github.com/towhidulahmed/nessus-metasploit-audit)
Scanned Ubuntu 8.04.x with Nessus, documented 71 vulnerabilities, and validated critical findings with Metasploit. Includes remediation steps and exploitability analysis.

### [Malware Traffic Analysis Write-up](https://github.com/towhidulahmed/malware-traffic-analysis-2025-01-22/)
PCAP analysis of a real-world malware sample. Identified infected hosts, phishing infrastructure, and C2 communication through Wireshark and protocol forensics.

---

## Research

### 🏅 Master's Thesis - Grade: 1.0 (German scale)
**Automated Detection of Vulnerable Firmware in OT Devices** *(Apr 2025 – Sep 2025)*

Built a signature-based detection system to find known CVEs in unpacked firmware images. Reverse-engineered STM32 firmware in Ghidra, extracted machine code signatures, and wrote YARA rules that detected CVE-2015-4590 in 23 of 30 vulnerable builds with no false positives. Also implemented CFG-based detection using graph isomorphism across ARM and Xtensa architectures.

### Research Project
**Security Analysis of Mechatronic Locking Systems via the 1-Wire Protocol** *(May 2024 – Jul 2024)*

Captured and decoded key-lock communication with a logic analyzer. Built Python tooling to parse the protocol at the bit level, identified weaknesses (static IDs, predictable checksums), and demonstrated replay attacks. Analyzed protocol timing for potential cryptographic countermeasures.

---

## Skills

| Area | Tools & Technologies |
|---|---|
| **SIEM & Detection** | Splunk, Elastic Stack (ELK), Wazuh, MISP, OpenCTI, MITRE ATT&CK |
| **Malware Analysis** | Ghidra, YARA, sandbox environments, Windows Internals, ARM Assembly |
| **Network Analysis** | Wireshark, Zeek, Nmap, Snort, TShark, BRIM, NetworkMiner |
| **OT / Embedded** | Binwalk, Logic Analyzer, Oscilloscope, ST-Link, OpenOCD, 1-Wire, I2C |
| **Programming** | Python, C, Bash |
| **Platforms** | Kali Linux, Ubuntu, Windows, VirtualBox, VMware, Microsoft Azure, Git |

---

## Certifications

| Certification | Provider |
|---|---|
| Blue Team Junior Analyst | Security Blue Team |
| TryHackMe — Top 5% Worldwide (Dec 2025) | TryHackMe |
| Reverse Engineering und Forensics | University of Rostock |
| Vulnerability Management with Nessus | LinkedIn Learning |
| Security Testing: Nmap Security Scanning | LinkedIn Learning |
| Azure: Virtual Machine & Web Server Deployment | Coursera |
| IT Technical Support Fundamentals | Coursera |
| A Deep Dive into SSL and TLS | Udemy |
| Machine Learning with Python | Coursera / IBM |
| Neural Networks and Deep Learning | Coursera |

[View all certificates](https://github.com/towhidulahmed/certificates)

---

## Badges

<table>
  <tr>
    <td align="center" colspan="5">
      <a href="https://tryhackme.com/p/ahmedtowhid00">
        <img src="https://tryhackme-badges.s3.amazonaws.com/ahmedtowhid00.png?v=3" alt="TryHackMe Profile" height="90">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/network-fundamentals">
        <img src="https://assets.tryhackme.com/room-badges/658d614d6c824a39f389c10a394c4875.png" alt="Network Fundamentals" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/web-fund">
        <img src="https://assets.tryhackme.com/room-badges/db2e637ff7ff8250aa01c042ccd6146a.png" alt="Web Fundamentals" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/world-wide-web">
        <img src="https://assets.tryhackme.com/room-badges/306a66a85804b90812df34a3f4d27448.png" alt="World Wide Web" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/terminaled">
        <img src="https://assets.tryhackme.com/room-badges/0799aa79b4e9c4dca44013de4d3ca1a7.png" alt="Terminaled" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/intro-to-pentesting">
        <img src="https://assets.tryhackme.com/room-badges/93a785207d320429097a595221e7f648.png" alt="Intro to Pentesting" height="90">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/skilled-navigator">
        <img src="https://assets.tryhackme.com/room-badges/a979903ebd4eb535c44d8bb5b67e67ca.png" alt="Skilled Navigator" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/bronze-league">
        <img src="https://assets.tryhackme.com/room-badges/000f8418e03d19db74d2ec8fe3b6a2fd.png" alt="Bronze League" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/friday-fixer">
        <img src="https://assets.tryhackme.com/room-badges/b5149d12f3f00c25cd92aa20b96dadb6.png" alt="Friday Fixer" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/advent-of-cyber-2025">
        <img src="https://assets.tryhackme.com/room-badges/bb668b2c07c714c34beeb807ec17a023.png" alt="Advent of Cyber 2025" height="90">
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://tryhackme.com/ahmedtowhid00/badges/defensive-toolsmith">
        <img src="https://assets.tryhackme.com/room-badges/527646fd75c6fef729dd39ab074ff85d.png" alt="Defensive Toolsmith" height="90">
      </a>
    </td>
  </tr>
</table>

---

## Languages

| Area | Details |
|---|---|
| **Bengali** | Native |
| **English** | Fluent (C1) |
| **German** | A2 (actively developing) |
