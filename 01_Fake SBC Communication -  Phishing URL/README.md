# Phishing URL Analysis - SOC L1 Project

## Overview
Analyzed a live phishing URL impersonating SBC/AT&T 
hosted on Webflow to steal user credentials.

## Tools Used
- MXToolbox - SPF/DKIM/DMARC analysis
- VirusTotal - URL threat intelligence
- AbuseIPDB - IP reputation check
- URLScan.io - Safe URL inspection
- MITRE ATT&CK - Technique mapping

## Key Findings
- URL: https://sbcverify-143788[.]webflow[.]io/
- SPF / DKIM / DMARC: All missing
- VirusTotal: Flagged as Phishing (AlphaMountain.ai)
- Hosting: Webflow, United States
- MITRE ATT&CK: T1566.002 - Spearphishing Link
- Technique: Living off Trusted Services (LoTS)

## Deliverables
- Full incident report (DOCX)
- IOC list
- Screenshots of all tool outputs

## Skills Demonstrated
SOC Analysis | Threat Intelligence | IOC Extraction | 
MITRE ATT&CK | Phishing Investigation | Incident Reporting

## Author - Shubrajit Dey 

Prepared as part of a phishing URL investigation and SOC analysis
practice.