# Windows Endpoint Security Monitoring & Threat Detection Using Wazuh SIEM

## Project Overview
A hands-on cybersecurity lab focused on implementing SIEM-based endpoint monitoring, security event detection, and threat investigation using Wazuh.

The project demonstrates how Windows security events can be centrally monitored and investigated in a simulated SOC environment.

## Tools & Technologies
- Wazuh SIEM
- Docker
- Ubuntu Linux
- Windows 11
- PowerShell
- MITRE ATT&CK

## Key Implementations
- Deployed Wazuh SIEM using Docker on Ubuntu.
- Integrated and monitored a Windows endpoint.
- Configured Windows security event auditing.
- Detected failed login attempts (Event ID 4625).
- Investigated authentication failures using Wazuh Threat Hunting.
- Analyzed alert severity and MITRE ATT&CK information.

## Detection Findings

| Attribute | Result |
|---|---|
| Windows Event ID | 4625 |
| Event Type | Failed Authentication |
| Wazuh Rule ID | 60122 |
| Alert Level | 5 |
| Observed Events | 5 |

Five failed authentication events were generated and investigated during the controlled lab exercise. Each generated an individual Level 5 alert.

## Project Screenshots

### 1. Wazuh Overview Dashboard
![Wazuh Overview](01-wazuh-overview.png)

### 2. Windows Endpoint Monitoring
![Windows Endpoint](02-windows-endpoint.png)

### 3. Failed Login Detection
![Failed Login Detection](03-failed-login-detection.png)

### 4. Threat Hunting & MITRE ATT&CK
![Threat Hunting](04-threat-hunting-mitre.png)

## Key Learnings
- SIEM deployment and endpoint integration.
- Centralized security event monitoring.
- Windows authentication failure investigation.
- Security alert analysis and threat detection.
- Basic SOC monitoring workflows.

## Future Enhancements
- Custom brute-force detection rules.
- File Integrity Monitoring.
- PowerShell activity monitoring.
- Incident response automation.

## Project Status
**Completed – Hands-on SOC Monitoring Lab**

*Developed for practical cybersecurity learning in a controlled lab environment.*
