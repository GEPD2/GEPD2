<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                   GEPD2 :: SECURITY RESEARCHER                   ║
║     CTI | Offensive Security | Digital Forensics (building)      ║
╚══════════════════════════════════════════════════════════════════╝
```

[![Profile Views](https://komarev.com/ghpvc/?username=GEPD2&label=PROFILE+VIEWS&color=00ff41&style=flat-square)](https://github.com/GEPD2)
[![GitHub Followers](https://img.shields.io/github/followers/GEPD2?label=FOLLOWERS&style=flat-square&color=00ff41&labelColor=0d1117)](https://github.com/GEPD2?tab=followers)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-TOP%202%25-00ff41?style=flat-square&labelColor=0d1117)](https://tryhackme.com/p/GEPD1)

</div>

---

## OPERATOR PROFILE

```python
class SecurityResearcher:
    def __init__(self):
        self.handle       = "GEPD2"
        self.role         = "Security Researcher | Cyber Threat Intelligence | Post-Quantum Cryptography"
        self.education    = "Ionian University Computer Science (2023–2027)"
        self.affiliation  = "Working closely with NMSLab on cybersecurity"
        self.location     = "Corfu, Greece"
        self.contact      = "georgios.efthymiou@tuta.com"

    def current_operations(self):
        return {
            "cti"       : "Threat actor tracking, IOC pipelines, dark web intelligence collection",
            "research"  : "Post-Quantum Cryptography and quantum-resistant cryptographic systems",
            "offensive" : ["Web & network pentesting (labs, CTFs)", "Exploit development (labs)", "Wireless security (labs)"],
            "defensive" : ["Digital forensics (building)", "Network protocol analysis"],
            "platform"  : "AGENTS-HQ: local-first AI intelligence platform (local LLM inference, no cloud AI)"
        }

    def opsec_stack(self):
        return {
            "operations" : ["Parrot OS", "Kali Linux", "BlackArch", "Kali Purple"],
            "high_opsec" : ["Qubes OS", "Tails OS"],
            "methodology": "Methodical analysis and thorough documentation"
        }
```

---

## FEATURED PROJECTS

### Intelligence & CTI Infrastructure

<table>
<tr>
<td width="50%">

**[AGENTS-HQ](https://github.com/GEPD2/agents-hq)**

Local-first AI intelligence platform with 10 agents. LLM inference runs locally through Ollama, with no cloud AI or telemetry; collection modules query external sources (Shodan, Censys, VirusTotal, Tor) by design.

**Stack:** Python · FastAPI · MySQL · n8n · Ollama · Docker · Tor  
**Model:** qwen2.5:14b  
**Agents:** OSINT Collector · Task Recon · RAG KB · Orchestrator · Red Team · Ghidra RE · Crypto Analysis · News Intel · Market Intel · Dark Web Monitor  
**Status:** `ACTIVE BUILD`

</td>
<td width="50%">

**[Crypto Toolkit](https://github.com/GEPD2/encryption_app)**

Cryptography GUI spanning classical ciphers to post-quantum key encapsulation.

**Stack:** Python · Kivy  
**Covers:** Caesar · Affine · Vigenère · 11 hash functions · ML-KEM-512/768/1024 (FIPS 203), hand-ported in pure Python  
**Purpose:** Teaching the classical-to-post-quantum span  
**Status:** `OPERATIONAL`

</td>
</tr>
</table>

### Offensive Security

<table>
<tr>
<td width="50%">

**[Automation Arsenal](https://github.com/GEPD2/automation_tool)**

Offensive security automation for network reconnaissance through vulnerability testing.

**Stack:** C · Python · Bash  
**Features:** Nmap automation · XSS testing · XML injection · UDP simulation  
**Context:** Controlled lab environments  
**Status:** `OPERATIONAL`

</td>
<td width="50%">

**[Web Attack Framework](https://github.com/GEPD2/web_csan_enumeration_and_attack_tool)**

Integrated web security testing with automated scanning through credential analysis.

**Stack:** Python  
**Features:** Web enumeration · Automated scanning · Hydra integration  
**Context:** Lab and CTF environments  
**Status:** `OPERATIONAL`

</td>
</tr>
<tr>
<td width="50%">

**[CTF Toolbox](https://github.com/GEPD2/CTF-scripts)**

Automation scripts for CTFs and labs, from reconnaissance through privilege escalation.

**Stack:** Bash  
**Features:** Automated recon · Enumeration · Exploitation workflows  
**Context:** CTF competitions · TryHackMe Top 2% · HTB  
**Status:** `OPERATIONAL`

</td>
<td width="50%">

**[Satellite Simulator](https://github.com/GEPD2/satellite_simulation)**

Orbital mechanics simulation with data transmission protocols.

**Stack:** Python  
**Features:** Orbital calculations · Communication protocols · Telemetry  
**Status:** `COMPLETE`

</td>
</tr>
</table>

---

## THREAT INTELLIGENCE WORK

```
IOC Extraction Pipelines    — automated extraction of IPs, hashes, domains, CVEs
Dark Web Collection         — passive .onion surface monitoring, paste site analysis
Threat Actor Profiling      — actor profiles and infrastructure correlation
RAG-Augmented Analysis      — LLM-assisted CTI via local MySQL KB + qwen2.5
Credential Exposure Ops     — breach database monitoring and hash analysis
```

---

## RESEARCH

```
[ IN PROGRESS ]  CRYSTALS-Kyber: Bridging Theory and Practice in PQ Key Encapsulation
                 Dependency-free C implementation checked against FIPS 203 vectors,
                 teaching platform and notebooks. Manuscript, in preparation

