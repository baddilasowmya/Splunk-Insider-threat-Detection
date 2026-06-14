# Splunk Insider Threat Detection Lab

## Overview
This project demonstrates insider threat detection using Splunk SIEM. It simulates realistic employee activities and malicious insider behavior through Windows Security Event Logs, enabling detection, monitoring, and investigation of suspicious activities.

## Features
- 556 Synthetic Windows Security Events
- 6 Custom SPL Detection Rules
- UEBA-Based Risk Scoring
- MITRE ATT&CK Mapped Detections
- Insider Threat Scenarios
- Splunk Dashboard Visualization
- Incident Response Playbooks

## Detection Use Cases
- Off-Hours Logins
- Sensitive File Access
- USB Device Usage
- Malicious Process Execution
- Audit Log Tampering
- User Risk Scoring

## Technologies Used
- Splunk Enterprise
- SPL (Search Processing Language)
- Python
- Windows Event Logs
- MITRE ATT&CK Framework

## Project Structure

```text
data/
├── insider_threat_logs.csv
dashboards/
└── insider_threat_dashboard.xml
playbooks/
└── IR_Playbooks_Insider_Threat.docx
