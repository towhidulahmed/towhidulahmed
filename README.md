# Towhidul Ahmed

**Junior SOC Analyst | Blue Team | Security Researcher**  
*M.Sc. in Electrical Engineering & IT (IT & Security Focus)*  
📍 Cologne, Germany

---

SOC / Blue Team analyst focused on alert triage, log correlation, incident escalation, and threat detection. Recent M.Sc. graduate with hands-on experience in SIEM operations, malware analysis, network traffic analysis, and OT security.

I enjoy working with logs, hunting for suspicious patterns, and building clear investigation notes that help teams respond faster. My background includes reverse engineering embedded systems, analyzing firmware vulnerabilities, and understanding how devices communicate at the protocol level.

---

## What I'm Working On

**SOC & Blue Team Operations**  
Alert triage, log correlation, incident escalation, and basic threat hunting using SIEM platforms like Splunk, Elastic Stack, and Wazuh.

**Malware Analysis & Reverse Engineering**  
Static and dynamic analysis of malicious samples, behavior profiling, IOC extraction, and malware classification using Ghidra, sandboxes, and YARA rules.

**Network Traffic Analysis**  
Protocol analysis and detection of suspicious traffic using Wireshark, Zeek, Snort, and Nmap.

**OT/ICS Security**  
Firmware analysis and communication protocol review (1-Wire, I2C) in operational technology systems.

---

## Research & Academic Work

### 🏅 Master's Thesis — *April 2025 – September 2025* — **Grade: 1.0** (German grading scale)
**Automated Detection of Vulnerable Firmware in OT Devices**

Developed a signature-based system to automatically identify known CVEs in unpacked firmware images. Detected CVE-2015-4590 (ArduinoJson buffer overflow) in STM32 L476RG firmware with 76.7% accuracy via YARA signatures extracted from Ghidra. Explored Control Flow Graph isomorphism for cross-architecture vulnerability detection across STM32 and ESP8266 builds.

**Key achievements:**
- Reverse-engineered STM32 firmware with Ghidra, extracted 8-byte machine code signature for vulnerable function
- Developed YARA rules achieving 76.7% detection accuracy (23 of 30 vulnerable builds), 0% false positives
- Implemented CFG-based detection using graph isomorphism across ARM and Xtensa architectures

### Research Project — *May 2024 – July 2024*
**Security Analysis of Mechatronic Locking Systems Using the 1-Wire Protocol**

This project involved capturing and decoding communication between electronic keys and locks using a logic analyzer. I built Python tools to parse the protocol, identified weaknesses like static identifiers and predictable checksums, and demonstrated practical replay attacks. The research also explored cryptographic countermeasures through protocol timing analysis.

---

## Projects

### [Automated Detection of Vulnerable Firmware in OT Devices](https://github.com/towhidulahmed/ot-firmware-vulnerability-detection)

Automated detection system for identifying known CVEs in OT firmware binaries without source code access. Implemented dual detection approach: YARA signature-based scanning (76.7% accuracy, <10ms) and Control Flow Graph isomorphism for cross-architecture vulnerability identification. Successfully detected CVE-2015-4590 across ARM Cortex-M4 and Xtensa architectures using Ghidra.

### [Keygen Reverse Engineering Challenge](https://github.com/towhidulahmed/keygen-reverse-engineering)

Reverse engineered a stripped x86-64 ELF binary to understand its serial validation mechanism and created a working keygen. Used Ghidra to identify the algorithm that derives serial numbers from email addresses through mathematical operations. Reimplemented the validation logic in C to generate valid serials for any email address.

### [1-Wire Protocol Analysis & Attack Demo](https://github.com/towhidulahmed/1wire-decoder-analysis)

Captured embedded communication between an electronic key and lock system, then built a Python decoder to extract and analyze the protocol structure. Identified vulnerabilities in proprietary hardware protocols through bit-level timing analysis. Demonstrated how static identifiers enable forwarding attacks.

### [Bash Scripting Utilities](https://github.com/towhidulahmed/bash_scripting)

Collection of practical Bash scripts for automation and security workflows:
- **password_generator.sh** — Generates cryptographically strong passwords using OpenSSL
- **script_backup.sh** — Automates Git commits and pushes for quick version control

### [Vulnerability Assessment Lab](https://github.com/towhidulahmed/nessus-metasploit-audit)

Performed a comprehensive vulnerability scan on Ubuntu 8.04.x using Nessus, then followed up with Metasploit exploitation. Documented 71 vulnerabilities including critical backdoors and authentication issues. Includes detailed remediation recommendations and exploitability analysis—useful for learning vulnerability management workflows.

---

## Technical Skills

**SOC & Blue Team Operations**  
Alert triage · Log correlation · Incident escalation · Threat hunting  
Splunk · Elastic Stack (ELK) · Wazuh · MISP · OpenCTI · MITRE ATT&CK

**Malware Analysis & OS Internals**  
Static & dynamic analysis · Behavior profiling · IOC extraction  
Ghidra · Sandboxes · YARA rules · Windows Internals · ARM Assembly

**Network Traffic Analysis**  
Wireshark · Zeek · Nmap · Snort · TShark · BRIM · NetworkMiner

**OT / Embedded Security**  
Firmware extraction · Protocol analysis (1-Wire, I2C)  
Binwalk · Logic Analyzer · Oscilloscope · ST-Link · OpenOCD

**Programming & Scripting**  
Python · C · Bash scripting

**Systems & Platforms**  
Kali Linux · Ubuntu · Windows · VirtualBox · VMware · Microsoft Azure (fundamentals)  
Git / GitHub

---

## TryHackMe Profile

<p align="center">
  <a href="https://tryhackme.com/p/ahmedtowhid00" target="_blank">
    <img src="https://tryhackme-badges.s3.amazonaws.com/ahmedtowhid00.png?v=2" alt="TryHackMe Badge" />
  </a>
</p>

Ranked in the top 5% worldwide (December 2025) — hands-on labs covering penetration testing, privilege escalation, and defensive security.

---

## Certifications & Training

- **TryHackMe** — Top 5% Worldwide (December 2025)
- **Vulnerability Management with Nessus** — LinkedIn Learning
- **Security Testing: Nmap Security Scanning** — LinkedIn Learning
- **Azure: Create a Virtual Machine and Deploy a Web Server** — Coursera
- **Blue Team Junior Analyst** — Security Blue Team  
- **Reverse Engineering und Forensics** — University of Rostock
- **IT Technical Support Fundamentals** — Coursera  
- **A Deep Dive into SSL and TLS** — Udemy  
- **Machine Learning with Python** — Coursera & IBM
- **Neural Networks and Deep Learning** — Coursera

[View All Certificates](https://github.com/towhidulahmed/certificates)

---

## Languages

- **Bengali** — Native speaker  
- **English** — Fluent (C1 level)  
- **German** — Basic proficiency (A2, currently improving)