[ IN PROGRESS ]  Autonomous CTI Platform (AGENTS-HQ)
                 Local AI agent stack for threat intelligence automation
                 Local LLM inference; collectors query external sources by design

[ PLANNED ]      Dark Web Telemetry Analysis
                 Passive collection methodology and IOC enrichment pipeline

[ PLANNED ]      Vulnerability Research & Responsible Disclosure
                 Start bug bounty on HackerOne, Bugcrowd, YesWeHack, Intigriti

[ PLANNED ]      Evidence integrity for AGENTS-HQ
                 SHA-256, RFC 3161 timestamps and a chain-of-custody log per capture
```

---

## TECHNICAL ARSENAL

### Languages & Scripting
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00ff41)
![C](https://img.shields.io/badge/C-0d1117?style=flat-square&logo=c&logoColor=00ff41)
![C++](https://img.shields.io/badge/C++-0d1117?style=flat-square&logo=cplusplus&logoColor=00ff41)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=flat-square&logo=gnubash&logoColor=00ff41)
![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=00ff41)
![PHP](https://img.shields.io/badge/PHP-0d1117?style=flat-square&logo=php&logoColor=00ff41)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=00ff41)
![HTML5](https://img.shields.io/badge/HTML5-0d1117?style=flat-square&logo=html5&logoColor=00ff41)

### CTI & Intelligence Platform
![Tor](https://img.shields.io/badge/Tor_Network-0d1117?style=flat-square&logo=torproject&logoColor=00ff41)
![n8n](https://img.shields.io/badge/n8n-0d1117?style=flat-square&logo=n8n&logoColor=00ff41)
![ollama](https://img.shields.io/badge/ollama-0d1117?style=flat-square&logoColor=00ff41)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=00ff41)

### Network & Reconnaissance
![Nmap](https://img.shields.io/badge/Nmap-0d1117?style=flat-square&logoColor=00ff41)
![Wireshark](https://img.shields.io/badge/Wireshark-0d1117?style=flat-square&logo=wireshark&logoColor=00ff41)
![EtherApe](https://img.shields.io/badge/EtherApe-0d1117?style=flat-square&logoColor=00ff41)
![Snort](https://img.shields.io/badge/Snort-0d1117?style=flat-square&logoColor=00ff41)

### Web Application Security
![Burp Suite](https://img.shields.io/badge/Burp_Suite-0d1117?style=flat-square&logoColor=00ff41)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-0d1117?style=flat-square&logo=owasp&logoColor=00ff41)
![SQLmap](https://img.shields.io/badge/SQLmap-0d1117?style=flat-square&logoColor=00ff41)
![Gobuster](https://img.shields.io/badge/Gobuster-0d1117?style=flat-square&logoColor=00ff41)

### Exploitation & Post-Exploitation
![Metasploit](https://img.shields.io/badge/Metasploit-0d1117?style=flat-square&logoColor=00ff41)
![Hydra](https://img.shields.io/badge/Hydra-0d1117?style=flat-square&logoColor=00ff41)

### Reverse Engineering
![Ghidra](https://img.shields.io/badge/Ghidra-0d1117?style=flat-square&logoColor=00ff41)

### Cryptography & Password Analysis
![Hashcat](https://img.shields.io/badge/Hashcat-0d1117?style=flat-square&logoColor=00ff41)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-0d1117?style=flat-square&logoColor=00ff41)

### Digital Forensics
![Autopsy](https://img.shields.io/badge/Autopsy-0d1117?style=flat-square&logoColor=00ff41)
![YARA](https://img.shields.io/badge/YARA-0d1117?style=flat-square&logoColor=00ff41)

### Wireless Security
![Airgeddon](https://img.shields.io/badge/Airgeddon-0d1117?style=flat-square&logoColor=00ff41)

### Operating Systems

**Operations**
![Parrot OS](https://img.shields.io/badge/Parrot_OS-0d1117?style=flat-square&logoColor=00ff41)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-0d1117?style=flat-square&logo=kalilinux&logoColor=00ff41)
![Kali Purple](https://img.shields.io/badge/Kali_Purple-0d1117?style=flat-square&logo=kalilinux&logoColor=00ff41)
![BlackArch](https://img.shields.io/badge/BlackArch-0d1117?style=flat-square&logo=archlinux&logoColor=00ff41)

**High OPSEC**
![Qubes OS](https://img.shields.io/badge/Qubes_OS-0d1117?style=flat-square&logoColor=00ff41)
![Tails OS](https://img.shields.io/badge/Tails_OS-0d1117?style=flat-square&logoColor=00ff41)

---

## COMPETENCIES

```yaml
Cyber Threat Intelligence:
  - Dark web monitoring & passive .onion collection
  - Threat actor profiling
  - IOC extraction, enrichment & correlation
  - Automated CTI pipeline development
  - OSINT, open-source intelligence collection

