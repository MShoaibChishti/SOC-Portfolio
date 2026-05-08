# 🎣 Project 2 — Phishing Domain Analysis

## Overview
Investigated a real-world phishing domain impersonating 
PayPal financial services targeting Dutch/Belgian users.

## Target Domain
| Field | Details |
|---|---|
| Domain | paypal-opladen.be |
| Verdict | MALICIOUS — Confirmed Phishing |
| Threat Type | PayPal Credential Theft |
| Targets | Dutch/Belgian users |

## Tools Used
| Tool | Purpose |
|---|---|
| VirusTotal | Domain reputation — 5/92 vendors flagged |
| AbuseIPDB | IP reputation check — 82.201.58.154 |
| WHOIS | Registration analysis — active since 2015 |
| DNS Analysis | Infrastructure mapping |
| MITRE ATT&CK | Technique mapping — T1566.002 |

## Key Findings
- 5/92 security vendors flagged as malicious
- Hosting IP: 82.201.58.154 (Netherlands)
- Domain registered since March 2015
- Fake PayPal mail server infrastructure
- Spoofed PayPal nameservers for legitimacy
- Anonymized registrant to avoid takedown

## MITRE ATT&CK
- Tactic: TA0001 — Initial Access
- Technique: T1566 — Phishing
- Sub-technique: T1566.002 — Spearphishing Link

## Analyst
Muhammad Shoaib Chisti | SOC Analyst
