# 📡 NetGuard // Real-Time Network Packet Inspector

> **A modern, threaded network traffic analyzer built with Python, Scapy, and CustomTkinter.**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Networking](https://img.shields.io/badge/Lib-Scapy-red)
![GUI](https://img.shields.io/badge/UI-CustomTkinter-green)

## 📖 Overview

**NetGuard** is a graphical network packet sniffer that acts as a lightweight alternative to Wireshark. It allows security researchers and students to intercept, view, and analyze network traffic in real-time.

Unlike standard command-line sniffers, NetGuard features a **Dark Mode GUI** with a threaded backend, ensuring the application remains responsive even during high-traffic capture sessions. It includes deep-packet inspection capabilities, allowing users to drill down into the raw payload and headers of every captured frame.


*(Add a screenshot of your tool running here)*

---

## ✨ Key Features

* **⚡ Real-Time Capture:** Sniff TCP, UDP, and ICMP packets as they traverse your network interface.
* **🔍 Deep Inspection:** Click any row to view the full packet breakdown (Hex dump, Flags, Options, Payload).
* **🎨 Hybrid UI:** Combines modern `CustomTkinter` controls with a custom-styled, dark-mode data grid.
* **🛡️ BPF Filtering:** Supports standard Berkeley Packet Filters (e.g., `tcp port 80` or `host 192.168.1.5`).
* **🧵 Multi-Threaded:** The sniffing engine runs on a daemon thread, preventing UI freezes.

---

## 🛠️ Prerequisites & Installation

### 1. System Requirements
* **Python:** 3.8 or higher.
* **Windows:** You must install **[Npcap](https://npcap.com/#download)** (Select "Install in API-compatible Mode").
* **Linux/Mac:** You must have `sudo` / root privileges to capture traffic.

### 2. Install Dependencies
```bash
pip install customtkinter scapy
