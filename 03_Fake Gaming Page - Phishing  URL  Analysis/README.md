# Phishing URL Analysis - SOC L1 Project

## Overview
Analyzed a live phishing URL impersonating Gaming Brand to steal user credentials.

## Tools Used
- MXToolbox - SPF/DKIM/DMARC analysis
- VirusTotal - URL threat intelligence
- AbuseIPDB - IP reputation check
- URLScan.io - Safe URL inspection
- MITRE ATT&CK - Technique mapping

## Key Findings
- URL: https://www[.]lootscanner[.]one
- SPF / DKIM / DMARC: All missing
- VirusTotal: Flagged as Phishing (AlphaMountain.ai)
- Hosting:  United States
- Domain Registered : 2026-06-17
- MITRE ATT&CK: T1566.002 - Spearphishing Link

## Recommendations

-   Block the domain at firewall and DNS filtering solutions (if
    malicious).
-   Report the URL to appropriate security vendors.
-   Educate users about phishing awareness.
-   Monitor for related indicators in enterprise logs.


## Deliverables
- Full incident report (DOCX)
- IOC list
- Screenshots of tool outputs


## Skills Demonstrated
SOC Analysis | Threat Intelligence | IOC Extraction | 
MITRE ATT&CK | Phishing Investigation | Incident Reporting

## Author - Shubrajit Dey 

Prepared as part of a phishing URL investigation and SOC analysis
practice.