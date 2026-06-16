# 🕵️‍♂️ Unveiling the Secrets of Network Traffic with Wireshark: A Hands-On Project Journey!

🔍 **Welcome to my packet analysis project!**  
This repository showcases my practical exploration of **malware PCAP File samples** using the industry-standard tool: **Wireshark**. The project highlights how packets tell stories of what's happening under the hood of the internet.

---

##  Project Overview

Wireshark is one of the most powerful tools for examining what’s going on in your network at a microscopic level. In this hands-on project, I practiced:

- Capturing real-time network traffic 
- Applying filters to isolate specific protocols 
- Analyzing packet structures at multiple layers 
- Identifying signs of unusual or malicious behavior 

---

## 🛠️ Tool Used: Wireshark

🧰 **Wireshark** is a **network protocol analyzer** used to capture and examine packets traveling through a network. Here's what it allows you to do:

-  Select an active network interface (Wi-Fi, Ethernet, etc.)
-  Start capturing live network traffic
-  Apply display filters to narrow down analysis (e.g., `http`, `tcp.port == 80`, `ip.addr == 192.168.1.1`)
-  Inspect individual packets across layers:
  - Ethernet
  - IP
  - TCP/UDP
  - Application-level protocols (HTTP, DNS, FTP, etc.)

---

## 🎯 What I Learned

This project has taught me critical foundational skills in cybersecurity and network engineering:

- How data flows across a network and how protocols interact  
- How to filter and follow conversations between devices  
- How to detect anomalies like:
  - Malicious payloads  
  - Port scans  
  - Unusual IP traffic patterns  
- Real-world usage of Wireshark for:
  - Network troubleshooting  
  - Intrusion detection  
  - Protocol reverse engineering  

---

## Project Files

Inside this repository, you'll find:

| File/Folder | Description |
|-------------|-------------|
| `pcap-analysis/` | 📂 Directory containing analyzed `.pcap` files and notes |
| `screenshots/` | 🖼️ [Captures of Wireshark during packet inspection](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/Network%20Packet%20Analysis%20Report.docx) |
| `filters.md` | 🧪 [Useful Wireshark display filters I used](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/Network%20Packet%20Analysis%20Report.docx) |
| `findings.md` | 📓 [Document of my observations and key learning moments](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/Network%20Packet%20Analysis%20Report.docx) |

---

## Security Concepts Involved

- **Packet Analysis**  
- **Protocol Inspection (TCP/IP, DNS, HTTP, etc.)**  
- **Network Forensics**  
- **Threat Detection & Network Anomaly Identification**

---

## Resources Used

- [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
- [Packetlife.net Cheat Sheets](https://packetlife.net/library/cheatsheets/)
- TryHackMe: *Wireshark* and *Intro to Networking* rooms  
- YouTube tutorials from [Chris Greer](https://www.youtube.com/@ChrisGreer)

---

## Next Steps

- Analyze more complex `.pcap` files (including malware samples)
- Build lab environments with simulated attacks
- Combine Wireshark analysis with IDS tools like **Snort** or **Zeek**

---

> “To master cybersecurity, you must learn to think like the packets.”  
> - Me, after spending hours in Wireshark 😅

---
