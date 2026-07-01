# 🛡️ Advanced Security Research & Hands-on Labs

Welcome to my central repository for advanced security research, operational defense testing, and enterprise-grade lab environments. This repository serves as a technical portfolio showcasing my practical capabilities as a Cyber Security Specialist, with a heavy focus on Windows Internals, EDR Evasion, and Threat Analysis.

---

## 📂 Executive Portfolio Modules

Every project listed below includes a comprehensive, step-by-step technical lab report (`.docx`) complete with configuration architectures, command logs, and live execution screenshots.

### 🔴 Offensive Security & Evasion Techniques (Red Teaming)

* **🪤 Credential Harvesting via Port Forwarding**
    * *Description:* Establishing secure reverse tunnels through edge firewalls via Ngrok to deploy localized phishing vectors and capture credentials in clear-text.
    * *Report Document:* [credential-harvesting-lab.docx](./credential-harvesting-lab.docx)
* **⛓️ Constrained Language Mode (CLM) Bypass**
    * *Description:* Bypassing administrative PowerShell language restrictions to execute unconstrained arbitrary payloads and scripts.
    * *Report Document:* [clm-bypass.docx](./clm-bypass.docx)
* **💉 AppDomain Injection & Exploitation**
    * *Description:* Hijacking the .NET Framework application execution chain to achieve arbitrary code execution via custom AppDomain contexts.
    * *Report Document:* [appdomain.docx](./appdomain.docx)
* **🌪️ Alternate Data Streams (ADS) Exploitation**
    * *Description:* Utilizing NTFS file system vulnerabilities to conceal malicious payloads and execute hidden binaries behind legitimate file structures.
    * *Report Document:* [Alternate data streams.docx](./Alternate%20data%20streams.docx)
* **🧠 Memory Manipulation & Allocation Analysis**
    * *Description:* Examining host memory bounds, process injection mechanics, and analyzing runtime memory spaces for defensive/offensive positioning.
    * *Report Document:* [Memory Manipulation.docx](./Memory%20Manipulation.docx)

### 🔵 Enterprise Hardening & Defensive Architecture (Blue Teaming)

* **🚧 AppLocker Policy Design & Implementation**
    * *Description:* Engineering strict application whitelisting and software restriction policies to block unauthorized script and binary execution.
    * *Report Document:* [applocker.docx](./applocker.docx)
* **🛡️ Attack Surface Reduction (ASR) Rules Optimization**
    * *Description:* Deploying and auditing Microsoft Defender ASR rules to proactively block common malware origination vectors (e.g., malicious office macros, script abuse).
    * *Report Document:* [asr%20rules.docx](./asr%20rules.docx)
* **📊 Windows Registry Analysis & Forensics**
    * *Description:* Monitoring and parsing registry hives to hunt for persistent malware keys (Run/RunOnce), execution traces, and system modifications.
    * *Report Document:* [Registry-analysis.docx](./Registry-analysis.docx)
* **🔍 Enterprise Security Log Analysis**
    * *Description:* Aggregating, filtering, and investigating Event Logs to discover unauthorized access patterns and anomalous system behaviors.
    * *Report Document:* [log-analysis.docx](./log-analysis.docx)
* **🌐 VLAN Double-Tagging (Hopping) Vulnerability Lab**
    * *Description:* Simulating layer-2 network protocol flaws to test trunk encapsulation boundaries and evaluate network isolation integrity.
    * *Report Document:* [vlan double-tagging.docx](./vlan%20double-tagging.docx)

---

## 🛠️ Technical Proficiency Demonstrated
* **Operating Systems:** Kali Linux, Windows 11, Windows Internals architecture.
* **Networking & Tunnels:** Advanced Layer 2/3 protocols, NAT bypassing, secure reverse tunneling (Ngrok/SSH).
* **Defensive Compliance:** System hardening, enterprise policy auditing (AppLocker/ASR), threat hunting via logs/registry.

---

## ⚠️ Legal Disclaimer
All documentation, configurations, and technical write-ups in this repository were conducted strictly within private, sandboxed laboratory environments for self-directed educational purposes, institutional research, and defense optimization. Unauthorized deployment against remote targets is strictly prohibited and illegal.
