# 🛡️ Ethical Hacking Exam Report

This repository documents the work done during my *Ethical Hacking* exam, where I used Kali Linux and a variety of tools to perform hands-on exercises across different categories of attacks and analysis.

---

## 🧰 Tools Used

The following tools were used during the exam:

- **Kali Linux** – Main penetration testing distribution.
- **ASN Lookup / ViewDNS.info / who.is / crt.sh** – Tools for domain and IP reconnaissance.
- **Nmap** – Network mapping and port scanning.
- **Dirb** – Web content discovery (hidden files and directories).
- **Burp Suite** – HTTP(S) traffic interception, analysis, and manipulation.
- **GDB + GEF** – Debugging and binary exploitation framework.

---

## 🧪 Exercise Categories

The exam was divided into five main categories:

### 1. 🔍 Technical Information Gathering
Collected technical data about infrastructure, domains, and public IPs using:
- ASN lookup
- ViewDNS.info
- who.is
- crt.sh (for analyzing public SSL certificates)

### 2. 🌐 Network Mapping
Mapped target networks using:
- Nmap for port scanning, service/version detection, and OS fingerprinting
- Analysis of open ports and exposed services

### 3. 🕸️ Web Hacking
Performed vulnerability assessments on web applications with:
- Dirb for brute-forcing hidden directories and files
- Burp Suite for request interception, parameter tampering, and vulnerability testing

### 4. 🕵️ OSINT (Open Source Intelligence)
Gathered sensitive information from public sources:
- Metadata analysis
- WHOIS and DNS records lookup
- SSL certificate enumeration via crt.sh

### 5. 💣 Binary Exploitation
Exploited vulnerable binaries through:
- Debugging with GDB
- Advanced inspection using GEF (GDB Enhanced Features)
- Stack analysis, buffer overflows, and basic shellcode techniques

---

## 📌 Disclaimer

All tests were conducted in controlled, ethical environments for educational purposes only.  
⚠️ **This project is strictly for learning and ethical hacking practice.**
