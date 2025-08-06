# Real-Time-Intrusion-Detection-System-IDS-
Python-based Intrusion Detection System (IDS) for real-time network traffic monitoring and threat detection. Detects SYN floods, ARP spoofing, and DNS spoofing using Scapy, with logging and alerting features
# 🛡️ PyIDS: Real-Time Intrusion Detection System with Python and Scapy

A lightweight, Python-based IDS designed to monitor live network traffic, detect suspicious patterns, and generate real-time alerts. Built for hands-on exploration of packet-level threat detection, this project simulates Tier 1 SOC workflows including SYN flood detection, ARP spoofing identification, and DNS spoofing validation.

---

## 📌 Project Objectives

- Capture and analyze live packets using Scapy
- Detect common attack signatures (SYN floods, ARP spoofing, DNS spoofing)
- Generate real-time alerts and log suspicious activity
- Simulate attacks to validate detection logic
- Showcase practical SOC skills in packet analysis and threat response

---

## 🧰 Tools & Technologies

| Tool / Tech        | Purpose                                                                 |
|--------------------|-------------------------------------------------------------------------|
| Python 3           | Core scripting language                                                 |
| Scapy              | Packet sniffing and protocol analysis                                   |
| tcpdump            | CLI-based packet capture                                                |
| Wireshark          | GUI-based packet inspection                                             |
| smtplib (Python)   | Email alerting for suspicious activity                                  |

---

## 🧪 Detection Modules

### 🔹 SYN Flood Detection
- Monitors TCP packets with SYN flag
- Tracks frequency and source IPs
- Alerts on abnormal bursts

### 🔹 ARP Spoofing Detection
- Inspects ARP replies
- Flags inconsistent IP–MAC mappings

### 🔹 DNS Spoofing Detection
- Validates domain-IP pairs
- Alerts on suspicious responses

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install scapy
