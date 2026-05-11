# CyberHub

## Overview

CyberHub is my private cybersecurity learning and operations environment built to develop real-world investigative and defensive security skills through hands-on execution.

This repository is not intended to be a polished "hacker dashboard," social media project, or certification showcase. Its primary purpose is to support operational learning across SOC workflows, incident response, threat hunting, malware traffic analysis, telemetry analysis, and detection engineering.

The environment is designed around repetition, investigation, documentation, and validation rather than passive studying or tutorial-based learning.

The goal is to progressively build the mindset and workflow discipline required for real-world defensive security roles.

---

## Primary Focus Areas

Current areas of study and development include:

- Security Operations Center (SOC) workflows
- Incident response investigations
- Threat hunting methodology
- Detection engineering
- Malware traffic analysis
- Windows telemetry analysis
- Sysmon and event log analysis
- DNS and network investigations
- PowerShell investigation techniques
- Sigma rule development
- KQL learning and query development
- MITRE ATT&CK mapping
- PCAP and network traffic analysis
- Evidence collection and investigative documentation

---

## Learning Philosophy

This environment follows an execution-first approach.

The focus is on:

- generating telemetry intentionally
- analyzing real logs and artifacts
- validating assumptions
- documenting findings
- identifying knowledge gaps
- improving investigative reasoning over time

Every major task or investigation is expected to include:

- hands-on execution
- screenshots or evidence collection
- validation/testing
- written explanations in my own words
- retention review
- confusion or gap tracking for follow-up learning

The objective is to develop operational capability, not just theoretical familiarity.

---

## Environment Structure

### Dashboard Layer

The CyberHub dashboard serves as the operational cockpit for organizing workflows, investigations, learning paths, and execution tracking.

### VS Code Workspace

The VS Code workspace acts as the primary operational environment for:

- scripting
- detection development
- telemetry analysis
- investigations
- PCAP review
- documentation
- evidence management

### Obsidian Knowledgebase

Obsidian is used as the long-term knowledge and investigation repository for:

- research notes
- investigation timelines
- detection logic
- telemetry observations
- concepts and retention review
- investigative writeups

### Evidence and Documentation

Screenshots, logs, exports, and investigation artifacts are stored throughout the repository to support reproducibility, validation, and documentation discipline.

---

## Repository Structure

```text
CYBERHUB/
|
|-- archive/
|-- datasets/
|-- detections/
|-- evidence/
|-- labs/
|-- notes/
|-- portfolio-assets/
|-- screenshots/
|-- scripts/
|-- telemetry/
|-- templates/
|-- tools/
|-- writeups/
```

---

## Key Directories

| Directory | Purpose |
|---|---|
| `datasets/` | Sample logs, Sigma examples, Atomic Red Team data |
| `detections/` | Sigma, KQL, Suricata, YARA, and detection-related work |
| `evidence/` | Investigation exports, screenshots, PCAPs, timelines |
| `labs/` | Hands-on lab environments and focused training areas |
| `notes/` | Operational notes, concepts, and investigative learning |
| `scripts/` | Automation, PowerShell, and Python tooling |
| `telemetry/` | Sysmon, Zeek, Suricata, Windows logs, and PCAP storage |
| `templates/` | Investigation, hunt, and detection documentation templates |
| `writeups/` | Investigative writeups and analytical reporting |

---

## Current Roadmap

### Phase 0
Foundation and workflow setup

- Workspace organization
- Dashboard refinement
- Documentation standards
- Screenshot and evidence workflow
- Operational structure design

### Phase 1
SOC and telemetry fundamentals

- Security Onion lab
- Windows VM telemetry generation
- Sysmon deployment
- Event log analysis
- Basic investigations
- Atomic Red Team testing

### Phase 2
Threat hunting and investigation workflows

- Process analysis
- Behavioral investigations
- DNS analysis
- PowerShell analysis
- Timeline building
- Investigation pivoting

### Phase 3
Malware traffic analysis

- PCAP analysis
- Beaconing identification
- IOC extraction
- DNS and HTTP traffic analysis
- Wireshark and Zeek workflows

### Phase 4
Detection engineering

- Sigma rule creation
- KQL development
- Detection tuning
- Validation testing
- MITRE ATT&CK alignment

---

## Long-Term Goal

The long-term objective of CyberHub is to build practical investigative capability and develop the operational thinking required for:

- SOC analyst roles
- incident response
- threat hunting
- detection engineering
- investigative cybersecurity operations

This repository represents an ongoing learning process centered on execution, validation, and continuous improvement.