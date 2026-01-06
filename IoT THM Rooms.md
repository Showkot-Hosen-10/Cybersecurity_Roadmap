# TryHackMe IoT & Embedded Security Rooms

This section focuses on **IoT security**, **embedded firmware**, and the **networking foundations** required to understand and attack Internet of Things ecosystems. It starts with theoretical and networking concepts, then moves into hands-on labs involving firmware extraction, emulation, and practical IoT pentesting on TryHackMe.  

## Author

**Name:** Showkot Hosen  
**Institution:** Chittagong University of Engineering & Technology (CUET)  
**Department:** Electronics and Telecommunication Engineering (ETE), CUET  
**Affiliation:** Student and enthusiast in ML-based cybersecurity research | Cisco EH | TryHackMe AoC 2025 & Presecurity Path | ML Models for Cybersecurity  

---

## IoT foundations (Easy)

1. [Intro to IoT Pentesting](https://tryhackme.com/room/iotintro)  
   Beginner-friendly overview of Internet of Things architectures, typical components, attack surfaces, and a guided first IoT pentest workflow. [web:13]

2. [Network Services](https://tryhackme.com/room/networkservices)  
   Covers core network service concepts and misconfigurations (e.g., FTP, SSH, SMB) that frequently appear in IoT and embedded devices exposed to the internet. [web:20]

3. [Cyber Kill Chain](https://tryhackme.com/room/cyberkillchain)  
   Explains the unified kill chain model and shows how compromised endpoints and IoT devices can be leveraged as proxies or pivot points in real attacks. [web:21]

4. [Introduction To Honeypots](https://tryhackme.com/room/introductiontohoneypots)  
   Introduces honeypots and how deliberately exposed services or IoT-like assets can be used to monitor attacker behaviour and collect telemetry. [web:16]

---

## IoT / embedded practical labs (Medium)

1. [Dumping Router Firmware](https://tryhackme.com/room/rfirmware)
   Practical lab on acquiring router firmware, unpacking images, and analysing the filesystem as a foundation for embedded and IoT exploitation work. [web:18]

---

## YARA-focused Rooms (TryHackMe)

1. [Yara](https://tryhackme.com/room/yara)  
   Core room teaching YARA syntax, rule structure (meta, strings, condition), and usage for malware/threat hunting. *(Premium room)*. [web:24]

2. [Threat Hunting With YARA](https://tryhackme.com/room/threathuntingwithyara)  
   Practical blue-team–oriented lab using YARA for hunting malicious artefacts on Windows, including writing and running custom rules. [web:25]

3. [YARA Rules - YARA mean one! (Advent of Cyber 2025)](https://tryhackme.com/room/yara-aoc2025-q9w1e3y5u7)  
   Advent of Cyber 2025 day focused on building a YARA rule to detect malicious images based on specific keywords and code words. [web:28]
