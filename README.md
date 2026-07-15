<div align="center">

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:000000,50:111111,100:1a1a1a&height=200&section=header&text=MUHAMMAD%20HARITH%20MUANIS&fontSize=38&fontColor=FFFFFF&fontAlignY=42&desc=CYBERSECURITY%20·%20DIGITAL%20FORENSICS%20·%20THREAT%20INTELLIGENCE%20·%20PURPLE%20TEAM&descAlignY=68&descSize=13&descColor=999999" />

<br/>

[![LINKEDIN](https://img.shields.io/badge/LINKEDIN-HARITHMUANIS-ffffff?style=for-the-badge&logo=linkedin&logoColor=000000&labelColor=ffffff)](https://linkedin.com)
[![EMAIL](https://img.shields.io/badge/EMAIL-HARITH-ffffff?style=for-the-badge&logo=gmail&logoColor=000000&labelColor=ffffff)](mailto:muhammadharithmuanismasrur@gmail.com)
[![MALAYSIA](https://img.shields.io/badge/NILAI%2C%20MALAYSIA-ffffff?style=for-the-badge&logo=googlemaps&logoColor=000000&labelColor=ffffff)](#)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## ABOUT

Hi, I'm Harith — a final-year Information Security & Assurance student at USIM, graduating August 2026. I've been fortunate to get some real hands-on time during my internship at NetByteSec, where I got to deploy a honeypot, monitor live attacker activity, and do a fair bit of forensics work. Outside of that I enjoy CTFs, tinkering with my own lab, and I'm currently working through a purple team exercise on the side. Still lots to learn, but genuinely enjoying the process.

```bash
$ whoami
> MUHAMMAD HARITH MUANIS | INFOSEC STUDENT @ USIM
> LEARNING  : DIGITAL FORENSICS | THREAT INTELLIGENCE | PURPLE TEAM
> INTERNING : NETBYTESEC | ENDS AUG 2026
> STATUS    : IMMEDIATELY AVAILABLE
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## TOOLS & STACK

Tools I've worked with — some more than others:

<p>
<img src="https://img.shields.io/badge/SPLUNK-ffffff?style=for-the-badge&logo=splunk&logoColor=000000" />
<img src="https://img.shields.io/badge/WIRESHARK-ffffff?style=for-the-badge&logo=wireshark&logoColor=000000" />
<img src="https://img.shields.io/badge/METASPLOIT-ffffff?style=for-the-badge&logo=metasploit&logoColor=000000" />
<img src="https://img.shields.io/badge/NMAP-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/NESSUS-ffffff?style=for-the-badge&logo=tenable&logoColor=000000" />
</p>
<p>
<img src="https://img.shields.io/badge/PROXMOX-ffffff?style=for-the-badge&logo=proxmox&logoColor=000000" />
<img src="https://img.shields.io/badge/NGINX-ffffff?style=for-the-badge&logo=nginx&logoColor=000000" />
<img src="https://img.shields.io/badge/LINUX-ffffff?style=for-the-badge&logo=linux&logoColor=000000" />
<img src="https://img.shields.io/badge/AUDITD-ffffff?style=for-the-badge&logo=linux&logoColor=000000" />
<img src="https://img.shields.io/badge/GOPHISH-ffffff?style=for-the-badge&logo=go&logoColor=000000" />
</p>
<p>
<img src="https://img.shields.io/badge/FTK_IMAGER-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/AUTOPSY-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/PYTHON-ffffff?style=for-the-badge&logo=python&logoColor=000000" />
<img src="https://img.shields.io/badge/PHP-ffffff?style=for-the-badge&logo=php&logoColor=000000" />
<img src="https://img.shields.io/badge/YOLO-ffffff?style=for-the-badge&logoColor=000000" />
</p>

**Where I practice** ⠀ `TRYHACKME` · `HACKTHEBOX` · `CTF COMPETITIONS`

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## SKILLS

**Blue Team / SOC**
SIEM log ingestion & correlation · SPL querying · incident timeline reconstruction · alert tuning

**Digital Forensics**
Disk image acquisition (VMDK) · PCAP analysis · Windows persistence artefacts (Credential Manager, registry, scheduled tasks)

**Red Team / Offensive**
Vulnerability assessment · phishing simulation · web exploitation · wireless pentesting

**Purple Team**
Lab infrastructure setup from scratch · adversary emulation · detection validation · gap analysis

**Threat Intelligence**
Honeypot deployment · attacker tradecraft profiling · investigation playbook development

**Machine Learning & AI**
YOLO (computer vision) · WEKA (data mining)

**Programming**
Advanced: PHP, HTML, C, C++ · Intermediate: Java, Python, Arduino

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## PROJECTS

### 🍯 HONEYPOT DEPLOYMENT & THREAT ANALYSIS
**NetByteSec Internship · March 2025 – August 2026**

Set up a Drupal 10 honeypot on Proxmox dressed up as a plausible Malaysian corporate environment — fake staff accounts, honeytoken credentials, canary tokens. The goal was to attract real attacker activity and observe what they actually do once they're in.

Ended up with ~1.1 million events across six Splunk sourcetypes. Wrote a custom investigation playbook and a full incident report off the back of it, which surfaced two separate attacker IPs with noticeably different tradecraft. Built the whole stack myself: Nginx, Auditd, Splunk Universal Forwarder, and network monitoring.

<sub>**STACK:** DRUPAL · PROXMOX · SPLUNK · NGINX · AUDITD · LINUX</sub>

---

### 🔴🔵 PURPLE TEAM EXERCISE — SELF-HOSTED LAB
**In Progress**

Spinning up a server from scratch as a target environment, then running both sides against it. Red team phase covers the usual: recon, exploitation, lateral movement. Blue team phase is about building the detection side — log collection, SIEM alerts, and incident write-ups — to see what actually gets caught and what slips through.

The point isn't just to attack or just to defend. It's to close the loop and understand where the gaps are between what an attacker does and what the defender sees.

<sub>**STACK:** LINUX · SPLUNK · NMAP · METASPLOIT · NESSUS</sub>

---

### 🔍 DISK & NETWORK FORENSICS
**NetByteSec Internship · March 2025 – August 2026**

Forensic acquisition and analysis of a Windows VMDK using FTK Imager and Autopsy — pulled filesystem artefacts, credential stores, and attacker footprints out of the image. Also worked through a 314 MB packet capture in Wireshark tracing a time-based blind SQL injection (`pg_sleep` via `forgotpassword.php`) back to the exfiltrated credentials. Finished by ingesting everything into Splunk and rebuilding the attack timeline with SPL queries.

<sub>**STACK:** FTK IMAGER · AUTOPSY · WIRESHARK · SPLUNK</sub>

---

### 🔐 SHADOWNET — SECURE DATA TRANSFER FRAMEWORK
**October 2025 · 🥈 Silver Medal, 5th Innovation Bank Challenge**

A secure file transfer mechanism built around steganography combined with quantum-resistant encryption. Presented as main pitcher, placed above 116+ teams at the Negeri Sembilan Festival of Ideas.

<sub>**STACK:** STEGANOGRAPHY · QUANTUM-RESISTANT ENCRYPTION</sub>

---

### 🚁 ANTI-DRONE DETECTION SYSTEM
**Final Year Project · Feb 2025 – Jan 2026**

Trained a YOLO-based computer vision model to flag unauthorised drones inside a defined surveillance boundary. Handled everything from dataset prep through to real-time video inference.

<sub>**STACK:** YOLO · PYTHON · COMPUTER VISION</sub>

---

### 🎣 PHISHING SIMULATION — ETHICAL HACKING EXERCISE
**July 2024**

Ran a controlled phishing campaign using GoPhish against a simulated organisation, tracked who clicked what, then delivered awareness briefings based on the results.

<sub>**STACK:** GOPHISH · SOCIAL ENGINEERING</sub>
<sub>📹 [Video demo](https://youtu.be/Gyld9TD0LeE)</sub>

---

### 🕌 SMARTMASJID SYSTEM
**Software Tester · February 2024**

Brought in as Software Tester for a mosque activity management system. Ran functional, integration, and performance tests across the full system, validated user flows, and made sure everything was stable before deployment.

<sub>**STACK:** FUNCTIONAL TESTING · INTEGRATION TESTING · PERFORMANCE TESTING</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## CERTIFICATIONS

| | NAME | ISSUER | DATE |
|:-:|---|---|---|
| ✓ | Blue Team Junior Analyst | CENTRI | July 2026 |
| ✓ | Wireless Penetration Tester | 0Day Academy | Feb 2026 |
| ✓ | CompTIA Security+ | CompTIA | Jan 2026 |
| ✓ | CCoE Career in Cybersecurity (Entry) | BlackBerry | May 2025 |
| ✓ | Introduction to Cloud Computing | — | May 2025 |
| ✓ | Introduction to Cryptography | — | Nov 2024 |
| ⋯ | Certified Artificial Intelligence (CAI) | — | In Progress |

**Training:** CompTIA Security+, CompTIA Pentest+, Cloud Computing (BlackBerry CCoE) · Drone Simulation & Flying (AKSADRONE)

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## CTFs & COMPETITIONS

| EVENT | RESULT | YEAR |
|---|---|---|
| 🥈 ShadowNet — 5th Innovation Bank Challenge, Negeri Sembilan FOI | Silver Medal | 2025 |
| LigaCTF — Week 6 | Top 4 | 2026 |
| Bahtera Siber CTF 3108 | Top 6% | 2025 |
| HackNyx | Participant | 2026 |
| Hack@10 | Participant | 2026 |
| ACOTECH Hackathon | Participant | 2025 |
| CTF Wargames MY | Participant | 2024 |

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## EDUCATION

| QUALIFICATION | INSTITUTION | RESULT |
|---|---|---|
| B.Sc. (Hons) Computer Science — Information Security & Assurance | USIM | CGPA 3.67 · Dean's Award ×4 |
| Foundation in Engineering | UiTM | CGPA 3.93 · Dean's Award ×2 |

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:1a1a1a,100:000000&height=80&section=footer" />