Offensive Security:
  - Web and network penetration testing in labs and CTFs
  - Kerberoasting and AS-REP roasting against Active Directory (labs)
  - Exploit development (labs)
  - CTF: TryHackMe Top 2% | HackTheBox

Digital Forensics (building):
  - Storage media imaging and file recovery
  - Autopsy, YARA rules
  - Evidence integrity and chain of custody (learning)
  - Network protocol analysis with Wireshark
  - SIEM searches and Snort IDS (labs)

Research:
  - Post-quantum cryptography: CRYSTALS-Kyber / ML-KEM (FIPS 203)
  - Basic reverse engineering with Ghidra
  - AI agent development for security automation
  - Wireless security assessment (labs)
```

---

## OPERATIONAL OBJECTIVES

**Threat Intelligence Platform**
- [x] Agent-10 Dark Web Monitor: Tor-routed crawler + IOC pipeline
- [x] Agent-04 Master Orchestrator: routing across agents
- [ ] Evidence-integrity module: SHA-256, RFC 3161 timestamps, chain-of-custody log
- [ ] MITRE ATT&CK auto-mapping for Dark Web Monitor findings

**Security Research**
- [ ] Complete and publish the CRYSTALS-Kyber manuscript
- [ ] First responsible disclosure via HackerOne/Bugcrowd
- [ ] Dark web telemetry analysis methodology writeup

**Future Certifications**
- [ ] PNPT for TCM Security (Practical Network Penetration Tester)
- [ ] CompTIA CySA+ for Cybersecurity Analyst
- [ ] OSCP for Offensive Security Certified Professional
- [ ] Entry-level DFIR certification (BTL1 or CCD)

**Competition & Community**
- [ ] Hellenic University Hack 2026
- [ ] Security conference attendance & research presentation
- [ ] Technical writeups for CTF solutions & vulnerability research

---

## SECURE COMMS

<div align="center">

[![Email](https://img.shields.io/badge/georgios.efthymiou@tuta.com-0d1117?style=flat-square&logo=tutanota&logoColor=00ff41)](mailto:georgios.efthymiou@tuta.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=00ff41)](https://www.linkedin.com/in/%CE%B3%CE%B5%CF%8E%CF%81%CE%B3%CE%B9%CE%BF%CF%82-%CE%B5%CF%85%CE%B8%CF%85%CE%BC%CE%AF%CE%BF%CF%85-4520883b1/)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-0d1117?style=flat-square&logo=hackthebox&logoColor=00ff41)](https://app.hackthebox.com/public/users/2158940)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-0d1117?style=flat-square&logo=tryhackme&logoColor=00ff41)](https://tryhackme.com/p/GEPD1)

*Encrypted communication preferred to tuta.com natively supports end-to-end encryption.*

</div>

---

<div align="center">

```
Security research, threat intelligence, and defensive engineering.
All offensive work is done in labs, CTFs and controlled environments.
```

</div>
