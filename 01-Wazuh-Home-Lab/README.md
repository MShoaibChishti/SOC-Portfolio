# SOC-Portfolio
# 🛡️ Project 1 — Wazuh SOC Home Lab

## Overview
Simulated real-world cyber attacks on a home lab environment 
and detected them using Wazuh SIEM.

## Lab Environment
| Component | Details |
|---|---|
| SIEM | Wazuh v4.14.4 |
| Attacker | Kali Linux 2025.3 |
| Target | Windows 10 x64 |
| Virtualization | VMware Workstation |
| Network | 150.1.7.0/24 |

## Attacks Simulated
| # | Attack | Tool | Detection |
|---|---|---|---|
| 1 | Windows Brute Force | PowerShell | Wazuh Rule 60122 + Custom 100002 |
| 2 | TCP SYN Flood | PentMenu/hping3 | Wireshark — 939k packets captured |

## Custom Wazuh Rules Written
- Rule 100002 — Windows Brute Force Detection (Level 12)
- MITRE ATT&CK mapped: T1110, T1498

## Evidence
- Wazuh alerts screenshots
- Windows Event Viewer Event ID 4625
- Wireshark PCAP capture — 939,537 packets
- Professional incident reports

## Tools Used
Wazuh · Kibana · Wireshark · Kali Linux · 
VMware · Windows Event Viewer · PentMenu

## Analyst
Muhammad Shoaib Chisti | SOC Analyst
