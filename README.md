<h1 align="center">Scott Renny</h1>

<p align="center">
  <strong>Security+ Certified · AWS Certified AI Practitioner · Cybersecurity Engineering · Security Operations</strong>
</p>

<p align="center">
  I build, secure, monitor, recover, and document real infrastructure in a continuously evolving home Cyber Operations Center.
</p>

<p align="center">
  <a href="https://www.comptia.org/certifications/security"><img alt="CompTIA Security+" src="https://img.shields.io/badge/CompTIA-Security%2B-EA1D2C?style=flat-square"></a>
  <a href="https://aws.amazon.com/certification/certified-ai-practitioner/"><img alt="AWS Certified AI Practitioner" src="https://img.shields.io/badge/AWS-Certified%20AI%20Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"></a>
  <a href="https://github.com/scott-renny/cyber-operations-center-engineering-program"><img alt="COC Phase 10 in progress" src="https://img.shields.io/badge/COC-Phase%2010%20In%20Progress-F0AD4E?style=flat-square"></a>
  <img alt="Current milestone Active Directory identity lab" src="https://img.shields.io/badge/Current-Active%20Directory%20Identity%20Lab-0078D4?style=flat-square">
  <a href="https://www.linkedin.com/in/scottrenny"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

## About me

I hold CompTIA Security+ and AWS Certified AI Practitioner certifications. My near-term target is an entry-level cybersecurity/SOC-oriented role, and I'm deliberately building broader capability in security engineering, cloud and cloud security engineering, and AI-assisted automation engineering through hands-on, production-style projects.

My portfolio goes beyond installing tools. Each major project documents the architecture, security decisions, implementation, validation evidence, failure modes, recovery procedures, and lessons learned behind the finished system.

My working method is simple:

```text
Plan → Build → Secure → Validate → Monitor → Recover → Document → Improve
```

## Portfolio snapshot

| Area | Current evidence |
|---|---|
| Cloud engineering | Cognito-approved serverless ticket intake, scoped workload permissions, DynamoDB persistence, SNS email, EC2 IMDSv2 and teardown validation |
| Security operations | Wazuh endpoint monitoring, alert analysis, Sysmon telemetry, MITRE ATT&CK context, malware remediation |
| Identity security | Windows Server 2025 AD DS/DNS, OU/group design, AGDLP-style privilege assignment, separate daily/admin/Tier-0 identities, Protected Users, gMSA and Kerberos attack-path practice |
| Infrastructure security | Hardened Ubuntu Server, Windows endpoint baselines, Docker segmentation, private HTTPS administration |
| Network security | Tailscale/private access, Pi-hole DNS policy, UFW, device discovery, network metadata, access-control design |
| Observability | Zeek, Prometheus, Grafana, Graylog, centralized Windows and Linux telemetry |
| Recovery engineering | Automated rsync and Restic backups, encrypted retention, integrity checks, representative restore validation |
| Automation | Python, PowerShell, Bash, systemd, scheduled jobs, REST APIs, GitHub workflows |
| AI-assisted automation | Deterministic eligibility/safety gates, grounded document generation from verified data, reviewer critique, human authority at consequential actions |
| Engineering governance | ADRs, risk registers, change control, evidence handling, validation gates, completion records |

---

## Flagship program

### [Cyber Operations Center Engineering Program](https://github.com/scott-renny/cyber-operations-center-engineering-program)

A structured 26-phase program documenting the design and operation of an enterprise-inspired Cyber Operations Center.

**Completed phases 0–9 (Phase 8.5 remains blocked separately):**

- program governance, risk management, and documentation standards;
- clean-slate Ubuntu Server foundation and base hardening;
- Docker platform security and private management access;
- private remote access, Pi-hole, Wazuh, ClamAV, and scoped firewall controls;
- encrypted, monitored, and restore-tested backup infrastructure;
- NET-WATCH network visibility and profile-based DNS enforcement;
- Zeek, Prometheus, Grafana, and Graylog telemetry;
- Windows, laptop, phone, and tablet endpoint engineering; and
- private Nextcloud file access and sync with tested recovery and security controls.

**Phase 10 — Identity Services: IN PROGRESS.**

