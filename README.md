# Cybersecurity_Roadmap
🛡️ Cybersecurity Roadmap (Beginner → Junior Analyst / Ethical Hacker)

![6 Months Cybersecurity Roadmap](roadmap2.png)


**Figure: 6 Months Cybersecurity Roadmap**

# Cybersecurity Roadmap – From Zero to Junior Analyst / Ethical Hacker

Welcome to the **Cybersecurity Roadmap** – a complete, beginner‑friendly learning path designed to take you from zero knowledge to **SOC Analyst** or **Ethical Hacker** using mostly free and minimal‑cost resources. This roadmap is structured, practical, and focused on **real‑world skills** and **hands‑on labs**.

---

## 🎯 Who This Roadmap Is For

- Students starting cybersecurity from scratch  
- Beginners with no formal IT background  
- Anyone aiming to become a **Junior Cybersecurity Analyst** or **Ethical Hacker**  
- Learners who want a **clear, free, and structured** study plan  

---

## 🧩 Roadmap Overview

The roadmap is divided into the following stages:

1. **Cybersecurity Introduction**  
2. **Fundamentals** (Networking, Operating Systems, Linux)  
3. **Programming for Cybersecurity**  
4. **Hands‑on Labs with TryHackMe**  
5. **Specialized Tracks & Thematic Room Lists**  
   - IoT Security  
   - Multimedia & Steganography  
   - Networking & Wireless  
   - Reverse Engineering & Malware Analysis  
   - AI/ML Security  
   - FAQ  
6. **FAQ – Frequently Asked Questions (Overview)**

All links are intended to be **clickable** and oriented around **free or low‑cost** content wherever possible.

---

## 1. Cybersecurity Introduction

Start here if you are completely new.

- What is cybersecurity?  
- Types of roles: **SOC Analyst, Pentester, Malware Analyst, DFIR**, etc.  
- Basic terminology: threat, vulnerability, exploit, risk, CIA triad.

Recommended starting points:
- High‑level intro videos or blogs from vendors (Cisco, Microsoft, OWASP, etc.).  
- Awareness of common attack types: **phishing, malware, brute force, web attacks**.

---

## 2. Fundamentals (Networking, OS, Linux)

Before deep hacking or SOC work, get solid foundations.

### Networking

- Understand: IP addressing, ports, protocols (TCP/UDP/HTTP/DNS), OSI model, routing, subnets.  
- Practice: reading diagrams, tracing packets logically.

### Operating Systems

- Windows basics: services, users, permissions, event logs.  
- Linux basics: filesystem, users/groups, permissions, processes, systemd.

### Linux for Security

- Command line usage  
- File operations, grep, pipes, redirection  
- Basic bash scripting  

---

## 3. Programming for Cybersecurity

You do not need to be a software engineer, but basic coding helps everywhere.

Recommended focus:

- **Python** for automation, tooling, and basic offensive/defensive scripts  
- Understanding of:
  - Variables, loops, conditions  
  - Functions and modules  
  - Working with files and simple sockets/HTTP

Optional but useful:

- Basic **JavaScript** for web security  
- Basic **Bash** scripting for automation on Linux  

---

## 4. Hands‑On Labs (TryHackMe Focus)

Once you have core fundamentals, start structured practice with hands‑on labs.

### Suggested Flow

1. **Pre‑Security & Introductory Paths**  
   - Basic Linux, basic web, basic networking  
2. **Complete Beginner / Junior Penetration Tester / SOC Level Paths**  
   - Web exploitation basics  
   - Enumeration and privilege escalation  
   - Basic incident response and analysis  

Use these rooms and paths to build muscle memory and get used to real tools:
- `nmap`, `ssh`, `hydra`, `wireshark`, `tcpdump`, `burpsuite`, basic scripting, etc.

---

## 5. Thematic TryHackMe Room Collections

These sections are implemented as **separate `.md` files** in your repo, each dedicated to a specific area. This central roadmap links to them so you can navigate everything from one place.

### 5.1 IoT THM Rooms

Focus: **IoT security, embedded devices, router firmware, and IoT networking**.

- Introductory IoT theory  
- Networking structures around IoT  
- Practical labs: router firmware dumping, emulation, basic IoT pentesting  

Open the full list here:  
👉 [IoT THM Rooms](./IoT%20THM%20Rooms.md)

---

### 5.2 Multimedia & Steganography Rooms

