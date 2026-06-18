# Phishing URL Analysis - SOC L1 Project

## Overview
Analyzed a live phishing URL impersonating Allegro Lokalnie 
hosted  to steal informations

## Tools Used / Detection Methodolgy
- MXToolbox - BIMI/DMARC analysis
- whois - Domain Detail extraction 
- VirusTotal - URL threat intelligence
- AbuseIPDB - IP reputation check
- URLScan.io - Safe URL inspection
- MITRE ATT&CK - Technique mapping

## Key Findings
- URL:  http://allegrolokalnie[.]oferta87518517[.]click
- SPF:  BIMI / DMARC: All missing
- VirusTotal: Flagged as Phishing 
- Hosting: <172.67.154.75> Cloudflare, United States of America 
- MITRE ATT&CK: T1566.002 - Spearphishing Link

## Deliverables
- Full incident report (pdf)
- IOC list
- Screenshots of all tool outputs

## Skills Demonstrated
SOC Analysis | Threat Intelligence | IOC Extraction | 
MITRE ATT&CK | Phishing Investigation | Incident Reporting

## Author - Shubrajit Dey 

Prepared as part of a phishing URL investigation and SOC analysis
practice.