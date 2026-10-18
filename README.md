# CIP-B106 — Mobile and IoT Forensics Case Study 3

## Echo Show 8 IoT Evidence Investigation

**Student:** Asmau Danzaria  
**Registration Number:** 2617285  
**Case ID:** CIPB106-EchoShow8-2617285

### Overview

This case study examines a supplied Amazon Echo Show 8 training evidence image using forensic analysis techniques.

The investigation covers:

- Evidence handling and integrity verification
- Device and operating system identification
- User and application artefacts
- Network and connectivity artefacts
- WebView/browser artefacts
- Communication artefacts
- Media artefacts
- Timeline reconstruction
- Cross-source corroboration
- Manual validation of forensic tool results

### Key Findings

The evidence identified an Amazon athena/AEOAT device running Fire OS 7.5.6.0.

The examination also identified stored Wi-Fi and Amazon connectivity telemetry, WebView/browser artefacts, communication-related databases, and media-related artefacts.

The examined SMS/MMS databases contained no returned message records. Media files with PNG/MP4-style names were also manually validated and could not be confirmed as standard PNG/MP4 files.

A chronology was constructed using independent device, media and connectivity artefacts while maintaining the limitations of the supplied evidence.

### Repository Contents

```text
Case_Study_Report/   → Final forensic report
Commands/            → Commands used during the investigation
Screenshots/         → Investigation screenshots organised by task
Evidence_Logs/       → Hashes, findings and tool documentation
```

### Forensic Approach

The investigation was performed using read-only forensic analysis of the supplied evidence. Original evidence was preserved and analysis was conducted using working copies.

The examination did not include:

- Live device acquisition
- Cloud account access
- Alexa account access
- Device unlocking or rooting
- Public uploading of evidence
- Claims of physical presence or person identity based solely on network artefacts

### Note

The original forensic image and other sensitive evidence are intentionally **not included in this repository**.

This repository contains the investigation documentation and supporting materials only.
