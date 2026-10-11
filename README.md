# Aman Gupta | Cybersecurity Portfolio

MSc Cybersecurity student at **Manipal University Jaipur** with a BSc in Information Technology background. I’m building practical skills in security monitoring, network analysis, Linux, scripting, and incident response through hands-on labs, coursework, and projects.

- **Current focus:** SIEM engineering, detection engineering, network security, and security operations
- **Education:** MSc Cybersecurity — Manipal University Jaipur (2026–present); BSc Information Technology — University of Mumbai
- **Portfolio:** [Cybersecurity reports and project notes](#portfolio)
- **Connect:** [LinkedIn](https://linkedin.com/in/aman-gupta-394474378) · [GitHub](https://github.com/AmanGupta-Sec)

---

## Featured projects

### Sentinel X — Personal SIEM & Detection Engineering Project
**Status: In progress · Personal project**

Sentinel X is my personal security monitoring and detection engineering project built around Wazuh and Ubuntu Server. Rather than stopping at a default SIEM dashboard, the goal is to build and test an application-aware detection workflow that connects real application events to meaningful, explainable security alerts.

- **Current baseline:** Wazuh dashboard running in an Ubuntu Server virtual machine.
- **Application-aware monitoring:** planned ingestion of structured events from a Flask web application, including successful logins, failed logins, and user activity.
- **Custom detection logic:** planned Wazuh decoders and custom rules tailored to the application's log format, rather than relying only on built-in alerts.
- **Correlation for suspicious behaviour:** planned detection of repeated failed logins from the same source IP to flag possible brute-force activity.
- **Testable detection engineering:** validate rules with Wazuh's log-testing workflow and controlled security scenarios, then record expected versus observed alerts.
- **Evidence-led reporting:** document the event flow, rule logic, severity, test cases, screenshots, and known limitations so results can be reproduced.
- **Related web application repository:** [SIEM-project-web-app](https://github.com/ArvindRaghav56/SIEM-project-web-app)

**What makes Sentinel X distinctive:** it aims to demonstrate the complete path from application event → log ingestion → custom detection → correlated alert → validation evidence, not just display a SIEM dashboard.

> The application-log integration, custom rules, correlation, and test evidence are planned work and will be marked complete only after implementation and verification.

### Smart Emergency Alert System (SEAS)
**Status: Academic project documentation / prototype work**

An IoT-oriented concept for helping alert nearby road users when an ambulance approaches. The portfolio currently contains the project synopsis; use the linked document for the scope and proposed approach.

- [Read the SEAS synopsis](projects/SEAS-synopsis-2.pdf)

---

## Portfolio

### Cybersecurity reports
- [Vulnerability Assessment Report](cybersecurity_reports/Vulnerability%20assessment%20report.pdf)
- [Incident Handler’s Journal](cybersecurity_reports/Incident%20Handlers%20Journal/Incident%20handler's%20journal.pdf)
- [Controls and Compliance Checklist](cybersecurity_reports/Controls%20and%20compliance%20checklist.pdf)
- [Botium Toys — Scope, Goals, and Risk Assessment](cybersecurity_reports/Botium%20Toys_%20Scope,%20goals,%20and%20risk%20assessment%20report.pdf)

### Programming and SQL
- [Algorithm for File Updates in Python](programming_SQL/Algorithm%20for%20file%20updates%20in%20Python.pdf)
- [Apply Filters to SQL Queries](programming_SQL/Apply%20filters%20to%20SQL%20queries.pdf)

### Linux and operating systems
- [File Permissions in Linux](system_and_OS/File%20permissions%20in%20Linux.pdf)

---

## Technical toolkit

**Security and network analysis:** Wazuh, Splunk, Wireshark, tcpdump, Nmap, Suricata, Metasploit  
**Operating systems and environments:** Linux, Kali Linux, Ubuntu Server, VMware Fusion  
**Programming and data:** Python, Java, C, C++, SQL, HTML, CSS, JavaScript

Tools listed here reflect coursework and hands-on learning; proficiency varies by tool and project.

## Certifications and learning

- **Google Cybersecurity Professional Certificate** — completed
- **IBM Cybersecurity Professional Certificate coursework** — in progress

Only completed credentials are marked as completed. Add certificate verification links when available.

## Current learning goals

- Build and validate application-aware SIEM detections
- Improve alert triage, event correlation, and detection-rule testing
- Document repeatable security labs with evidence, methodology, and limitations
- Publish clear setup instructions and reproducible demonstrations for personal projects

## Repository structure

```text
cybersec-portfolio/
├── cybersecurity_reports/   # Security assessment and incident-response coursework
├── programming_SQL/         # Python and SQL exercises
├── projects/                # Project documentation and summaries
├── system_and_OS/           # Linux and OS exercises
└── README.md
```

## Contact

- [LinkedIn](https://linkedin.com/in/aman-gupta-394474378)
- [GitHub profile](https://github.com/AmanGupta-Sec)

*This portfolio is a living record of my learning. Project status is stated explicitly so readers can distinguish completed work from work in progress.*
