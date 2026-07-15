<div align="center">

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:000000,50:111111,100:1a1a1a&height=180&section=header&text=MUHAMMAD%20HARITH%20MUANIS&fontSize=36&fontColor=FFFFFF&fontAlignY=42&desc=CYBERSECURITY%20·%20DIGITAL%20FORENSICS%20·%20THREAT%20INTELLIGENCE%20·%20PURPLE%20TEAM&descAlignY=68&descSize=13&descColor=888888" />

<br/>

[![LINKEDIN](https://img.shields.io/badge/LINKEDIN-ffffff?style=for-the-badge&logo=linkedin&logoColor=000000)](https://linkedin.com)
[![EMAIL](https://img.shields.io/badge/EMAIL-ffffff?style=for-the-badge&logo=gmail&logoColor=000000)](mailto:muhammadharithmuanismasrur@gmail.com)
[![MALAYSIA](https://img.shields.io/badge/NILAI%2C%20MALAYSIA-ffffff?style=for-the-badge&logo=googlemaps&logoColor=000000)](#)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

Hi, I'm Harith — a final-year Information Security & Assurance student at USIM, graduating August 2026. I've been fortunate to get some real hands-on time during my internship at NetByteSec, where I got to deploy a honeypot, monitor live attacker activity, and do a fair bit of forensics work. Outside of that I enjoy CTFs, tinkering with my own lab, and I'm currently working through a purple team exercise on the side. Still lots to learn, but genuinely enjoying the process.

```js
const harith = {
  education : "B.Sc. Computer Science (Information Security & Assurance) @ USIM",
  internship : "NetByteSec — Cybersecurity Analyst Intern",
  focus     : ["Digital Forensics", "Threat Intelligence", "Purple Teaming", "Incident Response"],
  certs     : ["CompTIA Security+", "Wireless Penetration Tester", "Blue Team Junior Analyst (CENTRI)"],
  tools     : {
    siem      : ["Splunk", "Auditd"],
    forensics : ["FTK Imager", "Autopsy", "Wireshark"],
    offensive : ["Nmap", "Metasploit", "Nessus", "GoPhish"],
    infra     : ["Proxmox", "Nginx", "Docker", "Cloudflare", "DigitalOcean"],
    ml        : ["YOLO", "WEKA"],
  },
  languages  : {
    advanced     : ["PHP", "HTML", "C", "C++"],
    intermediate : ["Python", "Java", "Arduino"],
  },
  ctf        : ["LigaCTF — Top 4 (2026)", "Bahtera Siber — Top 6% (2025)", "HackNyx (2026)", "Hack@10 (2026)"],
  status     : "immediately available",
};
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## TOOLS

<p align="center">
<img src="https://img.shields.io/badge/SPLUNK-ffffff?style=for-the-badge&logo=splunk&logoColor=000000" />
<img src="https://img.shields.io/badge/WIRESHARK-ffffff?style=for-the-badge&logo=wireshark&logoColor=000000" />
<img src="https://img.shields.io/badge/METASPLOIT-ffffff?style=for-the-badge&logo=metasploit&logoColor=000000" />
<img src="https://img.shields.io/badge/NMAP-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/NESSUS-ffffff?style=for-the-badge&logo=tenable&logoColor=000000" />
<img src="https://img.shields.io/badge/PROXMOX-ffffff?style=for-the-badge&logo=proxmox&logoColor=000000" />
<img src="https://img.shields.io/badge/DOCKER-ffffff?style=for-the-badge&logo=docker&logoColor=000000" />
<img src="https://img.shields.io/badge/NGINX-ffffff?style=for-the-badge&logo=nginx&logoColor=000000" />
<img src="https://img.shields.io/badge/CLOUDFLARE-ffffff?style=for-the-badge&logo=cloudflare&logoColor=000000" />
<img src="https://img.shields.io/badge/DIGITALOCEAN-ffffff?style=for-the-badge&logo=digitalocean&logoColor=000000" />
<img src="https://img.shields.io/badge/FTK_IMAGER-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/AUTOPSY-ffffff?style=for-the-badge&logoColor=000000" />
<img src="https://img.shields.io/badge/GOPHISH-ffffff?style=for-the-badge&logo=go&logoColor=000000" />
<img src="https://img.shields.io/badge/LINUX-ffffff?style=for-the-badge&logo=linux&logoColor=000000" />
<img src="https://img.shields.io/badge/PYTHON-ffffff?style=for-the-badge&logo=python&logoColor=000000" />
<img src="https://img.shields.io/badge/YOLO-ffffff?style=for-the-badge&logoColor=000000" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=2" width="100%" />

## GITHUB STATS

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AhmadBatu&theme=github_dark" width="100%" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AhmadBatu&theme=github_dark" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AhmadBatu&theme=github_dark" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AhmadBatu&theme=github_dark" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=AhmadBatu&theme=github_dark" />

</div>

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

### 🌐 CTFD INFRASTRUCTURE — SELF-HOSTED CTF PLATFORM
**Side Project · 2025**

Deployed and managed a live CTF platform for a national competition. Handled the full infra stack from scratch — provisioned a DigitalOcean droplet, containerised CTFd with Docker, set up Nginx as reverse proxy, bought and connected a custom domain, and routed traffic through Cloudflare for DNS and DDoS protection. Managed the containers live during the competition.

<sub>**STACK:** CTFD · DOCKER · NGINX · CLOUDFLARE · DIGITALOCEAN · LINUX</sub>

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

<div align="center">

<img src="https://raw.githubusercontent.com/AhmadBatu/AhmadBatu/main/certs/comptia-security-ce-certification.png" width="30%" />
<img src="https://raw.githubusercontent.com/AhmadBatu/AhmadBatu/main/certs/wireless.png" width="30%" />
<img src="https://raw.githubusercontent.com/AhmadBatu/AhmadBatu/main/certs/centri.png" width="30%" />

</div>

<br/>

<p align="center">
<img src="https://img.shields.io/badge/CompTIA_Security%2B-ffffff?style=for-the-badge&logo=comptia&logoColor=000000" />
<img src="https://img.shields.io/badge/Wireless_Penetration_Tester-ffffff?style=for-the-badge&logo=googlechrome&logoColor=000000" />
<img src="https://img.shields.io/badge/Blue_Team_Junior_Analyst-ffffff?style=for-the-badge&logo=cyberdefenders&logoColor=000000" />
<img src="https://img.shields.io/badge/CCoE_Cybersecurity_Entry-ffffff?style=for-the-badge&logo=blackberry&logoColor=000000" />
<img src="https://img.shields.io/badge/Intro_to_Cloud_Computing-ffffff?style=for-the-badge&logo=icloud&logoColor=000000" />
<img src="https://img.shields.io/badge/Intro_to_Cryptography-ffffff?style=for-the-badge&logo=gnuprivacyguard&logoColor=000000" />
<img src="https://img.shields.io/badge/CAI-In_Progress-555555?style=for-the-badge" />
</p>

**Training:** CompTIA Security+, CompTIA Pentest+, Cloud Computing (BlackBerry CCoE) · Drone Simulation & Flying (AKSADRONE)

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:1a1a1a,100:000000&height=80&section=footer" />
