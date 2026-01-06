# TryHackMe IoT & Embedded Security Rooms

This section focuses on **IoT security**, **embedded firmware**, and the **networking foundations** required to understand and attack Internet of Things ecosystems. It starts with theoretical and networking concepts, then moves into hands-on labs involving firmware extraction, emulation, and practical IoT pentesting on TryHackMe.  

## Author

**Name:** Showkot Hosen  
**Institution:** Chittagong University of Engineering & Technology (CUET)  
**Department:** Electronics and Telecommunication Engineering (ETE), CUET  
**Affiliation:** Student and enthusiast in ML-based cybersecurity research | Cisco EH | TryHackMe AoC 2025 & Presecurity Path | ML Models for Cybersecurity  

---

## IoT foundations (Easy)

1. **Intro to IoT Pentesting** – [Intro to IoT Pentesting](https://tryhackme.com/room/iotintro)  
   Beginner-friendly overview of Internet of Things architectures, typical components, attack surfaces, and a guided first IoT pentest workflow. [web:13]

2. **Network Services** – [Network Services](https://tryhackme.com/room/networkservices)  
   Covers core network service concepts and misconfigurations (e.g., FTP, SSH, SMB) that frequently appear in IoT and embedded devices exposed to the internet. [web:20]

3. **Cyber Kill Chain** – [Cyber Kill Chain](https://tryhackme.com/room/cyberkillchain)  
   Explains the unified kill chain model and shows how compromised endpoints and IoT devices can be leveraged as proxies or pivot points in real attacks. [web:21]

4. **Introduction to Honeypots** – [Introduction To Honeypots](https://tryhackme.com/room/introductiontohoneypots)  
   Introduces honeypots and how deliberately exposed services or IoT-like assets can be used to monitor attacker behaviour and collect telemetry. [web:16]

---

## IoT / embedded practical labs (Medium)

1. **Dumping Router Firmware** – [Dumping Router Firmware](https://tryhackme.com/room/dumpingrouterfirmware)  
   Practical lab on acquiring router firmware, unpacking images, and analysing the filesystem as a foundation for embedded and IoT exploitation work. [web:18]

2. **rFirmware (Router Firmware Analysis)** – [rFirmware](https://tryhackme.com/room/rfirmware)  
   Focuses on automated and semi-automated firmware analysis using frameworks such as the Firmware Analysis Toolkit and Firmadyne to emulate and inspect router images. [web:18]

3. **Intro to IoT Pentesting (practical tasks)** – [Intro to IoT Pentesting](https://tryhackme.com/room/iotintro)  
   Later tasks in this room walk through interacting with emulated devices, enumerating exposed services, and identifying weaknesses specific to IoT stacks. [web:13]

---

## Advanced / harder IoT-adjacent content (Medium–Hard)

These rooms are not branded purely as IoT but strengthen skills that directly carry over to advanced embedded and IoT security testing.

1. **PWN101** – [PWN101](https://tryhackme.com/room/pwn101)  
   Binary exploitation training that builds exploitation and debugging skills commonly required when dealing with low-level vulnerabilities in embedded/IoT firmware and services. [web:2]

2. **Windows Reversing Intro** – [Windows Reversing Intro](https://tryhackme.com/room/windowsreversingintro)  
   Provides reverse engineering and debugger experience that translates to analysing native binaries running on IoT gateways or embedded systems. [web:7]

3. **Dumping Router Firmware (deeper analysis)** – [Dumping Router Firmware](https://tryhackme.com/room/dumpingrouterfirmware)  
   When revisited with more experience, this room becomes a harder exercise in manually navigating firmware filesystems and identifying misconfigurations, credentials, or hidden services. [web:18]

