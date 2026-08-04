# Scott Renny

### Security+ Certified | Cybersecurity & Infrastructure Engineering | Aspiring SOC Analyst

I build, secure, validate, and document real systems in a continuously evolving home Cyber Operations Center.

My portfolio focuses on the work behind dependable security operations: hardened infrastructure, network visibility, DNS policy, security monitoring, backup and recovery, automation, and clear operational documentation.

[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-red)](https://www.comptia.org/certifications/security)
![COC Progress](https://img.shields.io/badge/COC-Phases%200--6%20Complete-success)
![Current Milestone](https://img.shields.io/badge/Next-Phase%207%20Telemetry-blue)
![Focus](https://img.shields.io/badge/Focus-Security%20Operations-005571)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/scottrenny)

---

## What I bring

- **Security operations mindset:** monitoring, alert analysis, hardening, validation, recovery, and continuous improvement
- **Infrastructure experience:** Ubuntu Server, Windows, Docker, systemd, Caddy, networking, VPNs, DNS, and firewalls
- **Automation and development:** Python, PowerShell, Bash, REST APIs, HTML, CSS, JavaScript, Git, and GitHub
- **Engineering discipline:** architecture records, risk management, evidence handling, change control, troubleshooting, and recovery testing
- **Clear documentation:** every major project explains what was built, why decisions were made, how it was tested, and what remains to improve

## Professional highlights

- CompTIA Security+ certified
- Amazon Information Security Analyst Program graduate through Correlation One
- Graduated with Honors and a 96% final average
- Building a structured, hands-on cybersecurity engineering portfolio
- Seeking an entry-level SOC Analyst opportunity

---

## Flagship program

### [Cyber Operations Center Engineering Program](https://github.com/scott-renny/cyber-operations-center-engineering-program)

A 26-phase engineering program documenting the design, deployment, security, operation, validation, and continued development of an enterprise-inspired Cyber Operations Center.

The program treats documentation and validation as engineering deliverables—not afterthoughts.

| Completed phase | Outcome |
|---|---|
| Phase 0 — Program Governance | Security principles, documentation standards, risk management, evidence handling, and change control |
| Phase 1 — Foundation | Clean-slate Ubuntu Server rebuild and validated infrastructure baseline |
| Phase 2 — Base Hardening | SSH keys, UFW, Fail2Ban, Auditd, AppArmor, updates, and private HTTPS operations |
| Phase 3 — Container Platform | Docker, Dockge, segmentation, logging standards, and secured management access |
| Phase 4 — Core Network & Security | WireGuard, Pi-hole, Wazuh, ClamAV, local DNS, and scoped firewall access |
| Phase 5 — Backup & Recovery | Automated protection, encrypted retention, monitoring, and restore verification |
| Phase 6 — NET-WATCH | Network discovery, profile policies, Pi-hole enforcement, and Wazuh visibility |

**Current status:** Phases 0–6 complete  
**Next milestone:** Phase 7 — Telemetry Platform

---

## Featured project

### [NET-WATCH](https://github.com/scott-renny/netwatch)

NET-WATCH is the project I am most proud of.

It began as a way to manage family internet schedules and evolved into an operational network visibility and profile-based DNS access-control platform.

The current deployment includes:

- discovery and classification of real network devices;
- assigned, unassigned, profile, and device-type views;
- per-profile schedules and daily usage budgets;
- manual profile kill switches;
- Pi-hole v6 group-based DNS enforcement;
- different content policies for different device profiles;
- Wazuh alerts with MITRE ATT&CK context;
- a Flask API served by Gunicorn and managed by systemd; and
- private HTTPS access through Caddy.

Its Pi-hole integration is deliberately profile-scoped. NET-WATCH does not disable filtering for the entire network: it reconciles a managed rule against only the groups that should be blocked and rejects unsafe group configurations.

**Demonstrated skills:** Python, Flask, REST APIs, Linux services, DNS security, network monitoring, access-control design, defensive programming, troubleshooting, and full-stack development.

---

## Additional engineering projects

| Project | Focus |
|---|---|
| [Project Hermes](https://github.com/scott-renny/project-hermes) | Modular PowerShell automation for configuring, validating, backing up, and restoring a Windows engineering workstation |
| [Project Atlas](https://github.com/scott-renny/project-atlas) | Restoration and modernization of repurposed hardware as a dependable Ubuntu infrastructure server |
| [Project Hydra](https://github.com/scott-renny/project-hydra) | SOC workstation design, analyst workflows, monitoring, investigations, and operational productivity |
| [Backup Lab](https://github.com/scott-renny/backup-lab) | Linux backup automation, encrypted snapshots, restore testing, Samba, and Wazuh monitoring |
| [Legacy Project Archive](https://github.com/scott-renny/legacy-project-archive) | Preserved earlier work showing the progression of my engineering and documentation practices |

---

## Technical toolkit

| Area | Technologies and practices |
|---|---|
| Security operations | Wazuh, alert analysis, MITRE ATT&CK context, log analysis, hardening, malware monitoring |
| Infrastructure | Ubuntu Server, Windows, Docker, Dockge, systemd, Caddy, virtualization |
| Networking | TCP/IP, DNS, DHCP, Pi-hole, WireGuard, UFW, segmentation and VLAN concepts |
| Automation | Python, PowerShell, Bash, scheduled jobs, REST API integration |
| Development | Flask, HTML, CSS, JavaScript, JSON, Git, GitHub |
| Engineering practice | Documentation, validation, troubleshooting, recovery testing, risk and change management |

## Currently developing

- Security monitoring and telemetry engineering
- Detection engineering and threat hunting
- Microsoft Sentinel and Splunk
- Active Directory and identity security
- Digital forensics and incident response
- Infrastructure automation
- Cloud and AWS security fundamentals

---

## How I work

```text
Plan → Build → Secure → Validate → Document → Improve
```

I do not consider a service complete because it starts successfully. I want to understand how it behaves, how it fails, how it is monitored, how it can be recovered, and how another person could operate it from the documentation.

That approach is the foundation of this portfolio and the kind of discipline I hope to bring to a security operations team.

---

## Connect

I’m interested in connecting with cybersecurity professionals, SOC analysts, infrastructure engineers, recruiters, and others who learn by building.

[Connect with me on LinkedIn](https://www.linkedin.com/in/scottrenny)

---

> **Build deliberately. Validate continuously. Document everything.**
