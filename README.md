# Cybersecurity Lab: Private Range Setup & Network Reconnaissance

## 📌 Project Overview
This project demonstrates the deployment of an isolated, virtual cyber range used to safely simulate enterprise network environments. The primary objective was to configure a secure network architecture separating an attacker environment (**Kali Linux**) from an endpoint target (**Windows 10**), perform connectivity troubleshooting via firewall optimization, and execute stealth reconnaissance using **Nmap**.

## 🎯 Core Objectives
* **Virtualization Architecture:** Deploy and isolate multiple operating systems using a secure hypervisor network interface.
* **Endpoint Defensive Configuration:** Modify Windows Defender Advanced Firewall rules to safely facilitate internal lab communication without exposing endpoints to the internet.
* **Network Mapping:** Conduct active reconnaissance to map open ports, discover network services, and perform OS fingerprinting.

## 💻 Environment Architecture & Configuration
Configured both virtual machines to share an isolated **Host-Only** network adapter to keep traffic separate from the home network infrastructure.

### Kali Linux Adapter Setup:
![Kali Linux Virtual Network Configuration](<img width="1366" height="768" alt="network-setup png" src="https://github.com/user-attachments/assets/8518ce5a-8c9e-4450-8431-dcde0a1a138f" />)

### Windows 10 Adapter Setup:
![Windows 10 Virtual Network Configuration](<img width="1366" height="768" alt="network-setups png" src="https://github.com/user-attachments/assets/18d3bec7-ec0f-49a9-8b40-76bf2514d63d" />)

## 🔍 Nmap Scan Execution & Results
Executed an active SYN stealth scan to map active services and attempt OS fingerprinting.

![Nmap Terminal Output Scan](<img width="1366" height="691" alt="Nmap-results" src="https://github.com/user-attachments/assets/7c3512b5-7c6a-49f5-8c09-b3b1c2843577" />)
# MyCybersecurity-Portfolio
Personal cybersecurity home lab and hands-on project write-ups demonstrating network security, threat analysis, and defense concepts.
