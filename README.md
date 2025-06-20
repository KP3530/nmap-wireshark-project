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

### Command Used
```bash
nmap -sS -sV -Pn <target-ip>
