# Threat Hunt Template

## Hunt Information

| Field | Value |
|---|---|
| Hunt ID | |
| Hunt Name | |
| Analyst | |
| Date | |
| Status | |
| Priority | |

---

## Hunt Objective

Describe the purpose of the hunt.

---

## Hunt Hypothesis

Document the hypothesis being tested.

Example:

> If suspicious PowerShell execution occurred, then Sysmon Event ID 1 and PowerShell logs should contain encoded or abnormal execution patterns.

---

## Environment Scope

| Component | Details |
|---|---|
| Host Systems | |
| Logging Sources | |
| Security Tools | |
| Network Scope | |

---

## Telemetry Sources

- Sysmon
- Windows Event Logs
- Zeek
- Suricata
- DNS Logs
- PCAP
- PowerShell Logs
- Security Onion

---

## Hunt Queries

### KQL Queries

```kql
// Insert KQL queries
```

### Sigma Logic

```yaml
title:
id:
status:
description:
logsource:
detection:
condition:
level:
```

### PowerShell Commands

```powershell
# Insert PowerShell commands
```

---

## Investigation Steps

1.
2.
3.
4.

---

## Findings

Document suspicious or confirmed findings.

---

## Indicators Identified

### IP Addresses
- 

### Domains
- 

### File Hashes
- 

### Processes
- 

### Users
- 

---

## Evidence Collected

| Evidence Type | Location |
|---|---|
| Screenshot | |
| PCAP | |
| Log Export | |
| Detection Output | |

---

## MITRE ATT&CK Mapping

| Technique | Description |
|---|---|
| | |

---

## Detection Opportunities

Document opportunities for:
- Sigma rules
- KQL detections
- alerting improvements
- telemetry tuning

---

## False Positives

- 
- 

---

## Lessons Learned

- 
- 

---

## Follow-Up Actions

- 
- 

---

## Final Assessment

Provide final conclusions and operational recommendations.