# Elevate-labs-task1

**Network Port Scanning & Vulnerability Assessment**  
*Completed: 04/08/2025 • Biswojeet Barik*

## Overview
This task shows network scanning skills:
Scanning local network (192.168.138.0/24) for open ports using Nmap tool
Identifying services on open ports and their vulnerabilities

## Tools used:
-**Nmap** :- Network scanning and Vulnerability detection
-**Wireshark** :- For capturing packets of scanning
-**Github** :- For documentation

.Network range - 192.168.138.0/24

# Sync scan:
nmap -sS 192.168.138.0/24 -o sync_scan.txt

# Script scan and service version detection: 
## nmap -sS -sV -sC 192.168.138.128 -o 192.168.138.128.txt
## nmap -sS -sV -sC 192.168.138.130 -o 192.168.138.130.txt
## All script scan file are present in .txt files

**Open Ports and services**
## For 192.168.138.128
<img width="459" height="463" alt="Screenshot_3" src="https://github.com/user-attachments/assets/b2bd4514-7247-47d2-8cc9-0edb44a4586e" />

## For 192.168.138.130
<img width="740" height="333" alt="Screenshot_4" src="https://github.com/user-attachments/assets/fc1d0068-806d-4ba1-82ed-9ffe7690cea7" />

# Recomendation

Use patch Management for every service and use the latest version of it.
