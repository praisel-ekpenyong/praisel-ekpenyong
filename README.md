#Hi 👋, I'm Praisel Ekpenyong

### Entry-Level SOC Analyst

📧 [ekpenyongpraisel@gmail.com](mailto:ekpenyongpraisel@gmail.com) | 🔗 [LinkedIn](linkedin.com/in/praiselekpenyong)

**📄 [Download One-Page Canva-Style Portfolio Summary (PDF)](Portfolio-Summary.pdf)**

This is my **hands-on SOC Analyst Portfolio** — a collection of realistic investigations built in a home lab using Splunk, Wazuh, Microsoft Sentinel, Sysmon, Zeek, and Caldera/Atomic Red Team.

I focused on the exact skills hiring managers look for in a Junior/Tier 1 SOC role: alert triage, log analysis, false-positive discipline, escalation documentation, and clear ticket-style communication.

---

### 🧭 Quick Navigation

- [Featured Cases](#featured-cases)
- [Full Case Studies](#full-case-studies)
- [Detections & Playbooks](./detections/)
- [Lab Setup](./lab/)
- [Playbooks](./playbooks/)

---

### Skills at a Glance

- **Alert Triage & Investigation** – Splunk SPL, Sentinel KQL, Wazuh
- **Log & Endpoint Analysis** – Sysmon, Windows Security, PowerShell Logs
- **Network Validation** – Zeek, Wireshark, short PCAP review
- **Detection Engineering** – Rule writing + false-positive tuning
- **Documentation** – Ticketing, escalation notes, shift handoffs

---

### Featured Cases (My Strongest Work)

**🔥 Case 02 – Encoded PowerShell False Positive**  
Investigated high-severity encoded PowerShell alert → confirmed legitimate NinjaOne RMM activity using parent-process analysis, script-block logs, baseline, and vendor TLS traffic. Closed as benign with tuning recommendation.

**🔥 Case 05 – Microsoft Sentinel Multi-Stage Attack Chain**  
Correlated RDP brute force → successful Logon Type 10 → PowerShell execution → outbound TLS using KQL. Delivered full timeline and strong Tier 1→Tier 2 escalation note.

**🔥 Case 06 – PCAP-Backed Beaconing vs Legitimate Updater**  
Analyzed recurring HTTPS traffic that looked like C2. Used Zeek metadata, Task Scheduler, and short PCAP to prove it was legitimate scheduled update activity. Documented tuning opportunities.

---

### Full Case Studies

<details>
<summary>📋 Click to expand — All 9 Cases (with direct links)</summary>

| #   | Case Title | Key Skills Shown | Link |
| --- | --- | --- | --- |
| 01  | Failed Logon Followed by Successful Authentication | Authentication correlation, baseline check, escalation | [View](./case-studies/01_failed_logon_successful_authentication.md) |
| 02  | Encoded PowerShell False Positive (NinjaOne RMM) | False-positive discipline, baseline analysis, tuning | [View](./case-studies/02_powershell_false_positive_admin_tool.md) |
| 03  | New Local Administrator Account Creation | Persistence review, unauthorized change detection | [View](./case-studies/03_new_local_admin_account_creation.md) |
| 04  | Suspicious Outbound Connection Review | Process-to-network correlation | [View](./case-studies/04_suspicious_outbound_connection_review.md) |
| 05  | Microsoft Sentinel Multi-Stage Attack Chain | KQL correlation, full kill-chain timeline | [View](./case-studies/05_sentinel_multistage_attack_chain.md) |
| 06  | PCAP-Backed Beaconing vs Legitimate Update Traffic | Zeek + Wireshark validation, updater vs C2 | [View](./case-studies/06_pcap_beaconing_vs_legitimate_update_traffic.md) |
| 07  | SOAR Edge Case – VPN False Block | Automation logic review, playbook improvement | [View](./case-studies/07_soar_edge_case_vpn_false_block.md) |
| 08  | Phishing Email with Malicious Attachment | Email header + endpoint correlation | [View](./case-studies/08_phishing_malicious_attachment_triage.md) |
| 09  | Scheduled Task Persistence After PowerShell | Persistence detection, process chain analysis | [View](./case-studies/09_scheduled_task_persistence.md) |

</details>

---

**Full Portfolio:** [github.com/praisel-ekpenyong/Portfolio](https://github.com/praisel-ekpenyong/Portfolio)  
**Last updated:** April 2026

---

*Built with real lab telemetry (Caldera + Atomic Red Team). Focused on practical Tier 1 SOC skills: triage, investigation, documentation, and escalation.
