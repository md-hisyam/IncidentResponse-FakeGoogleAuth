
<div align="center">

# 🛡️ Malware Traffic Analysis & Incident Response

### Network Forensics | PowerShell Analysis | Threat Intelligence

[![Analysis](https://img.shields.io/badge/Analysis-Malware%20Traffic-blue?style=for-the-badge)](https://github.com/)
[![Tool](https://img.shields.io/badge/Tool-Wireshark-blue?style=for-the-badge)](https://www.wireshark.org/)
[![Tool](https://img.shields.io/badge/Tool-CyberChef-orange?style=for-the-badge)](https://gchq.github.io/CyberChef/)

**Incident Investigation Date: 22 January 2025**

</div>

---

## 📌 Overview

This project documents a malware traffic analysis and incident response focuses on identifying the infected Windows host, analyzing suspicious network communications, recovering an embedded PowerShell payload, identifying potential Command and Control (C2) infrastructure, and documenting Indicators of Compromise (IOCs).

## 🎯 Investigation Objectives

- Identify the infected Windows client and its network details.
- Investigate the suspected phishing domain associated with a fake Google Authenticator page.
- Analyze suspicious network traffic using Wireshark.
- Recover and examine the embedded PowerShell payload using CyberChef.
- Identify suspicious external IP addresses and potential C2 communications.
- Correlate findings with threat intelligence sources.
- Document IOCs and provide security recommendations.

## 🧰 Tools & Technologies

| Tool | Purpose |
|:---|:---|
| [Wireshark](https://www.wireshark.org/) | Network traffic analysis |
| [CyberChef](https://gchq.github.io/CyberChef/) | PowerShell payload decoding |
| [VirusTotal](https://www.virustotal.com/) | Threat intelligence investigation |
| [AbuseIPDB](https://www.abuseipdb.com/) | IP reputation analysis |

## 🔍 Key Findings

- Identified the potentially compromised internal Windows host.
- Recovered an embedded PowerShell payload for static analysis.
- Identified HTTP communication with a suspected C2 server.
- Discovered suspicious startup shortcut creation indicating potential persistence.
- Identified additional external IP addresses associated with suspicious activity.
- Correlated network findings with external threat intelligence sources.
- Documented Indicators of Compromise (IOCs) and remediation recommendations.

## 📂 Repository Structure

```text
📁 IncidentResponse-FakeGoogleAuth
│
├── 📄 README.md
├── 📄 LICENSE
│
├── 📁 report
│   └── 📄 Malware_Incident_Response_Report.pdf
│
└── 📁 evidence
     ├── 📄 Wireshark.md
     ├── 📄 Virustotal.md
     └── 📄 AbuseIP.md


```

## 🖥️ Investigation Evidence

Screenshots and supporting evidence from the investigation:

<!-- Add your evidence images below after uploading them -->

| Evidence | Description |
|:---|:---|
| Wireshark | Identification of suspicious external IP addresses |
| Payload | Recovery and static analysis of the embedded script |
| Abuse IP | Reputation checks using AbuseIPDB |
| Virustotal | Reputation checks using Virustotal|

## 🧠 Skills Demonstrated

- Malware Traffic Analysis
- Network Forensics
- PCAP Analysis
- PowerShell Payload Analysis
- Threat Intelligence
- IOC Identification
- Incident Response
- Security Documentation

## 📚 Reference

**Original Investigation Scenario & PCAP Resources**

[Malware Traffic Analysis Palo Alto Unit 42 – 22 January 2025] ([2025-01-22-IOCs-for-malware-from-fake-Microsoft-Teams](https://github.com/PaloAltoNetworks/Unit42-timely-threat-intel/blob/main/2025-01-22-IOCs-for-malware-from-fake-Microsoft-Teams-site.txt))

## ⚠️ Disclaimer

This project is intended for educational and defensive cybersecurity purposes only. The analysis was conducted using provided lab artifacts and does not represent an actual organizational security breach.

All findings should be interpreted within the context of the supplied investigation materials. Malicious indicators and artifacts are documented for defensive analysis and should not be used outside authorized environments.

---

<div align="center">

**Cybersecurity Portfolio Project**

*Malware Analysis • Network Forensics • Incident Response*

</div>
