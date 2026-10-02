# Enterprise Network Security Assessment and Hardening

## Project Overview

This project demonstrates an enterprise network security assessment and hardening workflow in an authorized, isolated lab environment. The objective is to identify active hosts, enumerate network services, review potential security weaknesses, and recommend practical security controls.

## Objectives

* Discover active hosts using Nmap.
* Identify open ports and running services.
* Review potential vulnerabilities and insecure configurations.
* Prepare a security findings and risk register.
* Recommend network and host hardening measures.
* Document validation and retesting procedures.

## Tools Used

* Kali Linux
* Nmap
* Wireshark
* Nessus or OpenVAS, if used
* VMware Workstation
* Metasploitable 2 lab environment, if used

## Project Methodology

1. Prepare the authorized lab environment.
2. Perform host discovery.
3. Conduct port and service enumeration.
4. Review potential vulnerabilities and misconfigurations.
5. Document findings and assess their severity.
6. Recommend appropriate hardening controls.
7. Validate improvements and record evidence.

## Example Command

```bash
nmap -sn 192.168.23.129
```

This command performs host discovery against the specified lab target without conducting a full port scan.

## Hardening Recommendations

* Disable unnecessary services and close unused ports.
* Apply security patches and software updates.
* Restrict network access using firewall rules and segmentation.
* Use secure protocols for remote administration.
* Enforce least privilege and multi-factor authentication where supported.
* Enable security logging and monitoring.
* Retest systems after applying security changes.

## Repository Contents

* `README.md` — Project overview and instructions.
* `reports/` — Final project report.
* `evidence/` — Actual screenshots and scan results.
* `diagrams/` — Network architecture diagram.
* `findings/` — Risk register and remediation tracking.

## Scope and Authorization

All testing must be conducted only against systems that I own or am explicitly authorized to assess. This project is intended for educational and defensive security purposes.

## Author

Lakshmi Subhaja Kari
B.Tech — Cybersecurity

## Project Status

Document the completed activities and add actual assessment evidence before submitting the project.
