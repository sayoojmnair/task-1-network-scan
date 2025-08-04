# Task 1: Scan Your Local Network for Open Ports

## 🎯 Objective
To discover open ports on devices in the local network using Nmap, and understand potential service exposures.

## 🧰 Tools Used
- Kali Linux (in VirtualBox)
- Nmap
- (Optional) Wireshark

## 🔍 Scan Command Used
```bash
sudo nmap -sS 192.168.81.99/24 -oN scan_result.txt
