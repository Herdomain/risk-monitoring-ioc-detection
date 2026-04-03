# 🔍 Risk Monitoring & Threat Detection (PRTG + IoCs)

Threats that go unmonitored go undetected.

This project designs a proactive monitoring strategy using Paessler PRTG across three critical business systems, an SQL database, a Linux development environment, and an IIS web server,  mapping each to real-world Indicators of Compromise before an incident occurs.

---

## Why These Systems

Each monitored asset was selected based on data sensitivity and business impact:

- **SQL Database** — Holds proprietary and financial data; primary target for exfiltration and injection attacks
- **Linux Development Environment** — Exposed to privilege escalation and unauthorized access attempts
- **IIS Web Server** — Public-facing attack surface vulnerable to brute force, DDoS, and web application exploits

---

## Monitoring Strategy

Each system is assigned PRTG sensors with defined alert thresholds tied directly to known attack behaviors.

Thresholds are calibrated against expected baseline activity to balance detection accuracy and minimize alert fatigue.

| System | Sensor Focus | IoCs Monitored |
|---|---|---|
| SQL Database | Query volume, authentication events | Unusual query patterns, failed logins, data exfiltration |
| Linux Environment | CPU load, user activity, process monitoring | Privilege escalation, unauthorized access, abnormal processes |
| IIS Web Server | Bandwidth usage, request rates, error codes | Brute force attempts, DDoS patterns, suspicious traffic spikes |

---

## If a Threat Were Detected

1. **Validate** — Confirm abnormal sensor activity against established baseline behavior
2. **Investigate** — Identify affected systems and entry points; analyze logs for attack patterns
3. **Escalate** — Notify stakeholders based on severity classification; document findings and potential impact
4. **Contain** — Block suspicious IPs, sessions, or processes; isolate affected systems if needed
5. **Improve** — Tune thresholds and expand sensor coverage based on findings

---

## Framework Alignment

| Framework | Application |
|---|---|
| NIST SP 800-61 | Incident detection and response structure |
| MITRE ATT&CK | IoC mapping to known attack techniques |
| CIS Controls | Asset prioritization and monitoring best practices |

---

## Artifacts & Outputs

- Sensor configuration and threshold definitions per system
  
- IoC mapping table linking sensors to real-world attack patterns
  
- Monitoring coverage map across critical assets

> 📌 *Sensor table and PRTG screenshots coming soon.*

