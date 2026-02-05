# Snort Intrusion Detection System (IDS) Project

## Overview
This project demonstrates the implementation of **Snort as an Intrusion Detection System (IDS)** to detect multiple real-world network attacks using **custom Snort rules**.

The project was completed as part of a Cyber Security course and includes attack simulations, rule creation, and alert analysis.

## Tools & Technologies
- Snort IDS
- Ubuntu Linux
- hping3
- nmap
- hydra
- arpspoof
- curl
- TCP/IP Networking

## Attack Scenarios Covered
- DDoS / DoS attacks
- SQL Injection
- Port Scanning
- Man-in-the-Middle (ARP Spoofing)
- SSH Brute Force Attacks
- ICMP Flood / Large Packet Attacks
- Cross-Site Scripting (XSS)

## Custom Snort Rules
All detection logic is implemented using **custom Snort rules**, located in the `rules/` directory.

Each rule is designed to:
- Detect malicious patterns
- Minimize false positives
- Trigger real-time alerts

## Attack Simulation
Attacks were generated using tools such as:
- `hping3` for flooding attacks
- `nmap` for port scanning
- `hydra` for brute-force SSH
- `arpspoof` for MITM attacks
- `curl` for SQLi and XSS payloads

## Results
Snort successfully detected all simulated attacks and generated alerts in real time.  
Some false positives were observed, highlighting the importance of fine-tuning IDS rules.

## Report
A detailed project report with screenshots and analysis is available in:

## Authors
- Umar Niazi  
- Eman Zafar Raja
