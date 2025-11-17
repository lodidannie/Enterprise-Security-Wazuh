# Enterprise Security Monitoring and Threat Detection using Wazuh SIEM

## A hands-on cybersecurity homelab project focused on deploying, configuring, and demonstrating enterprise-grade security monitoring, log analysis, and file integrity monitoring using Wazuh — an open-source SIEM and XDR platform.

### Project Overview

This project simulates a small-to-medium enterprise (SME) SOC environment, demonstrating how security teams can leverage Wazuh to:

- [ ] ✔️ Monitor system logs and endpoint behavior
- [ ] ✔️ Detect unauthorized access / policy violations
- [ ] ✔️ Track changes to critical files
- [ ] ✔️ Gain centralized visibility across multiple endpoints

This homelab also serves as a portfolio project showcasing skills in security engineering, SIEM deployment, configuration, and monitoring.

| Component OS | Role |
|---------|--------|
| Wazuh Manager	Ubuntu (VirtualBox) | SIEM server, dashboard, analysis |
| Wazuh Agent	Windows 10 VM | Endpoint monitoring & telemetry |


Network: Internal virtual network

Tools & Technologies:
Wazuh SIEM, Kibana, OpenSearch, Ubuntu Server, Windows 10 Pro, VirtualBox, Sysmon (planned), MITRE ATT&CK (planned)

### Features Implemented So Far
- [x] Wazuh Installation & Deployment
- [x] Agent Enrollment
- [x] File Integrity Monitoring (FIM)
- [x] Log Collection & Alerting
- [x] Dashboard Visualization
- [x] Threat Detection (Basic)
- [ ] Sysmon + MITRE ATT&CK mapping
- [ ] Vulnerability detection module
- [ ] Active response automation (firewall block)
- [ ] Cloud log ingestion (AWS or GCP)

# Step-by-Step Project Documentation
## 1️⃣ Install & Configure Wazuh Manager (Ubuntu)

✔️Update and install required packages

✔️Install Wazuh repository

✔️Install Wazuh manager

✔️Enable and start service

✔️Secure access and enable dashboard

## 2️⃣ Deploy Wazuh Agent on Windows 10

✔️Download agent from manager dashboard

✔️Install using putty MSI

✔️Configure agent with manager IP & registration

✔️Verify successful connection

## 3️⃣ File Integrity Monitoring Setup

✔️Configured monitoring for:

✔️System files

✔️Desktop sensitive files

✔️Documents & configuration files

### Validated detection of:

✔️Creation

✔️Modification

✔️Deletion

Alerts were visible on the SIEM dashboard with timestamp, affected asset, and user interaction details.

📸 Screenshots

## Add the following screenshots in /screenshots directory and embed here:
✔️ Wazuh dashboard
✔️ Connected agent list
✔️ FIM alert details
✔️ Alert JSON / rule match


## Sample Use Cases (Real World)

-Detecting web server defacement

-Detecting insider modification to policy docs

-Detecting malware encrypting files (ransomware behavior)

-Monitoring compliance requirements (HIPAA, PCI, ISO27001)

## Security Value Proposition

This project demonstrates how organizations can implement enterprise-grade monitoring at zero software licensing cost, enabling:

-Centralized security visibility

-Early threat detection

-Incident triage & investigation

-Compliance reporting

## Key Skills Demonstrated

✔️Linux administration

✔️SIEM deployment & configuration

✔️Endpoint security monitoring

✔️Detection engineering & rule tuning

✔️Incident investigation & alert analysis

✔️Documentation & cybersecurity reporting


📚 References

https://wazuh.com/

https://documentation.wazuh.com/
