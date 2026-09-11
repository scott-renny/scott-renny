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
  <a href="https://github.com/scott-renny/cyber-operations-center-engineering-program"><img alt="COC Phase 9 complete" src="https://img.shields.io/badge/COC-Phase%209%20Complete-2EA44F?style=flat-square"></a>
  <img alt="Completed milestone COC Phase 9 Nextcloud" src="https://img.shields.io/badge/Completed-Phase%209%20Nextcloud-0082C9?style=flat-square">
  <a href="https://www.linkedin.com/in/scottrenny"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

## About me

I hold CompTIA Security+ and AWS Certified AI Practitioner certifications, and I am building toward a security operations role through hands-on engineering.

My portfolio goes beyond installing tools. Each major project documents the architecture, security decisions, implementation, validation evidence, failure modes, recovery procedures, and lessons learned behind the finished system.

My working method is simple:

```text
Plan → Build → Secure → Validate → Monitor → Recover → Document → Improve
```

## Portfolio snapshot

| Area | Current evidence |
|---|---|
| Security operations | Wazuh endpoint monitoring, alert analysis, Sysmon telemetry, MITRE ATT&CK context, malware remediation |
| Infrastructure security | Hardened Ubuntu Server, Windows endpoint baselines, Docker segmentation, private HTTPS administration |
| Network security | WireGuard, Pi-hole DNS policy, UFW, device discovery, network metadata, access-control design |
| Observability | Zeek, Prometheus, Grafana, Graylog, centralized Windows and Linux telemetry |
| Recovery engineering | Automated rsync and Restic backups, encrypted retention, integrity checks, representative restore validation |
| Automation | Python, PowerShell, Bash, systemd, scheduled jobs, REST APIs, GitHub workflows |
| Engineering governance | ADRs, risk registers, change control, evidence handling, validation gates, completion records |

---

## Flagship program

### [Cyber Operations Center Engineering Program](https://github.com/scott-renny/cyber-operations-center-engineering-program)

A structured 26-phase program documenting the design and operation of an enterprise-inspired Cyber Operations Center.

**Completed phases 0–9 (Phase 8.5 remains blocked separately):**

- program governance, risk management, and documentation standards;
- clean-slate Ubuntu Server foundation and base hardening;
- Docker platform security and private management access;
- WireGuard, Pi-hole, Wazuh, ClamAV, and scoped firewall controls;
- encrypted, monitored, and restore-tested backup infrastructure;
- NET-WATCH network visibility and profile-based DNS enforcement;
- Zeek, Prometheus, Grafana, and Graylog telemetry; and
- Windows, laptop, phone, and tablet endpoint engineering.

**Phase 9 — File Access & Sync: COMPLETE (September 10/11, 2026).**

Nextcloud 34.0.3 file access and sync is complete on Atlas, with Tailscale private access through a canonical HTTPS hostname and Caddy, tested Restic backup and database restore, Wazuh FIM alert validation, EICAR-tested ClamAV, working 2FA and outbound email, configured Windows 11 and Windows 10 clients, and successful reboot persistence. Galaxy S25 and Tab A11 Nextcloud onboarding are intentionally deferred and are not Phase 9 blockers.

Phase 8.5 — Linux Mint Cinnamon Migration remains blocked in parallel pending the Cerberus hardware build; it does not gate Phase 9.

[Project Cerberus](https://github.com/scott-renny/project-cerberus-build) delivers this workstation as the Linux Mint Cinnamon engineering platform and primary COC control node.

The next workstation will be built from verified Linux Mint Cinnamon installation media with Secure Boot, full-disk encryption, AppArmor, UFW, selective restoration, Wazuh monitoring, application acceptance testing, and a validated Linux Mint backup before the legacy Windows system is retired.

---

## Featured repositories

These six repositories are the curated entry points to my current portfolio.

| Repository | What it demonstrates | Core technologies |
|---|---|---|
| [Cyber Operations Center Engineering Program](https://github.com/scott-renny/cyber-operations-center-engineering-program) | Phased security-operations program spanning infrastructure, endpoints, telemetry, recovery, and governance | Wazuh · Zeek · Docker · Linux · Windows |
| [NET-WATCH](https://github.com/scott-renny/netwatch) | Operational network visibility and profile-based DNS access control | Python · Flask · Pi-hole · Nmap · Wazuh |
| [Project Hermes](https://github.com/scott-renny/project-hermes) | Repeatable Windows provisioning, validation, backup, restoration, and maintenance | PowerShell · Pester · Windows Security |
| [Project Daedalus](https://github.com/scott-renny/project-daedalus) | Self-hosted automation and intelligence workflows with explicit governance | n8n · APIs · JSON · Automation |
| [Project Cerberus](https://github.com/scott-renny/project-cerberus-build) | Linux Mint Cinnamon engineering workstation and primary COC control-node build | Linux Mint · Cinnamon · AppArmor · UFW |
| [Security+ Trainer](https://github.com/scott-renny/secplus-trainer) | Browser-based study tools, exercises, and mock examinations | HTML · CSS · JavaScript · Security+ |

### Additional engineering work

| Project | Focus |
|---|---|
| [Project Ares](https://github.com/scott-renny/project_ares) | Isolated adversary simulation and detection validation |
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
| Operating systems | Ubuntu Server, Windows 10/11, Linux Mint Cinnamon |
| Security and telemetry | Wazuh, Sysmon, Zeek, Suricata, ClamAV, Graylog, MITRE ATT&CK |
| Infrastructure | Docker, Docker Compose, Dockge, systemd, Caddy, Samba, virtualization |
| Networking | TCP/IP, DNS, DHCP, Pi-hole, WireGuard, UFW, Nmap, segmentation concepts |
| Observability | Prometheus, Grafana, structured logs, health checks, operational dashboards |
| Automation and development | Python, PowerShell, Bash, Flask, REST APIs, HTML, CSS, JavaScript |
| Recovery | Restic, rsync, retention policies, integrity checks, hash comparison, restore testing |
| Engineering practice | Architecture decisions, risk analysis, change control, evidence handling, runbooks |

Atlas v1 completed its September 7, 2026 unattended-operation resilience milestone using the existing laptop battery, BIOS Wake on AC, systemd and Docker restart policies. Optional evidence follow-up does not reopen the completed operational milestone.

## Current direction

- Operating the completed COC Phase 9 Nextcloud platform; Phase 10 Identity Services remains planned
- Keeping completed Atlas infrastructure operational through simple, reusable recovery controls
- Expanding detection engineering and threat-hunting skills
- Developing incident-response and digital-forensics workflows
- Building identity-security and Active Directory experience
- Strengthening cloud and AWS security fundamentals
- Preparing for an entry-level SOC Analyst opportunity

---

## Professional highlights

- CompTIA Security+ certified
- AWS Certified AI Practitioner (AIF-C01), earned August 29, 2026
- Amazon Information Security Analyst Program graduate through Correlation One
- Graduated with Honors and a 96% final average
- Building a public, validation-driven cybersecurity engineering portfolio
- Interested in SOC analysis, infrastructure security, detection, and incident response

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