The current pre-attack baseline uses Windows Server 2025 on `DC01` and a Windows 11 Enterprise domain client in the isolated `corp.lab.test` lab. AD DS/DNS, protected OU/group design, AGDLP-based workstation administration, separate everyday/admin/Tier-0 identities, Tier-0 workstation logon restrictions, hardened password/lockout policy, a working gMSA/KDS foundation, advanced audit policy, and a deliberately isolated legacy service identity are implemented and validated. I also hardened the default machine-account quota from 10 to 0 with explicit workstation-admin delegation and remediated a multihomed-DC DNS registration issue before capturing clean pre-attack snapshots.

Next work is the isolated Kali attacker and Wazuh/Sysmon telemetry validation, followed by controlled password-spray, Kerberoasting and credential-access exercises, investigation/remediation, incident-response records, and Greenbone/OpenVAS vulnerability-management practice.

Phase 8.5 — Linux Mint Cinnamon Migration remains blocked in parallel pending the Cerberus hardware build; it does not gate independent Phase 10 work.

[Project Cerberus](https://github.com/scott-renny/project-cerberus-build) delivers this workstation as the Linux Mint Cinnamon engineering platform and primary COC control node.

The next workstation will be built from verified Linux Mint Cinnamon installation media with Secure Boot, full-disk encryption, AppArmor, UFW, selective restoration, Wazuh monitoring, application acceptance testing, and a validated Linux Mint backup before the legacy Windows system is retired.

---

## AI Job Search Automation Platform

One of my strongest individual production-style engineering projects: a production-style AI automation platform with deterministic eligibility and safety gates, grounded document generation from verified candidate information, an independent reviewer-critique pass, controlled browser automation, and human authority preserved at every consequential decision point. It is not presented as fully autonomous — a CAPTCHA, security question, or ambiguous requirement always hands control back to a human.

**Operational private platform · public portfolio showcase published.**

[View the public showcase →](https://github.com/scott-renny/ai-job-search-automation-platform)

---

## Featured repositories

These repositories are the curated entry points to my current portfolio.

| Repository | What it demonstrates | Core technologies |
|---|---|---|
| [Cyber Operations Center Engineering Program](https://github.com/scott-renny/cyber-operations-center-engineering-program) | Phased security-operations program spanning infrastructure, endpoints, telemetry, recovery, identity and governance | Wazuh · Active Directory · Zeek · Docker · Linux · Windows |
| [AI Job Search Automation Platform](https://github.com/scott-renny/ai-job-search-automation-platform) | Production-style AI automation with deterministic safety gates, grounded generation, reviewer critique, and human-controlled submission | Python · Claude/Groq · Playwright · systemd |
| [NET-WATCH](https://github.com/scott-renny/netwatch) | Complete, operational, maintained network visibility and profile-based DNS access-control platform | Python · Flask · Pi-hole · Nmap · Wazuh |
| [Project Hermes](https://github.com/scott-renny/project-hermes) | Stable v1.0.1 release — repeatable Windows provisioning, validation, backup, restoration, and maintenance, validated by 381 automated tests | PowerShell · Pester · Windows Security |
| [Cloud Engineering Portfolio](https://github.com/scott-renny/cloud-engineering-portfolio) | Completed AWS starter series and Family IT Help Desk v0.2 authenticated ticket management | AWS · Cognito · Lambda · DynamoDB · SNS |
| [Project Cerberus](https://github.com/scott-renny/project-cerberus-build) | Linux Mint Cinnamon engineering workstation and primary COC control-node build | Linux Mint · Cinnamon · AppArmor · UFW |
| [Project Ares](https://github.com/scott-renny/project_ares) | On-demand isolated virtual cyber range hosted on Cerberus for controlled attack simulation and detection validation | Virtualization · Kali · Active Directory · Wazuh |
| [Project Daedalus](https://github.com/scott-renny/project-daedalus) | Self-hosted automation and intelligence workflows with explicit governance | n8n · APIs · JSON · Automation |
| [Security+ Trainer](https://github.com/scott-renny/secplus-trainer) | Browser-based study tools, exercises, and mock examinations | HTML · CSS · JavaScript · Security+ |

### Additional engineering work

| Project | Focus |
|---|---|
| [Project Apollo](https://github.com/scott-renny/project-apollo) | Samsung mobile-device security hardening and validation |
| [Project Atlas](https://github.com/scott-renny/project-atlas) | Operational Ubuntu infrastructure; completed hardware restoration, unattended power/reboot recovery, and owner-confirmed external SSH/remote-development acceptance |
| [Pi-hole DNS Infrastructure](https://github.com/scott-renny/pihole-dns-infrastructure) | DNS filtering, policy enforcement, and resilient name resolution |
| [Home Lab Network Security](https://github.com/scott-renny/home-lab-network-security) | Network architecture, segmentation, secure administration, and defensive controls |
| [HomeSOC](https://github.com/scott-renny/homesoc) | Preserved SOC-oriented home-lab engineering |
| [Backup Lab](https://github.com/scott-renny/backup-lab) | Preserved Linux backup automation and recovery engineering |
| [Legacy Project Archive](https://github.com/scott-renny/legacy-project-archive) | Earlier work showing the progression of my engineering practices |

---

## Technical toolkit

| Domain | Technologies and practices |
|---|---|
| Operating systems | Ubuntu Server, Windows Server 2025, Windows 10/11, Linux Mint Cinnamon |
| Security and telemetry | Wazuh, Sysmon, Zeek, Suricata, ClamAV, Graylog, MITRE ATT&CK |
| Identity | Active Directory Domain Services, DNS, Group Policy, Kerberos, AGDLP, Protected Users, gMSA |
| Infrastructure | Docker, Docker Compose, Dockge, systemd, Caddy, Samba, virtualization |
| Networking | TCP/IP, DNS, DHCP, Pi-hole, Tailscale, UFW, Nmap, segmentation concepts |
| Observability | Prometheus, Grafana, structured logs, health checks, operational dashboards |
| Automation and development | Python, PowerShell, Bash, Flask, REST APIs, HTML, CSS, JavaScript |
| Recovery | Restic, rsync, retention policies, integrity checks, hash comparison, restore testing |
| Engineering practice | Architecture decisions, risk analysis, change control, evidence handling, runbooks |

Atlas v1 completed its September 7, 2026 unattended-operation resilience milestone using the existing laptop battery, BIOS Wake on AC, systemd and Docker restart policies. Optional evidence follow-up does not reopen the completed operational milestone.

## Current direction

- Pursuing entry-level cybersecurity / SOC-oriented roles as my near-term target
- Deliberately building toward security engineering, cloud/cloud security engineering, and AI engineering & automation through hands-on, production-style projects — direction, not a current title
- Building COC Phase 10 Identity Services with a validated Windows Server 2025/Windows 11 pre-attack baseline, privilege separation, delegated administration, advanced auditing, and the controlled attack/detection chapter next
- Operating the completed Phase 9 Nextcloud platform without reopening accepted scope
- Keeping completed Atlas infrastructure operational through simple, reusable recovery controls
- Progressing a booked AWS certification path: Cloud Practitioner (Oct 24), Solutions Architect – Associate (Nov 28), Security – Specialty (Dec 19, 2026)
- Building on the completed AWS starter series and Family IT Help Desk v0.2 authenticated ticket management
- Expanding detection engineering and threat-hunting skills
- Developing incident-response and digital-forensics workflows

---

## Professional highlights

- CompTIA Security+ certified
- AWS Certified AI Practitioner (AIF-C01), earned August 29, 2026
- Information Security Analyst Program — Correlation One graduate
- Graduated with Honors and a 96% final average
- Building a public, validation-driven cybersecurity engineering portfolio
- Interested in SOC analysis, infrastructure security, identity security, detection, and incident response

---

## Connect

I welcome conversations with SOC analysts, cybersecurity professionals, infrastructure engineers, recruiters, and people who learn by building.

<p>
  <a href="https://www.linkedin.com/in/scottrenny"><strong>Connect with me on LinkedIn</strong></a>
  ·
  <a href="https://scott-renny.github.io"><strong>Read my engineering journal</strong></a>
  ·
  <a href="https://github.com/scott-renny?tab=repositories"><strong>Explore all repositories</strong></a>
</p>

---

<p align="center">
  <strong>Build deliberately. Validate continuously. Document everything.</strong>
</p>
