# 🔍 Nmap Local Network Port Scan Lab

This repository contains the results and artifacts of scanning a local network for open ports using **Nmap**, and analyzing packet traffic using **Wireshark**.

---

## 📚 Project Objective

To discover open ports on a local device (IP: `192.168.0.105`) using Nmap, understand the type of services running, and capture packet-level traffic using Wireshark.

---

## 🧰 Tools Used

- 🛠️ **Nmap** – Network port scanning
- 🧪 **Wireshark** – Packet analysis
- 🌐 **Python3 HTTP Server** – Hosted on port 80
- 📡 **Netcat** – Listener on port 1234
- 💻 **Kali Linux (VirtualBox, Bridged Mode)**

---

## 📝 Procedure Summary

1. Identified the local IP of target device.
2. Performed initial scans with:
   ```bash
   nmap -sS 192.168.0.105
   nmap -p- -sS 192.168.0.105
# nmap-port-scan-lab
Nmap scan of local network, port discovery, Wireshark analysis
