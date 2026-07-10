# Enterprise-Wazuh-Siem-Lab
Enterprise Security Monitoring with Wazuh for Windows and Linux

## Table of Contents

- Overview
- Objectives
- Lab Environment
- Architecture
- Skills Demonstrated
- Detection Scenarios
- Investigation Walkthroughs
- Screenshots
- Lessons Learned
- Future Improvements
## Overview
This project demonstrates the deployment of an enterprise-style Security Information and Event Management (SIEM) environment using Wazuh to monitor Windows and Linux systems. The objective is to practice security monitoring, log analysis, incident investigation, and defensive detection techniques commonly used in Security Operations Centers (SOCs).

## Objectivies

Detect and investigate brute-force authentication attempts.

Collect and analyze endpoint security logs.

Monitor Windows and Linux security events.

Develop practical SOC investigation skills.

Practice incident detection and alert triage.

## Lab Enviroment

 | Component | Technology |
|-----------|------------|
| SIEM | Wazuh |
| Windows Endpoint | Windows 11 |
| Linux Endpoint | Ubuntu Server |
| Virtualization | VirtualBox |
| Log Sources | Sysmon, Windows Event Logs |
| Network | Internal Lab Network |

## Architecture

## Skills Demonstrated

### Security Operations

- SIEM Deployment
- Security Monitoring
- Alert Triage
- Incident Investigation

### Log Analysis

- Windows Event Logs
- Linux Authentication Logs
- Sysmon Analysis

### Threat Detection

- IOC Identification
- Brute Force Detection
- Event Correlation

## Detection Scenarios

| Detection Scenario | Status |
|-------------------|--------|
| Failed Login Detection | ✅ Completed |
| Brute Force Detection | ✅ Completed |
| Suspicious PowerShell | 🚧 In Progress |
| Malware Detection | 🚧 Planned |
| Privilege Escalation | 🚧 Planned |
| Persistence Detection | 🚧 Planned |

## Investigation walkthroughs
investigatons/

brute-force.md

failed-logons.md

malware.md

## Lessons Learned

 - Learned how Wazuh correlates endpoint events.
 - Improved Windows Event Log analysis.
 - Better understanding of SOC investigation workflow.
 - Learned to distinguish false positives from actionable alerts

## Future Improvements

- Integrate Active Directory logging.
- Add MITRE ATT&CK technique mapping.
- Create custom Wazuh detection rules.
- Integrate VirusTotal enrichment.
- Develop automated alert reporting.

  ## Project Goal

Modern Security Operations Centers rely on centralized log collection and event correlation to identify malicious activity. This lab was designed to simulate a small enterprise environment where Windows and Linux systems generate security events that can be collected, analyzed, and investigated using Wazuh.

The project focuses on developing practical SOC skills, including alert triage, log analysis, incident investigation, and defensive detection techniques commonly required in entry-level Security Operations roles.
