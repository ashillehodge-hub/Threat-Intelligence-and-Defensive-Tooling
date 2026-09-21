# Threat Intelligence & Defensive Security Tooling

## Overview
This repository features defensive network auditing tools, automated administrative scripting in Linux Bash and Windows Batch, Open-Source Intelligence (OSINT) reconnaissance reports, and intrusion monitoring via a deployed Pentbox honeypot.

---

## Core Tooling & Implementations

### 1. Security Automation & Scripting (Bash & Batch)
* **Linux Bash Tooling:** Developed modular shell scripts to automate network diagnostics:
  * *Ping Scanner:* Prompts users for target domains and packet counts to automate reachability testing.
  * *File-Based Ping Sweep:* Iterates through bulk target addresses stored in external text files (`url.txt`) to assess fleet availability.
  * *Reconnaissance Wrapper:* Integrated custom interactive prompts with Nmap and network utilities for rapid service enumeration.
* **Windows Batch Automation (`.bat`):** Engineered administrative utility scripts for folder directory management, secure file staging, diagnostic checks, and targeted system monitoring.

### 2. OSINT & Active Vulnerability Scanning
* **Attack Surface Mapping:** Executed Open-Source Intelligence gathering against target domains (`testphp.vulnweb.com`, `ggc.edu`), uncovering hosting infrastructure (Amazon AWS), geographic server locations, subdomains, and primary technical contacts.
* **Nmap Port & NSE Auditing:** Performed active reconnaissance across privileged ports, OS fingerprinting (Linux kernel detection), and vulnerability scripts (`script vuln`) to surface unpatched application vectors.

### 3. Honeypot Deployment & Intrusion Logging
* **Pentbox Honeypot Integration:** Deployed a low-interaction honeypot on an isolated network port to emulate web services and capture adversarial scanning activity.
* **Telemetry Triage:** Logged incoming connection metadata including attacker source IPs, timestamps, and client User-Agent strings, triggering automated administrator alerts upon unauthorized probe detection.

---

## Repository Artifacts
* `Linux-Bash-Scripting-Security-Automation-Ashille-Hodge.pdf` — Bash scripts for ping sweeps, DNS reconnaissance, and port scanning wrappers.
* `Windows-Batch-Scripting-Security-Automation-Ashille-Hodge.pdf` — Windows batch scripts for administrative automation and file integrity checks.
* `OSINT-Reconnaissance-Nmap-Auditing-and-Honeypots-Ashille-Hodge.pdf` — OSINT target audits, Nmap vulnerability scanning outputs, and honeypot deployment logs.
