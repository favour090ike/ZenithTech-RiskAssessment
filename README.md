# ZenithTech Risk Assessment: Threat Scenario R-001

##  Project Overview
This project demonstrates a quantitative approach to managing high-impact cyber threats. I conducted a risk analysis of a destructive malware attack targeting developer infrastructure and proposed a technical mitigation strategy to protect business continuity.

##  The Scenario
**Threat:** A hacker gains unauthorized access to a developer's workstation and executes a script to wipe the entire system.
**Inherent Risk Score:** 15/25 (High)

##  Mitigation Strategy
To move the risk from **High** to **Low**, I implemented a triple-layer defense:
1. **MFA (Preventive):** Stops unauthorized access at the front door.
2. **EDR (Detective):** Kills malicious "wiper" processes in real-time.
3. **Cloud Backups (Recovery):** Ensures zero data loss even if a system is wiped.


