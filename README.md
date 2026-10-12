# Cybersecurity Lab: Private Range Setup & Network Reconnaissance

## Project Overview
This project demonstrates the deployment of an isolated, virtual cyber range used to safely simulate enterprise network environments. The primary objective was to configure a secure network architecture separating an attacker environment (**Kali Linux**) from an endpoint target (**Windows 10**), perform connectivity troubleshooting via firewall optimization, and execute stealth reconnaissance using **Nmap**.

## Core Objectives
* **Virtualization Architecture:** Deploy and isolate multiple operating systems using a secure hypervisor network interface.
* **Endpoint Defensive Configuration:** Modify Windows Defender Advanced Firewall rules to safely facilitate internal lab communication without exposing endpoints to the internet.
* **Network Mapping:** Conduct active reconnaissance to map open ports, discover network services, and perform OS fingerprinting.

## Environment Architecture & Configuration
Configured both virtual machines to share an isolated **Host-Only** network adapter to keep traffic separate from the home network infrastructure.

### Kali Linux Adapter Setup:
<img width="1366" height="768" alt="network-setup png" src="https://github.com/user-attachments/assets/de063329-7b4d-46d0-9bc2-9def53392fbd" />


### Windows 10 Adapter Setup:
<img width="1366" height="768" alt="network-setups png" src="https://github.com/user-attachments/assets/d4621129-67c2-4e40-bcd9-48be7ded069f" />


## 🔍 Nmap Scan Execution & Results
Executed an active SYN stealth scan to map active services and attempt OS fingerprinting.

<img width="1366" height="691" alt="Nmap-results" src="https://github.com/user-attachments/assets/76ee87b7-871f-47f1-abee-87d26495b2bc" />

# MyCybersecurity-Portfolio
Personal cybersecurity home lab and hands-on project write-ups demonstrating network security, threat analysis, and defense concepts.
