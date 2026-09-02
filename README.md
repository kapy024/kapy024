<h1 align="center">Hi, I'm Juan Manuel Capistrán 👋</h1>

<p align="center">
  📍 Mexico City, Mexico · 🏢 Cisco Systems · 🗣️ Spanish (native) · English (professional)<br/>
  <b>Network Operations &amp; Automation Engineer</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-IOS%20XR%20%7C%20IOS%20XE-1BA0D7?logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white" />
</p>

---

## About Me

I work in **carrier-grade network operations**: keeping large Cisco transport and mobile-backhaul
networks observable, healthy, and boring — the good kind of boring.

Most of what I build starts as a repetitive task in an operations shift: a health check that
someone runs by hand, an inventory that lives in five spreadsheets, an alarm that nobody sees
until a customer calls. I turn those into **modular, documented, production-safe tooling** —
Bash and Python, REST APIs, SNMP/Syslog integrations, and CI-friendly test suites.

My rules of thumb: **read-only by default, fail loudly, log everything, and never surprise the
person on call at 3 AM.**

```python
juan = {
    "role": "Network Operations & Automation Engineer",
    "location": "Mexico City, Mexico",
    "works_on": ["Cisco IOS XR", "Cisco IOS XE", "EPNM", "Crosswork / WAE", "UCS", "Intersight", "Nutanix"],
    "platforms": ["NCS 55xx", "NCS 560", "ASR 920", "ASR 9000", "ASR 5000"],
    "daily_drivers": ["Python", "Bash", "Linux (RHEL)", "REST APIs", "Git"],
    "focus": [
        "Network Automation",
        "Monitoring & Observability",
        "Network Lifecycle & Compliance (EoX / PSIRT)",
        "DevOps for NetOps"
        "AI",
    ],
    "currently_learning": ["Terraform", "Ansible", "Kubernetes", "Cloud Infrastructure"],
    "principle": "automate the boring, document the rest",
}
```

---

## 🛠️ Technical Skills

**Networking**
`IOS XR` `IOS XE` `NCS / ASR platforms` `Routing & troubleshooting` `MPLS / transport`
`Network management systems (EPNM)` `Cisco Crosswork & WAE planning` `REST API integrations`

**Monitoring & Observability**
`SNMP · OIDs · MIBs` `Custom MIB definition` `SNMP traps` `Syslog` `Alarm & event integration`
`Threshold-based hardware monitoring` `Proactive health checks`

**Automation & Development**
`Python` `Bash (modular libraries)` `REST APIs` `YAML / JSON` `pytest` `Linux administration`
`Cron & scheduled jobs` `Report generation (Excel / HTML)`

**DevOps & Infrastructure**
`Kubernetes + CronJobs` `Docker` `Terraform` `Ansible` `Git & GitHub` `CI-style test suites`
`SSH hardening (ed25519)` `RHEL 8.x`

---

## 🚀 Featured Projects

### 🌡️ Hardware Health Monitor for Cisco Routers
Bash monitoring suite for IOS XR platforms that reads on-box SMART/sensor data, evaluates
configurable thresholds, and raises **SNMP traps + Syslog events** into the NMS.
Runs both off-box (SSH collector) and **on-box**, with a shared threshold model and parity tests
that guarantee both modes agree. Backed by a full unit-test suite (270+ tests).

### 🩺 NMS & Compute Health Check Suites
Automated pre/post-maintenance health checks for network management appliances and UCS compute:
service status, filesystems, database health, certificates, cluster state — rendered as a
shareable report, with an on-box mode for restricted environments and optional email delivery.
Written to run on **legacy Python 3.6** targets without external dependencies.

### 📦 Network Inventory & Lifecycle Reporting
Toolkit that consolidates inventory from multiple management platforms (network + compute) and
cross-references it against **EoX / End-of-Life** milestones and **PSIRT security advisories**,
producing a multi-sheet workbook: install base, past-LDoS hardware, vulnerable software versions,
and reconciliation against commercial datasets. All customer data stays out of the repo by design.

### 🧹 Kubernetes Log Cleaner
CronJob-based filesystem maintenance for containerized NMS platforms: watches utilization per
mount point and service, prunes eligible logs above threshold, with dry-run mode, safeguards,
and operational logging.

### 📊 Operations Dashboards & KPI Converters
Small, sharp tools that turn raw exports (performance KPIs, planning data) into clean datasets
and dashboards — archived per period so trends survive longer than a shift handover.

### 🔌 NMS Integrations
Custom MIBs, trap forwarding, Syslog normalization and REST integrations to get third-party and
custom alarms into the alarm management platform where the NOC actually looks.

> Several of these live in private repositories — customer data never touches a repo.
> Happy to walk through the architecture and share sanitized snippets.

---

## 🧭 Engineering Principles

- **Modular and reusable** — shared libraries (`common.sh`, `email.sh`, `logging.py`) over copy-paste
- **Read-only by default** — a monitoring tool should never be the outage
- **Documented in English** — comments, README, and usage examples that survive a handover
- **Test before deploy** — unit tests and dry-run modes, even for shell scripts
- **Predictable in production** — explicit paths, no surprises in cron, clear exit codes
- **No customer data in code** — synthetic values in tests, docs, and examples. Always.

---

## 📚 Currently Learning

Infrastructure as Code with **Terraform** · Network automation with **Ansible** ·
**Kubernetes** operations · **Docker** workflows · advanced **Python** for network automation ·
Cloud & DevOps practices (Cisco U learning paths)

---

## 🎮 Outside of Work

- 🎮 Beat 'em ups, roguelikes, and anything Halo — Master Chief fan since day one
- 🏋️ Functional strength training
- 🤖 AI wearables and smart glasses for hands-free field support
- ☀️ Solar + EV charging and smart-home energy projects
- 🎨 Cyberpunk: Edgerunners levels of neon in my terminal themes

---

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.kapy024.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/juanmanuelcapistran)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kapy024)

[![kapy024](https://gh-stats.com/api/kapy024)](https://gh-stats.com)

<h3 align="center">🐍 My contribution graph, eaten</h3>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/kapy024/kapy024/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)"
            srcset="https://raw.githubusercontent.com/kapy024/kapy024/output/snake.svg" />
    <img alt="snake eating my GitHub contribution graph"
         src="https://raw.githubusercontent.com/kapy024/kapy024/output/snake.svg" />
  </picture>
</p>

<p align="center">
  <sub>Generated every 12h by <a href="https://github.com/Platane/snk">Platane/snk</a> — because even the commit history deserves automation.</sub>
</p>

<p align="center"><i>Automating network operations, one script at a time. 🚀</i></p>
