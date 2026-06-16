# 🕵️‍♂️ Unveiling the Secrets of Network Traffic with Wireshark: A Hands-On Project Journey!

🔍 **Welcome to my packet analysis project!**  
This repository showcases my practical exploration of **malware PCAP File samples** using the industry-standard tool: **Wireshark**. The project highlights how packets tell stories of what's happening under the hood of the internet.

---

##  Project Overview

Wireshark is one of the most powerful tools for examining what’s going on in your network at a microscopic level. In this hands-on project, I practiced:

- I analyzed two captured real-time network traffic 
- Applying filters to isolate specific protocols 
- Analyzing packet structures at multiple layers 
- Identifying signs of unusual or malicious behavior 

---

## 🛠️ Tool Used: 
 
### Wireshark

🧰 **Wireshark** is a **network protocol analyzer** used to capture and examine packets traveling through a network. Here's what it allows you to do:

-  Select an active network interface (Wi-Fi, Ethernet, etc.)
-  Start capturing live network traffic
-  Apply display filters to narrow down analysis (e.g., `http`, `tcp.port == 80`, `ip.addr == 192.168.1.1`)
-  Inspect individual packets across layers:
  - Ethernet
  - IP
  - TCP/UDP
  - Application-level protocols (HTTP, DNS, FTP, etc.)

### VirusTotal

🧰 **VirusTotal** is an **online threat intelligence and malware analysis platform** used to scan files, URLs, IP addresses, domains, and hashes against multiple security engines. Here's what it allows you to do:

-  Upload files for malware analysis
-  Scan URLs to check for phishing, malware, or malicious content
-  Search using file hashes (MD5, SHA1, SHA256)
-  Investigate IP addresses and domains for malicious activity
-  view detections from dozens of antivirus vendors in one place
-  Analyze relationships between files, domains, IPs, and URLs

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
| `pcap-files/` | 📂 Directory containing`.pcap` files, [forest park school.pcap](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/Forest%20Park%20School.pcap), [holiday_agency_evidence.pcap](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/holiday_agency_evidence.pcap.zip)|
| `.docx` | 🧪 [A report detailing an overview of the analysis conducted on the network traffic from both `.pcap` files using Wireshark ](https://github.com/Tmitchy/wireshark-traffic-Exploration/blob/main/Network%20Packet%20Analysis%20Report.docx) |


---

## Security Concepts Involved

- **Packet Analysis**  
- **Protocol Inspection (TCP/IP, DNS, HTTP, etc.)**  
- **Network Forensics**  
- **Threat Detection & Network Anomaly Identification**

---

## Resources Used

- [Packetlife.net Cheat Sheets](https://packetlife.net/library/cheatsheets/)  
- YouTube tutorials from [Chris Greer](https://www.youtube.com/@ChrisGreer)

---
# Conclusion

This project has established a foundation for understanding the critical importance of implementing security measures against cyberattacks. It emphasizes the risks associated with not securing our network and highlights both the technical and non-technical aspects of security. The project also explored several open-source tools, such as Wireshark, Nmap, and Linux VM, which are utilized for scanning vulnerabilities and detecting malicious content.
While the traffic associated with "holiday_agency_evidence.zip" does not indicate any immediate security threats, the traffic related to the Forest Park School PCAP reveals security issues that were identified during the analysis. Additionally, addressing the recent security breach and preparing for potential future threats requires a comprehensive strategy that combines advanced technical defenses with robust governance, policies, and employee awareness.
Only through this multi-layered approach can Caribex build resilience against evolving cyber threats.


