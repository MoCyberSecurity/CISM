
# Incident Response Playbook Example

This playbook demonstrates a standardized tactical response procedure aligned with the **Incident Response Plan (IRP)**.  
It supports repeatable, fast, and legally sound incident handling.

---

## Incident Type
Ransomware Infection

---

## Detection Triggers

- Endpoint antivirus or EDR alert
- SIEM correlation rule indicating encryption behaviour
- User-reported file inaccessibility

---

## Initial Response Actions

### Identification
- Validate endpoint compromise.
- Collect host logs and alert metadata.
- Determine spread indicators.

---

### Containment

- Immediately isolate affected systems.
- Block suspicious IP addresses at firewall.
- Disable compromised credentials.

---

### Eradication

- Remove malware artefacts.
- Reimage infected systems.
- Patch exploited vulnerabilities.
- Reset affected accounts.

---

### Recovery

- Restore data from backups meeting RPO objectives.
- Validate system integrity.
- Monitor closely for reinfection.

---

### Lessons Learned

- Conduct post-incident review meeting.
- Identify security control gaps.
- Update detection signatures.
- Improve user awareness training.

---

## Escalation Matrix

| Severity | Notification |
|----------|----------------|
| Critical | CEO, Legal, PR, Regulators |
| High | CIO, SOC Leadership |
| Medium | SOC Management |
| Low | Incident ticket & routine reporting |

---

---

## Exam Relevance

- Demonstrates **IR lifecycle phases**.
- Shows **classification-based escalation**.
- Integrates detection, response, and recovery objectives.
