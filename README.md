# 🔍 Nmap + Wireshark Local Network Scan

## 🧪 Project Overview
This project demonstrates how to perform a local network scan using **Nmap**, and how to capture and analyze the resulting traffic using **Wireshark**. The purpose is to understand what common Windows network services look like from both a port scanning and packet analysis perspective.

---

## 🛠 Tools Used
- **Kali Linux VM (VirtualBox)**
- **Nmap 7.95**
- **Wireshark**
- Target: A Windows device on the same Wi-Fi network

---

## 📡 Wireshark Traffic Analysis

What Was Observed:
TCP SYN packets were sent to ports 135, 139, and 445 from the scanning machine.

The target responded with SYN-ACK for open ports, confirming their availability.

RST packets were seen for filtered or closed ports.

No payload data was captured — all traffic was part of the TCP handshake or basic port checking.

Packets showed normal behavior for a SYN scan and were useful in identifying how Nmap interacts with TCP during a stealth scan (-sS).

---

## 🧠 Key Takeaways
Learned how to use Nmap for stealth and version detection scans on a local network.

Identified open ports on a Windows system and recognized their services.

Practiced capturing and filtering network traffic with Wireshark.

Gained hands-on experience reading TCP packet flags and understanding scan patterns.

---
