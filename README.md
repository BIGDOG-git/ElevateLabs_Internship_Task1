# 🔍 Nmap Network Scan and Wireshark Packet Analysis

This project demonstrates a basic internal network scan using **Nmap** and optional packet-level inspection using **Wireshark**. The goal is to identify active hosts, open ports, and potential vulnerabilities within a local subnet (e.g., `192.168.1.0/24`).

---

## 🧪 Objectives

- Perform a TCP SYN scan to find open ports on devices in a local network.
- Identify common services and assess potential risks.
- Optionally analyze traffic using Wireshark.
- Save scan results for reporting and further analysis.

---

## 🛠️ Tools Used

- **Nmap** – Network discovery and port scanning tool.
- **Wireshark** – Packet analyzer for network protocol inspection.
- **Operating System** – Linux (kali)

---

 ## Port Service	⚠️ Potential Threats
21	FTP	- Unencrypted credentials
- Brute force attacks
- Anonymous login access
- Remote Code Execution (RCE) in outdated FTP servers
53	DNS	- DNS amplification (DDoS)
- Zone transfer data leakage
- Internal info exposure
- Cache poisoning
80	HTTP	- Unencrypted traffic
- XSS, SQL injection, RCE in vulnerable web apps
- Sensitive data exposure
- Server fingerprinting
443	HTTPS	- SSL/TLS misconfiguration
- Use of weak or deprecated protocols (e.g., SSLv3, TLS 1.0)
- Expired or invalid certificates
- Vulnerabilities like Heartbleed (if OpenSSL is outdated)

- ---
