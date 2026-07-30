# Wazuh Endpoint Security Monitoring Lab

## Overview

This project demonstrates the implementation of Endpoint Detection and Response (EDR) using Wazuh to monitor a Windows endpoint. The lab includes Sysmon integration, File Integrity Monitoring (FIM), security alert analysis, and threat intelligence verification using MalwareBazaar.

## Objectives

- Deploy Wazuh as an EDR solution.
- Monitor Windows Sysmon events.
- Enable File Integrity Monitoring (FIM).
- Analyze high-severity security alerts.
- Validate malware indicators using MalwareBazaar.

## Technologies Used

- Wazuh
- Sysmon
- Windows 11
- Ubuntu Server
- VirtualBox
- MalwareBazaar

## Project Workflow

1. Installed and configured Wazuh Manager.
2. Connected Windows Agent to Wazuh.
3. Installed and verified Sysmon.
4. Collected and monitored Sysmon logs.
5. Enabled File Integrity Monitoring (Syscheck).
6. Reviewed alert severity levels.
7. Investigated high-severity alerts (Rule Level 12).
8. Verified suspicious file hash using MalwareBazaar.

## Task Deliverables

- ✅ Wazuh deployed successfully.
- ✅ Windows Agent connected.
- ✅ Sysmon installed and running.
- ✅ Sysmon logs collected.
- ✅ File Integrity Monitoring enabled.
- ✅ High severity alerts analyzed.
- ✅ MalwareBazaar used for threat intelligence verification.

## Screenshots

The **screenshots** folder contains evidence of every completed step.

1. Wazuh Dashboard
2. Agent Active
3. Sysmon Successfully Installed
4. Sysmon Logs
5. Syscheck File Integrity Monitoring
6. Severity Levels
7. High Severity Alert Details
8. High Severity Alert Details (Additional)
9. MalwareBazaar Home Page
10. MalwareBazaar Result

## Learning Outcomes

During this project I learned how to:

- Deploy Wazuh as an Endpoint Detection and Response (EDR) platform.
- Monitor Windows events using Sysmon.
- Detect file integrity changes using Wazuh FIM.
- Investigate security alerts based on severity levels.
- Use MalwareBazaar for basic threat intelligence validation.

## Repository Structure

```
wazuh-endpoint-security-monitoring-lab/
│
├── screenshots/
├── report/
├── README.md
└── LICENSE
```

## Author

**Muhammad Ehsaan Bawany**

BS Computer Science  
Cybersecurity Student
