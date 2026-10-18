# SOC Automation Project

**Automated Threat Detection, Enrichment and Response using Wazuh, Shuffle and TheHive**

A hands-on Security Operations Center (SOC) lab demonstrating how security monitoring, detection engineering, workflow automation, threat-intelligence enrichment, and analyst-approved response can work together.

## Architecture

Windows 10 + Sysmon + Wazuh Agent → Wazuh Manager → Shuffle → VirusTotal / TheHive / Email → Analyst-approved response through Wazuh.

## Tools & Technologies

- **Wazuh:** SIEM/XDR, event analysis, custom detection rules and active response
- **Sysmon:** Windows process-creation telemetry
- **Shuffle:** SOAR workflow automation and API integrations
- **TheHive 5:** Security alert and incident management
- **VirusTotal:** File-hash threat-intelligence lookup
- **MITRE ATT&CK:** Detection mapping to T1003 — OS Credential Dumping
- **Windows 10 and Linux:** Lab endpoint and server environments

## Key Features

- Centralized Windows endpoint monitoring
- Custom detection rule for Mimikatz execution
- Automated forwarding of alerts from Wazuh to Shuffle
- File-hash extraction and VirusTotal lookup
- Automated alert creation in TheHive
- Email notification with an analyst approval/denial step
- Wazuh active-response integration for IP blocking

## Project Report

[Read the full project report](SOC_AUTOMATION.pdf)

The report documents the architecture, implementation, troubleshooting, test observations, and potential improvements.

## Key Learning Outcomes

- SIEM operations and endpoint telemetry
- Custom detection engineering
- SOAR workflow development
- Threat-intelligence integration
- Incident management and response automation
- Linux service and configuration management

## Security Disclaimer

This project was developed for educational purposes in a controlled lab environment. Security tools and response actions should only be tested on systems for which authorization has been granted.

## Author

**Bibash Bhandari**

Cybersecurity | SOC Operations | Blue Team | Security Automation
