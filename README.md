# networkwalks-week-two-project
Week 2 of my Cybersecurity Internship at Networkwalks, documenting practical exercises in footprinting, network reconnaissance, Nmap scanning and Zenmap topology mapping using Kali Linux.

# Cybersecurity Internship – Week 2

## Footprinting, Network Reconnaissance & Topology Mapping

This repository documents my Week 2 practical activities during my Cybersecurity Internship at **Networkwalks**.

The exercises focused on developing practical knowledge of footprinting, information gathering, network scanning and topology visualization using Kali Linux.

## Objectives

- Understand the fundamentals of footprinting and reconnaissance.
- Practise information gathering using cybersecurity tools.
- Perform network scanning using Nmap.
- Visualize discovered network hosts using Zenmap.
- Document practical findings and learning outcomes.

## Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| NSLookup | DNS resolution |
| cURL | HTTP response header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS enumeration |
| Nmap | Network scanning and host discovery |
| Zenmap | Network scan visualization and topology mapping |

## Practical Activities

### 1. Footprinting

Used WHOIS, WhatWeb, NSLookup, cURL, Wafw00f and DNSRecon to gather information about a selected domain and website.

### 2. Network Scanning

Performed a fast Nmap scan against the local subnet:

```bash
nmap -T4 -F 192.168.100.0/24
```

### 3. Network Topology Mapping

Used Zenmap's topology feature to visualize network hosts represented in the scan results.

## Repository Contents

- `reports/` – Detailed Week 2 practical report.
- `screenshots/` – Screenshots documenting practical activities.
- `tools/` – Notes about tools and commands used.

## Key Learning Outcomes

- Understanding footprinting and reconnaissance techniques.
- Familiarity with DNS and web technology information gathering.
- Understanding basic Nmap scanning operations.
- Visualizing network hosts through Zenmap.
- Improving technical documentation and reporting skills.

## Practical Report

The complete practical report is available in the `reports/` directory.

## Disclaimer

All activities were conducted for educational and cybersecurity training purposes. Scanning and reconnaissance should only be performed on systems and networks where proper authorization has been granted.

---

**Author:** Paul Andera  
**Programme:** Cybersecurity Internship  
**Organization:** Networkwalks  
**Project:** Week 2 Practical Activities

