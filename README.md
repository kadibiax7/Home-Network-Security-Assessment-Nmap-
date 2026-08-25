# Home Network Security Assessment (Nmap)

## Objective
Practiced core Nmap workflows against my own home network to build hands-on reconnaissance and vulnerability assessment skills relevant to SOC/GRC analyst roles.

## Skills Demonstrated
- Host discovery & network mapping
- Port scanning & service/version detection
- OS fingerprinting
- Vulnerability scanning (NSE scripts)
- Network inventory & risk-based asset tracking
- Firewall/security auditing
- Compliance-baseline checking

## Key Finding
Identified an HP networked printer exposing a duplicate web admin interface on ports 80 and 8080, both vulnerable to a known Slowloris DoS CVE (CVE-2007-6750). Recommended disabling the redundant interface to reduce attack surface.

## Full Write-Up
See [nmap-notes.md](./nmap-notes.md) for the detailed methodology, screenshots, asset inventory table, and firewall audit findings.

## Tools Used
- Nmap 7.98
- Ubuntu Linux (bash/root shell)

## Disclaimer
All scans were performed against my own home network and personally owned devices, with full authorization as the network/device owner. No external or third-party systems were tested.