Focus: **images, audio, and file‑based steganography** + multimedia CTFs.

- Core dedicated stego rooms  
- CTFs with heavy stego elements  
- Image/audio analysis challenges  
- Good for building a toolkit: `steghide`, `exiftool`, `zsteg`, `binwalk`, etc.

Open the full list here:  
👉 [Multimedia and Steganography THM Rooms](./Multimedia%20and%20Steganography%20THM%20Rooms.md)

---

### 5.3 Networking & Wireless Communication Rooms

Focus: from **basic networking labs** to **wireless (Wi‑Fi) hacking** and more advanced traffic analysis.

Typical content:

- Introductory networking  
- LAN concepts and service enumeration  
- Network traffic basics and PCAP analysis  
- Network security essentials and firewall/log analysis  
- Wi‑Fi Hacking 101 and wireless‑specific attacks  

Open the full list here:  
👉 [Networking and Wireless Communication THM Rooms](./Networking%20and%20Wireless%20Communication%20THM%20Rooms.md)

---

### 5.4 Reverse Engineering & Malware Analysis Rooms

Focus: **reverse engineering**, **assembly**, and **malware analysis**.

Sub‑sections:

- Reverse engineering foundations  
  - Windows reversing intro, x86/x64 assembly, JVM reversing, PE headers, ELF reversing, firmware dumping  
- Malware analysis module rooms  
  - Basic/Advanced Static Analysis  
  - Basic Dynamic Analysis & Debugging  
  - Anti‑RE, MalBuster, MalDoc, Windows Internals  
- Binary exploitation and RE‑adjacent content  
  - PWN101, etc.

Open the full list here:  
👉 [Reverse_Engineering_and_Malware_Analysis_Rooms_THM](./Reverse_Engineering_and_Malware_Analysis_Rooms_THM.md)

---

### 5.5 AI & ML Security Rooms

Focus: **AI/ML concepts and security threats**.

Core example:

- `AI/ML Security Threats` – understanding AI vs ML vs DL vs LLMs, model lifecycle, adversarial ML, prompt injection, data poisoning, model theft, privacy leakage, model drift, and defensive use cases.

Open the full list here:  
👉 [THM Ai-ML Related Rooms](./THM%20Ai-ML%20Related%20Rooms.md)

---

### 5.6 FAQ – Dedicated FAQ File

A separate FAQ file gives quick answers about study order, pacing, tools, and career direction.

Open it here:  
👉 [FAQ – Frequently Asked Questions](./FAQ-Frequently%20Asked%20Questions.md)

---

## 6. FAQ – Frequently Asked Questions (Overview)

This section is a brief inline overview. The **full, detailed version** lives in `FAQ-Frequently Asked Questions.md`.

### Q1. I’m a complete beginner. Where do I start?

- Cybersecurity introduction + basic networking and OS  
- Then Linux basics and introductory hands‑on labs  

### Q2. Do I need programming knowledge to begin?

- Not required to start, but basic **Python** and some scripting will boost you significantly later.  

### Q3. How should I use the themed room lists?

- Treat them as **mini‑specializations**  
- Start with Easy rooms inside each `.md`, then progress to Medium/Hard  

For more questions and detailed answers, see:  
👉 [FAQ – Frequently Asked Questions](./FAQ-Frequently%20Asked%20Questions.md)

---

## Central Index (Quick Navigation)

- [IoT THM Rooms](./IoT%20THM%20Rooms.md)
- [Multimedia and Steganography THM Rooms](./Multimedia%20and%20Steganography%20THM%20Rooms.md)
- [Networking and Wireless Communication THM Rooms](./Networking%20and%20Wireless%20Communication%20THM%20Rooms.md)
- [Reverse Engineering and Malware Analysis Rooms (THM)](./Reverse_Engineering_and_Malware_Analysis_Rooms_THM.md)
- [THM Ai-ML Related Rooms](./THM%20Ai-ML%20Related%20Rooms.md)
- [FAQ – Frequently Asked Questions](./FAQ-Frequently%20Asked%20Questions.md)

---

## Author

**Name:** Showkot Hosen  
**Institution:** Chittagong University of Engineering & Technology (CUET)  
**Department:** Electronics and Telecommunication Engineering (ETE), CUET  
**Affiliation:** Student and enthusiast in ML‑based cybersecurity research | ISC2 CC | Cisco Ethical Hacker | TryHackMe AoC 2025 & Presecurity Path | ML Models for Cybersecurity

