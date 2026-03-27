# 🌐 Network Analysis with Wireshark & Nmap

## 📌 Overview
This project explores how network traffic and system information can be analyzed using Wireshark and Nmap.

The goal is to understand how much information can be gathered from a network and why monitoring and securing that information is important.

---

## ⚙️ What This Project Does

This analysis combines two tools:

- **Wireshark** → captures and analyzes live network traffic  
- **Nmap** → scans the network to identify devices, open ports, and services  

Together, they provide a clearer picture of:
- What devices are on the network  
- How they communicate  
- What potential risks may exist  

---

## 🧪 Environment Setup

The analysis was performed using three virtual machines:

- Windows Server  
- Linux Server (Ubuntu)  
- Kali Linux (used for scanning and monitoring)  

All scans and traffic captures were performed from the Kali machine.

---

## 🔍 Approach

This project followed these steps:

- Identified device IP addresses across the network  
- Ran Nmap scans to detect:
  - Open ports  
  - Operating systems  
  - Active services  
- Captured network traffic using Wireshark  
- Matched scan results with live traffic data  
- Analyzed communication patterns (e.g., TCP handshakes)  
- Collected MAC addresses and device details  

---

## 📊 Key Findings

- Identified multiple active devices on the network  
- Discovered open ports such as:
  - **80 (HTTP)**  
  - **21 (FTP)**  
  - **3306 (MySQL)**  
- Observed real communication between devices using TCP handshakes  
- Matched Nmap scan results with Wireshark packet data  
- Confirmed how much system and network information is exposed during scans  

---

## 🎯 Why This Matters

This project highlights that:

- Even a basic network scan can reveal detailed system information  
- Open ports can expose services that may be vulnerable  
- Network traffic contains valuable data about communication patterns  
- Combining tools provides stronger visibility than using one alone  

Understanding this helps organizations:
- Identify potential vulnerabilities  
- Monitor network activity more effectively  
- Strengthen overall security posture  

---

## 🛠️ Tools & Technologies

- **Wireshark:** packet capture and traffic analysis  
- **Nmap:** network scanning and discovery  
- **Kali Linux:** testing environment  
- **VirtualBox:** virtual machine setup  

---

## 🔄 Workflow Summary

1. Set up virtual machines  
2. Identify IP addresses of each device  
3. Run Nmap scans across the network  
4. Capture traffic using Wireshark  
5. Filter and analyze packets (e.g., TCP traffic)  
6. Match scan results with observed network activity  
7. Document findings  

---

## 🖼️ Sample Observations

- Devices communicating over port 80 (web traffic)  
- TCP 3-way handshake confirming active connections  
- MAC address identification from packet data  
- Cross-verification between Nmap results and Wireshark captures  

---

## 🚀 Future Improvements

- Segment the network to limit exposure  
- Close or secure unnecessary open ports  
- Implement continuous network monitoring  
- Add alerting for unusual traffic patterns  
- Perform more targeted scans instead of full network scans  

---

## 🔐 Security Value

This project demonstrates how to:

- Discover devices and services on a network  
- Analyze real network traffic  
- Identify potential exposure points  
- Validate findings across multiple tools  
- Build a stronger understanding of network security fundamentals  

---

## 📄 Full Report

See full detailed analysis and screenshots here:  
👉 :contentReference[oaicite:0]{index=0}







Recommended Screenshots 
