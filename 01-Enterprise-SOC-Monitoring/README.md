# Lab 01 — Enterprise SOC Monitoring & Threat Detection

## Project Overview

This project documents the design, deployment, and testing of a Security Operations Center (SOC) monitoring environment using Windows endpoint telemetry and security monitoring tools.

The lab focuses on security event collection, threat detection, alert investigation, and incident documentation.

**Project Status:** In Progress

## Objectives

- Build a virtualized cybersecurity lab environment.
- Configure centralized security monitoring.
- Collect Windows Security and Sysmon event logs.
- Generate controlled security test events.
- Detect suspicious authentication and process execution.
- Investigate alerts and map relevant activity to MITRE ATT&CK.
- Document technical findings and remediation recommendations.

## Planned Technologies

| Technology | Purpose |
|---|---|
| Hyper-V | Virtualization platform |
| Windows 11 | Monitored endpoint |
| Sysmon | Endpoint process and network telemetry |
| Wazuh | SIEM and security monitoring (subject to resource testing) |
| PowerShell | Administration and controlled test activity |
| MITRE ATT&CK | Detection and investigation mapping |

## Planned Architecture

Windows 11 Host (Hyper-V)

- Windows endpoint VM — Security logs and Sysmon
- Security monitoring server — Log collection, analysis, and alerting

The final architecture will depend on available system memory and performance testing.

## Investigation Scenarios

1. Multiple failed Windows login attempts.
2. Suspicious PowerShell process execution.
3. Privileged account activity.
4. Security event correlation and alert triage.

## Project Documentation

As the lab progresses, this repository will include:

- Architecture diagrams
- Virtual machine configurations
- Security monitoring configuration
- Detection rules and queries
- Screenshots of actual test results
- SOC investigation reports
- Troubleshooting notes
- Lessons learned

## Current Progress

- [x] GitHub repository created
- [x] Portfolio README published
- [ ] Hyper-V environment configured
- [ ] Virtual machine deployed
- [ ] Endpoint telemetry configured
- [ ] Security monitoring platform deployed
- [ ] Detection scenarios tested
- [ ] Investigation report published

## Security Notice

All activities will be performed on owned or explicitly authorized lab systems. No production systems will be targeted, and no credentials or sensitive information will be published.

---

**Status:** Environment setup in progress.
