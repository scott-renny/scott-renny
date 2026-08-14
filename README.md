<h1 align="center">Scott Renny</h1>

<p align="center">
  <strong>Security+ Certified · Cybersecurity Engineering · Security Operations</strong>
</p>

<p align="center">
  I build, secure, monitor, recover, and document real infrastructure in a continuously evolving home Cyber Operations Center.
</p>

<p align="center">
  <a href="https://www.comptia.org/certifications/security"><img alt="CompTIA Security+" src="https://img.shields.io/badge/CompTIA-Security%2B-EA1D2C?style=flat-square"></a>
  <a href="https://github.com/scott-renny/cyber-operations-center-engineering-program"><img alt="COC Phase 8 complete" src="https://img.shields.io/badge/COC-Phase%208%20Complete-2EA44F?style=flat-square"></a>
  <img alt="Current milestone Fedora migration" src="https://img.shields.io/badge/Current-Fedora%20KDE%20Migration-51A2DA?style=flat-square&logo=fedora&logoColor=white">
  <a href="https://www.linkedin.com/in/scottrenny"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

## About me

I am a Security+ certified cybersecurity practitioner building toward a security operations role through hands-on engineering.

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

**Completed through Phase 8:**

- program governance, risk management, and documentation standards;
- clean-slate Ubuntu Server foundation and base hardening;
- Docker platform security and private management access;
- WireGuard, Pi-hole, Wazuh, ClamAV, and scoped firewall controls;
- encrypted, monitored, and restore-tested backup infrastructure;
- NET-WATCH network visibility and profile-based DNS enforcement;
- Zeek, Prometheus, Grafana, and Graylog telemetry; and
- Windows, laptop, phone, and tablet endpoint engineering.

**Current milestone:** [Phase 8.5 — Fedora KDE Plasma Migration](https://github.com/scott-renny/cyber-operations-center-engineering-program/tree/main/phases/phase-08-5-workstation-migration)

[Project Cerberus](https://github.com/scott-renny/project-cerberus-build) delivers this workstation as the Fedora KDE engineering platform and primary COC control node.

The next workstation will be built from verified Fedora KDE installation media with Secure Boot, LUKS2-backed encryption, SELinux, firewalld, selective restoration, Wazuh monitoring, application acceptance testing, and a validated Fedora backup before the legacy Windows system is retired.

---

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/scott-renny/netwatch">NET-WATCH</a></h3>
      <p>Operational network visibility and profile-based DNS access control. Combines real device discovery, inventory, schedules, daily budgets, Pi-hole group policy, and Wazuh visibility in a private dashboard.</p>
      <p><strong>Python · Flask · Pi-hole · Wazuh · Nmap · systemd · Caddy</strong></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/scott-renny/project-hermes">Project Hermes</a></h3>
      <p>A modular PowerShell framework for provisioning, configuring, validating, backing up, restoring, and maintaining Windows engineering workstations with repeatable workflows and rollback paths.</p>
      <p><strong>PowerShell · Windows · Validation · Backup · Automation</strong></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/scott-renny/secplus-trainer">Security+ Trainer</a></h3>
      <p>A complete browser-based study suite with domain trainers, acronym and port exercises, performance-based practice, and four mock examinations that runs locally without an account or server.</p>
      <p><strong>Security+ · HTML · CSS · JavaScript · Learning Design</strong></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/scott-renny/project-atlas">Project Atlas</a></h3>
      <p>Hardware restoration and modernization of a used business laptop into a dependable, primarily headless Ubuntu infrastructure server, including compatibility, cooling, testing, and reliability planning.</p>
      <p><strong>Linux · Hardware · Infrastructure · SSH · Reliability</strong></p>
    </td>
  </tr>
</table>

### More engineering work

| Project | Focus |
|---|---|
| [Pi-hole DNS Infrastructure](https://github.com/scott-renny/pihole-dns-infrastructure) | DNS filtering, policy enforcement, monitoring, and resilient home-network name resolution |
| [Home Lab Network Security](https://github.com/scott-renny/home-lab-network-security) | Network architecture, segmentation, secure administration, and defensive controls |
| [HomeSOC](https://github.com/scott-renny/homesoc) | Security monitoring and SOC-oriented home-lab development |
| [Backup Lab](https://github.com/scott-renny/backup-lab) | Early Linux backup automation and the foundation of later recovery-engineering work |
| [Legacy Project Archive](https://github.com/scott-renny/legacy-project-archive) | Preserved earlier work showing the progression of my engineering and documentation practices |

---

## Technical toolkit

| Domain | Technologies and practices |
|---|---|
| Operating systems | Ubuntu Server, Windows 10/11, Fedora KDE Plasma migration planning |
| Security and telemetry | Wazuh, Sysmon, Zeek, Suricata, ClamAV, Graylog, MITRE ATT&CK |
| Infrastructure | Docker, Docker Compose, Dockge, systemd, Caddy, Samba, virtualization |
| Networking | TCP/IP, DNS, DHCP, Pi-hole, WireGuard, UFW, Nmap, segmentation concepts |
| Observability | Prometheus, Grafana, structured logs, health checks, operational dashboards |
| Automation and development | Python, PowerShell, Bash, Flask, REST APIs, HTML, CSS, JavaScript |
| Recovery | Restic, rsync, retention policies, integrity checks, hash comparison, restore testing |
| Engineering practice | Architecture decisions, risk analysis, change control, evidence handling, runbooks |

## Current direction

- Completing the Fedora replacement-workstation migration plan
- Expanding detection engineering and threat-hunting skills
- Developing incident-response and digital-forensics workflows
- Building identity-security and Active Directory experience
- Strengthening cloud and AWS security fundamentals
- Preparing for an entry-level SOC Analyst opportunity

---

## Professional highlights

- CompTIA Security+ certified
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
  <a href="https://github.com/scott-renny?tab=repositories"><strong>Explore all repositories</strong></a>
</p>

---

<p align="center">
  <strong>Build deliberately. Validate continuously. Document everything.</strong>
</p>
