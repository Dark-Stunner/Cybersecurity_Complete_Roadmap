<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:00f5a0&height=220&section=header&text=Cybersecurity%20Roadmap&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=From%20Zero%20to%20Advanced%20Specialist&descSize=20&descAlignY=58)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=00F5A0&center=true&vCenter=true&width=700&lines=Learn+%E2%86%92+Practice+%E2%86%92+Certify+%E2%86%92+Specialize;Build+your+foundations+the+right+way;Hands-on+beats+certificate+hoarding;12+months+to+job-ready+%7C+3-5+years+to+specialist)](https://git.io/typing-svg)

<br>

![Level](https://img.shields.io/badge/Level-Beginner%20→%20Advanced-00f5a0?style=for-the-badge&logo=target&logoColor=white)
![Duration](https://img.shields.io/badge/Duration-12%20Months%20to%20Job--Ready-0ea5e9?style=for-the-badge&logo=clockify&logoColor=white)
![Tracks](https://img.shields.io/badge/Tracks-5%20Career%20Paths-a855f7?style=for-the-badge&logo=hackthebox&logoColor=white)
![Free](https://img.shields.io/badge/Resources-Mostly%20Free-f59e0b?style=for-the-badge&logo=opensourceinitiative&logoColor=white)

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

**A practical, step-by-step guide to becoming a cybersecurity specialist, with phases, milestones, tools, labs and certifications.**

[🗺️ Roadmap](#-the-big-picture) • [🧱 Phase 1](#-phase-1-it-foundations-months-1-3) • [🛡️ Phase 2](#-phase-2-security-fundamentals-months-3-6) • [🎯 Phase 3](#-phase-3-hands-on-skills--choosing-your-path-months-6-12) • [🚀 Phase 4](#-phase-4-professional-entry--intermediate-year-1-2) • [👑 Phase 5](#-phase-5-advanced-specialist-year-3-5) • [🧰 Resources](#-resource-hub)

</div>

---

## 📑 Table of Contents

- [🗺️ The Big Picture](#-the-big-picture)
- [🧭 Phase 0: Orientation](#-phase-0-orientation-week-1-2)
- [🧱 Phase 1: IT Foundations](#-phase-1-it-foundations-months-1-3)
- [🛡️ Phase 2: Security Fundamentals](#-phase-2-security-fundamentals-months-3-6)
- [🎯 Phase 3: Hands-On Skills & Choosing Your Path](#-phase-3-hands-on-skills--choosing-your-path-months-6-12)
- [🚀 Phase 4: Professional Entry & Intermediate](#-phase-4-professional-entry--intermediate-year-1-2)
- [👑 Phase 5: Advanced Specialist](#-phase-5-advanced-specialist-year-3-5)
- [🔁 Cross-Cutting Habits](#-cross-cutting-habits)
- [📅 Summary Timeline](#-summary-timeline)
- [🧰 Resource Hub](#-resource-hub)
- [🤝 Contributing](#-contributing)

---

## 🗺️ The Big Picture

> 💡 **Realistic expectation:** ~**12 months** to be job-ready at entry level, and **3-5 years** to reach genuine specialist level. Consistent hands-on practice matters far more than collecting certificates.

### Roadmap Flowchart

```mermaid
flowchart TD
    A([🚀 START: Zero Experience]) --> B["🧭 Phase 0<br/>Orientation<br/>Week 1-2"]
    B --> C["🧱 Phase 1<br/>IT Foundations<br/>Months 1-3"]
    C --> D["🛡️ Phase 2<br/>Security Fundamentals<br/>Months 3-6"]
    D --> E["🎯 Phase 3<br/>Hands-On + Pick a Track<br/>Months 6-12"]
    E --> F["🚀 Phase 4<br/>First Job + Deepening<br/>Year 1-2"]
    F --> G["👑 Phase 5<br/>Specialist<br/>Year 3-5+"]

    F --> R["🔴 Red Team"]
    F --> BL["🔵 Blue Team"]
    F --> CL["☁️ Cloud Security"]
    F --> AP["💻 AppSec / DevSecOps"]
    F --> GR["📋 GRC"]

    R --> G
    BL --> G
    CL --> G
    AP --> G
    GR --> G

    classDef start fill:#00f5a0,stroke:#00f5a0,color:#0b1220,font-weight:bold
    classDef phase fill:#0f2027,stroke:#00f5a0,color:#ffffff
    classDef track fill:#1e293b,stroke:#a855f7,color:#ffffff
    classDef goal fill:#f59e0b,stroke:#f59e0b,color:#0b1220,font-weight:bold

    class A start
    class B,C,D,E,F phase
    class R,BL,CL,AP,GR track
    class G goal
```

### 🧠 Cybersecurity Domain Map

```mermaid
mindmap
  root((Cybersecurity))
    Offensive
      Penetration Testing
      Red Teaming
      Exploit Development
      Bug Bounty
    Defensive
      SOC Analysis
      Threat Hunting
      Incident Response
      Digital Forensics
    Engineering
      Cloud Security
      Application Security
      DevSecOps
      Network Security
    GRC
      Governance
      Risk Management
      Compliance
      Auditing
    Specialized
      Malware Analysis
      Reverse Engineering
      Threat Intelligence
      OT and ICS Security
```

### 🗓️ First 12 Months at a Glance

```mermaid
gantt
    title First 12 Months: Zero to Job-Ready
    dateFormat  YYYY-MM-DD
    axisFormat  Month %m
    section Orientation
    Explore the landscape          :done, p0, 2026-01-01, 14d
    section Foundations
    OS and Linux and Windows       :active, p1a, 2026-01-15, 75d
    Networking                     :active, p1b, 2026-01-15, 75d
    Python and Scripting           :p1c, 2026-02-01, 60d
    Home Lab                       :p1d, 2026-02-01, 45d
    section Security Basics
    Security Concepts and Crypto   :p2a, 2026-04-01, 60d
    OWASP Top 10 and Web           :p2b, 2026-04-15, 60d
    Security+ Exam                 :crit, p2c, 2026-06-01, 30d
    section Hands-On
    Sample Blue and Red Team       :p3a, 2026-07-01, 60d
    Commit to a Track              :milestone, p3b, 2026-09-01, 1d
    Portfolio and Write-ups        :p3c, 2026-09-01, 90d
    Entry-Level Applications       :crit, p3d, 2026-10-01, 90d
```

### ⏱️ Suggested Weekly Time Split

```mermaid
pie showData title Weekly Study Time Allocation
    "Hands-on labs and CTFs" : 50
    "Theory and reading" : 20
    "Coding and scripting" : 15
    "Write-ups and portfolio" : 10
    "Community and networking" : 5
```

---

## 🧭 Phase 0: Orientation (Week 1-2)

**Goal:** Understand the landscape before diving in.

| Area | Focus |
|------|-------|
| 🔴 **Offensive (Red Team)** | Penetration testing, red teaming, exploit development |
| 🔵 **Defensive (Blue Team)** | SOC analysis, threat hunting, incident response, forensics |
| ☁️ **Engineering / Architecture** | Cloud security, AppSec, DevSecOps, network security |
| 📋 **GRC** | Governance, risk, compliance, auditing |
| 🧬 **Specialized** | Malware analysis, reverse engineering, threat intel, OT/ICS |

> You don't need to choose yet. **Phases 1-2 are common to everyone.**

> [!WARNING]
> **Ground rules:** Only practice on systems you own or on labs designed for it. Unauthorized access is illegal, even "just to test." Learn the basics of relevant laws (e.g., India's IT Act, or the laws where you plan to work).

---

## 🧱 Phase 1: IT Foundations (Months 1-3)

> Most beginners skip this and struggle later. **You can't secure what you don't understand.**

### 1️⃣ Computer & OS Fundamentals
- How hardware, memory, processes, and file systems work
- **Windows:** Active Directory basics, registry, services, event logs, PowerShell
- **Linux:** command line, file permissions, users/groups, package management, services, logs. Aim to live in the terminal.

### 2️⃣ Networking (Most Important Foundation)
- OSI and TCP/IP models, IP addressing, subnetting, MAC, ARP
- DNS, DHCP, HTTP/HTTPS, FTP, SSH, SMTP, TLS
- Routers, switches, firewalls, VLANs, NAT, VPNs
- Practice with **Wireshark**: capture traffic and read packets

### 3️⃣ Programming & Scripting

| Language | Priority | Use Case |
|----------|:--------:|----------|
| 🐍 **Python** | ⭐⭐⭐⭐⭐ | Automation, parsing, simple tools, sockets |
| 🐚 **Bash** | ⭐⭐⭐⭐ | Linux automation |
| 🪟 **PowerShell** | ⭐⭐⭐⭐ | Windows automation and admin |
| 🗄️ **SQL** | ⭐⭐⭐ | Web security, data analysis |
| 🌐 **JavaScript / HTML** | ⭐⭐⭐ | Web security |
| ⚙️ **C / C++ / Assembly** | ⭐⭐ (later) | Reverse engineering, exploit development |

### 4️⃣ Build a Home Lab

```mermaid
flowchart LR
    H["💻 Host Machine<br/>VirtualBox / VMware"] --> K["🐉 Kali Linux<br/>Attacker"]
    H --> U["🐧 Ubuntu Server<br/>Target / Services"]
    H --> W["🪟 Windows VM<br/>Target / AD Lab"]
    K <--> N{{"🔒 Isolated<br/>Virtual Network"}}
    U <--> N
    W <--> N

    classDef host fill:#0f2027,stroke:#00f5a0,color:#fff
    classDef vm fill:#1e293b,stroke:#0ea5e9,color:#fff
    classDef net fill:#a855f7,stroke:#a855f7,color:#fff
    class H host
    class K,U,W vm
    class N net
```

<details>
<summary><b>📚 Recommended Resources for Phase 1 (click to expand)</b></summary>

| Topic | Resource |
|-------|----------|
| Network+/Security+ videos | [Professor Messer](https://www.professormesser.com/) (free) |
| Intro programming | [CS50](https://cs50.harvard.edu/) |
| Linux | [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) |
| Networking | [Cisco Networking Academy](https://www.netacad.com/) |
| Guided start | [TryHackMe Pre-Security Path](https://tryhackme.com/) |

</details>

**🎓 Optional certs:** CompTIA Network+ or CCNA (A+ if totally new to IT)

> ✅ **Milestone:** You can explain what happens when you type a URL into a browser (DNS → TLS → HTTP) and write a short Python script to automate a task.

---

## 🛡️ Phase 2: Security Fundamentals (Months 3-6)

### 🔑 Core Concepts
- **CIA triad**, authentication vs. authorization, least privilege, defense in depth
- Threat actors, **Cyber Kill Chain**, **MITRE ATT&CK** framework
- **Cryptography:** symmetric/asymmetric encryption, hashing, digital signatures, PKI, certificates
- **Common attacks:** phishing, malware, DoS/DDoS, MITM, password attacks, social engineering
- **Vulnerability management:** CVE, CVSS, patching
- **Security controls:** firewalls, IDS/IPS, EDR, antivirus, SIEM, WAF

### 🌐 Web Security Fundamentals: OWASP Top 10
SQL injection • XSS • CSRF • Broken access control • SSRF • Insecure deserialization • and more.

### 🧪 Hands-On Practice

| Platform | What to Do |
|----------|-----------|
| [TryHackMe](https://tryhackme.com/) | Complete Beginner, Jr Penetration Tester, SOC Level 1 paths |
| [PortSwigger Academy](https://portswigger.net/web-security) | Free, excellent web security labs |
| [picoCTF](https://picoctf.org/) | Beginner-friendly CTFs |

### 🏅 Certification
![Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)

> Widely recognized and a common HR filter for entry-level roles.

> ✅ **Milestone:** You can explain the OWASP Top 10 with examples, use **Nmap, Wireshark, and Burp Suite** at a basic level, and have solved **30-50 beginner labs/challenges**.

---

## 🎯 Phase 3: Hands-On Skills & Choosing Your Path (Months 6-12)

Spend ~**2 months sampling both sides**, then commit to a track.

```mermaid
flowchart LR
    S["🎯 Sampling Period<br/>~2 Months"] --> RT["🔴 Red Team Sampling"]
    S --> BT["🔵 Blue Team Sampling"]
    RT --> D{"Which feels<br/>more natural?"}
    BT --> D
    D -->|Breaking things| OFF["🔴 Offensive Track"]
    D -->|Detecting and responding| DEF["🔵 Defensive Track"]
    D -->|Cloud or code| ENG["☁️ Engineering Track"]
    D -->|Policy and risk| GRC["📋 GRC Track"]

    classDef s fill:#f59e0b,stroke:#f59e0b,color:#0b1220
    classDef r fill:#7f1d1d,stroke:#ef4444,color:#fff
    classDef b fill:#1e3a8a,stroke:#3b82f6,color:#fff
    classDef g fill:#14532d,stroke:#22c55e,color:#fff
    class S s
    class RT,OFF r
    class BT,DEF b
    class ENG,GRC g
```

<table>
<tr>
<td width="50%" valign="top">

### 🔵 Blue Team Sampling
- Read logs, investigate alerts
- Use a SIEM: **Splunk Free, Elastic/Wazuh, Security Onion**
- Learn **Sysmon**, Windows event IDs, **Snort/Suricata**, **YARA**, **Sigma** rules
- **Platforms:** LetsDefend, Blue Team Labs Online, CyberDefenders

</td>
<td width="50%" valign="top">

### 🔴 Red Team Sampling
- Recon → Scanning → Exploitation → PrivEsc → Post-exploitation
- **Platforms:** Hack The Box (Starting Point, easy machines), TryHackMe offensive paths
- **Tools:** Nmap, Burp Suite, Metasploit, Gobuster, John/Hashcat, BloodHound (later)

</td>
</tr>
</table>

### 📝 Document Everything
Start a **blog, GitHub, or Notion** with write-ups of machines you've solved, lab setups, and small scripts. **This becomes your portfolio.**

### 🏅 Entry Certs by Track

| Track | Certifications |
|:-----:|----------------|
| 🔴 Offensive | `eJPT` → `PNPT` or `CPTS` |
| 🔵 Defensive | `BTL1`, `CompTIA CySA+` |
| 📋 GRC | `ISC2 CC`, `ISO 27001 Foundation` |

> ✅ **Milestone:** You've chosen a track, built a visible portfolio, and are applying for entry-level roles: **SOC Analyst L1, Junior Pentester, Security Analyst, Vulnerability Analyst, IT Auditor.**

---

## 🚀 Phase 4: Professional Entry & Intermediate (Year 1-2)

**Get a job.** Paid experience beats solo study. Common entry points: SOC analyst, helpdesk/sysadmin → security, or an internship. Many strong specialists started in IT support or networking.

### Choose Your Deep-Dive Track

<details open>
<summary><b>🔴 A. Penetration Testing / Red Team</b></summary>

- Advanced web app testing (business logic, API testing, auth bypasses)
- **Active Directory attacks:** Kerberoasting, pass-the-hash, lateral movement, domain escalation
- Network and wireless pentesting, mobile app testing (Android/iOS)
- **Reporting skills**: a pentest is only as useful as its report

**Certs:** `OSCP` (industry benchmark) → `CRTO`, `OSWE`, `OSEP`

</details>

<details>
<summary><b>🔵 B. SOC / Incident Response / Threat Hunting</b></summary>

- **Detection engineering:** SIEM queries and detection rules
- Incident response lifecycle (NIST), memory and disk forensics (Volatility, Autopsy)
- Threat hunting using hypotheses and ATT&CK
- Malware triage, EDR tools (CrowdStrike, Defender, SentinelOne)

**Certs:** `CySA+`, `GCIH`, `GCFA`, `BTL2`, `GCIA`

</details>

<details>
<summary><b>☁️ C. Cloud Security</b></summary>

- Master **one cloud first** (AWS, Azure, or GCP): IAM, networking, logging, storage security
- Infrastructure as Code (**Terraform**), container/Kubernetes security
- CSPM tools, cloud attack paths

**Certs:** `AWS Security Specialty`, `AZ-500`, `CCSP`, `CKS`

</details>

<details>
<summary><b>💻 D. Application Security / DevSecOps</b></summary>

- Secure code review, **SAST / DAST / SCA**, threat modeling (**STRIDE**)
- CI/CD pipeline security, secrets management

**Certs:** `OSWE`, `GWEB`, relevant secure coding training

</details>

<details>
<summary><b>📋 E. GRC (Governance, Risk, Compliance)</b></summary>

- Frameworks: **ISO 27001, NIST CSF/800-53, SOC 2, PCI-DSS, GDPR**
- Risk assessments, policy writing, audits, vendor risk management

**Certs:** `CISA`, `CRISC`, `CISM`, later `CISSP`

</details>

### 📈 Intermediate Skill Progression

```mermaid
xychart-beta
    title "Typical Skill Growth Over Time (Illustrative)"
    x-axis ["Month 3", "Month 6", "Month 12", "Year 2", "Year 3", "Year 5"]
    y-axis "Skill Level (0-100)" 0 --> 100
    line [10, 25, 45, 62, 78, 92]
```

---

## 👑 Phase 5: Advanced Specialist (Year 3-5+)

This is where you become **known for something specific.**

| Path | Specialties | Advanced Certs |
|------|-------------|----------------|
| 🔴 **Offensive** | Exploit development (buffer overflows, ROP, heap, kernel), red team ops & C2, evasion, hardware/IoT hacking, vulnerability research, bug bounty | `OSEE` `OSED` `CRTL` `GXPN` |
| 🔵 **Defensive** | Malware analysis & reverse engineering (IDA/Ghidra, x64dbg), advanced forensics, threat intelligence, purple teaming, detection engineering at scale | `GREM` `GCTI` `GNFA` |
| 🏛️ **Architecture / Leadership** | Security architecture, zero trust design, large-scale threat modeling, CISO track (risk, budgeting, communication) | `CISSP` `CISM` `SABSA` `CCSP` |
| 🧬 **Niche Domains** | OT/ICS/SCADA, automotive, medical devices, AI/ML security, blockchain & smart contract auditing | Domain-specific |

### 💪 Advanced Habits
- 📖 Read research papers, conference talks (**DEF CON, Black Hat, BSides**), and CVE write-ups
- 🎤 Give talks, publish research or tools, contribute to open source
- 💰 Participate in bug bounties (**HackerOne, Bugcrowd**) for real-world experience
- 🧑‍🏫 Mentor others: teaching deepens your own understanding

---

## 🔁 Cross-Cutting Habits

| # | Habit | Why It Matters |
|:-:|-------|----------------|
| 1 | ⏰ **Practice daily/weekly** | Even 1-2 hours a day compounds enormously |
| 2 | 📰 **Stay current** | Follow The Hacker News, Krebs on Security, BleepingComputer, researchers on X/Mastodon/LinkedIn |
| 3 | 🗣️ **Build soft skills** | Report writing, explaining risk to non-technical people, teamwork |
| 4 | 🤝 **Network** | Local meetups, BSides, OWASP chapters, Discord/Slack communities |
| 5 | 🚫 **Don't cert-hoard** | 1-2 well-chosen certs + strong portfolio beats 10 certs with no practical skill |

---

## 📅 Summary Timeline

```mermaid
timeline
    title Your Cybersecurity Journey
    Months 1-3 : IT Foundations
               : OS and Networking
               : Python and Home Lab
    Months 3-6 : Security Fundamentals
               : OWASP and Crypto
               : Security+ Certification
    Months 6-12 : Sample Both Sides
                : Choose a Track
                : Portfolio and Applications
    Year 1-2 : First Security Role
             : Track Deepening
             : OSCP / CySA+ / Cloud Cert
    Year 3-5+ : Specialization
              : Research and Talks
              : Leadership or Expert Status
```

| Period | Focus | Output |
|--------|-------|--------|
| **Months 1-3** | OS, networking, Python, home lab | Strong IT base |
| **Months 3-6** | Security concepts, OWASP, labs | Security+ |
| **Months 6-12** | Pick track, CTFs, portfolio | Entry cert + job applications |
| **Year 1-2** | First role + track deepening | OSCP / CySA+ / cloud cert |
| **Year 3-5+** | Specialization, research, leadership | Expert-level reputation |

---

## 🧰 Resource Hub

### 🎮 Practice Platforms

| Platform | Best For | Cost |
|----------|----------|:----:|
| [TryHackMe](https://tryhackme.com/) | Guided beginner learning | Free + Paid |
| [Hack The Box](https://www.hackthebox.com/) | Realistic machines, pentesting | Free + Paid |
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) | Web app security | Free |
| [OverTheWire](https://overthewire.org/wargames/) | Linux and wargames | Free |
| [picoCTF](https://picoctf.org/) | Beginner CTFs | Free |
| [LetsDefend](https://letsdefend.io/) | SOC analyst practice | Free + Paid |
| [CyberDefenders](https://cyberdefenders.org/) | Blue team challenges | Free + Paid |
| [Blue Team Labs Online](https://blueteamlabs.online/) | Defensive labs | Free + Paid |

### 🛠️ Essential Toolkit

![Nmap](https://img.shields.io/badge/Nmap-Scanning-4682B4?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-Packets-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-Web%20Testing-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-Exploitation-2596CD?style=flat-square)
![Kali](https://img.shields.io/badge/Kali%20Linux-Offensive%20OS-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-SIEM-000000?style=flat-square&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM%20%2F%20XDR-00A9E5?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-Reverse%20Engineering-C0392B?style=flat-square)
![Python](https://img.shields.io/badge/Python-Scripting-3776AB?style=flat-square&logo=python&logoColor=white)

### 📰 Stay Updated
[The Hacker News](https://thehackernews.com/) • [Krebs on Security](https://krebsonsecurity.com/) • [BleepingComputer](https://www.bleepingcomputer.com/) • [DEF CON](https://defcon.org/) • [Black Hat](https://www.blackhat.com/)

---

## 🤝 Contributing

Found an outdated resource or want to add a section? Contributions are welcome!

1. 🍴 Fork this repository
2. 🌿 Create a branch: `git checkout -b feature/improve-roadmap`
3. 💾 Commit your changes: `git commit -m "Add: new resource"`
4. 📤 Push to your branch: `git push origin feature/improve-roadmap`
5. 🔃 Open a Pull Request

---

## ⚖️ Disclaimer

This roadmap is for **educational purposes only**. Always practice ethically and legally, only on systems you own or have explicit written permission to test. Certification names and platforms may change over time; verify current details on official websites.

---

<div align="center">

### ⭐ If this roadmap helped you, give it a star!

**Stay curious. Stay ethical. Keep hacking (legally). 🛡️**

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:00f5a0,50:203a43,100:0f2027&height=120&section=footer)

</div>
