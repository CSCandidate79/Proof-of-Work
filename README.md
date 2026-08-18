# Proof-of-Work
Cybersecurity portfolio showcasing practical home lab deployments &amp; risk assessments. Features defensive engineering, security hardening, and technical remediation documentation. Powered by a strong operational foundation, CompTIA Security+, and active progression toward the CISSP.
---
## Lab Architecture & Tools
* **Virtual Software Platform:** VMWare Workstation Pro
* **SIEM/EDR Manaager:** Wazuh VM (Ubuntu OS)
* **Target Endpoint:** Windows 11 Enterprise with Microsoft Sysmon installed and forwarding events.
* **Attack Emulation Platform:** AtomicRedTeam
---
## Documenting of Simuulations
With the goal of simulating real-world Security Operations Center (SOC) workdflows, all simulation reports in this repository attempt
to adhere to professional reporting standards:
* **Framework:** Simulations are mapped directly to the MITRE ATTACK Framework to main industry-standard threat taxonomy.
* **BLUF (Bottom Line Upfront):** Each report will begin a high-level executive summary and detection status for rapid overview.
* **Evidence-Based:** ALL detections are back by raw, parsed JSON telemetry from Sysmon and Wazuh.
* **Mitigations:** Hardening recommendations are based on defense in-depth principles (ie. AppLocker, GPO, PowerShell hardening).
---
## Simulation Logs (Index)
Will include date, technique tested, attack tool, detection status, report link
