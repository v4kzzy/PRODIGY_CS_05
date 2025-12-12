# Network Packet Analyzer 🔍

A Python-based GUI tool to capture and analyze network traffic. This tool was developed as part of the **Prodigy InfoTech Cybersecurity Internship (Task 05)**.

It uses `scapy` for packet sniffing and `ttkbootstrap` for a modern, dark-themed user interface.

## 🚀 Features
- **Real-time Packet Capture:** Sniffs network traffic on the fly.
- **Protocol Analysis:** Identifies TCP, UDP, and ICMP packets.
- **Payload Preview:** Shows a snippet of the data payload (first 20 bytes).
- **GUI Interface:** Start/Stop controls and a sortable data table.
- **Multi-threading:** Keeps the interface responsive while sniffing.

## 🛠️ Prerequisites (Windows)
To run this tool on Windows, you **must** have the Npcap driver installed. Python cannot access the network card without it.

1. **Download Npcap:** [https://npcap.com/#download](https://npcap.com/#download)
2. **Install:** During installation, check the box:  
   `"Install Npcap in WinPcap API-compatible Mode"`

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone
