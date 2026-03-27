# 🌐 Network Analysis with Wireshark & Nmap

## 📌 Overview
In this project, I explored how network traffic and system information can be analyzed using Wireshark and Nmap.

My goal was to understand how much information can be gathered from a network and why monitoring and securing that information is important.

---

## ⚙️ What I Did

I used two main tools:

- **Wireshark** to capture and analyze live network traffic  
- **Nmap** to scan the network and identify devices, open ports, and services  

By combining these tools, I was able to:
- Identify devices on the network  
- Observe how they communicate  
- Understand potential security risks  

---

## 🧪 Environment Setup

I set up three virtual machines:

- Windows Server  
- Linux Server (Ubuntu)  
- Kali Linux (used for scanning and monitoring)  

All scans and traffic captures were performed from the Kali machine.

---

## 🔍 Approach

To complete this analysis, I:

- Identified IP addresses for each device  
- Ran Nmap scans to detect open ports, operating systems, and services  
- Captured network traffic using Wireshark  
- Filtered and analyzed packets (e.g., TCP traffic)  
- Matched scan results with live traffic data  
- Collected MAC addresses and device details  

---

## 📊 Key Findings

Through this analysis, I:

- Identified multiple active devices on the network  
- Discovered open ports such as:
  - **80 (HTTP)**  
  - **21 (FTP)**  
  - **3306 (MySQL)**  
- Observed real communication between devices using TCP handshakes  
- Matched Nmap scan results with Wireshark packet data  
- Confirmed how much system and network information can be exposed during scans  

---

## 🎯 Why This Matters

This project helped me understand that:

- Even a basic network scan can reveal detailed system information  
- Open ports can expose services that may be vulnerable  
- Network traffic contains valuable insights into system behavior  
- Using multiple tools together provides better visibility than using one alone  

---

## 🛠️ Tools & Technologies

- **Wireshark:** packet capture and traffic analysis  
- **Nmap:** network scanning and discovery  
- **Kali Linux:** testing environment  
- **VirtualBox:** virtual machine setup  

---

## 🔄 Workflow Summary

1. Set up virtual machines  
2. Identified IP addresses of each device  
3. Ran Nmap scans across the network  
4. Captured traffic using Wireshark  
5. Analyzed packets and communication patterns  
6. Matched scan results with observed activity  
7. Documented findings  

---

## 🖼️ Sample Observations

- Devices communicating over port 80 (web traffic)  
- TCP 3-way handshake confirming active connections  
- MAC address identification from packet data  
- Cross-verification between Nmap results and Wireshark captures  

---

## 🚀 Future Improvements

If I were to extend this project, I would:

- Segment the network to reduce exposure  
- Close or secure unnecessary open ports  
- Implement continuous network monitoring  
- Add alerting for unusual traffic patterns  
- Perform more targeted scans instead of full network scans  

---

## 🔐 Security Value

This project demonstrates my ability to:

- Discover devices and services on a network  
- Analyze real network traffic  
- Identify potential exposure points  
- Validate findings across multiple tools  
- Build a stronger understanding of network security fundamentals  

---

## 📄 Full Report

See the full detailed analysis and screenshots here:  
👉 :contentReference[oaicite:0]{index=0}






