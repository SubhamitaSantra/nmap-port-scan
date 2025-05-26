# Nmap Network Scan

This repository contains the results and analysis of a local network scan using **Nmap**.

## Task Overview
- Performed a **TCP SYN scan** on the local network using `nmap`.
- Targeted the IP range: `192.168.1.0/24`
- Saved output to `scan_results.txt`.
- Identified active devices, open ports, and potential security risks.

## 🔍 Command Used
```bash
sudo nmap -sS -oN scan_results.txt 192.168.1.0/24
