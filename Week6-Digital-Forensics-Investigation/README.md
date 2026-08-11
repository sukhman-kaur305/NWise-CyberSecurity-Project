# Week 6 – Digital Forensics Investigation

## Overview

This project was completed as part of the **NWise Student-Led Cybersecurity Internship – Week 6 Digital Forensics Lab**.

The objective of the investigation was to follow a structured digital forensic process while examining a forensic image from the **Digital Corpora `nps-2009-ntfs1` dataset**.

The investigation focused on evidence preservation, SHA-256 integrity verification, forensic image analysis using Autopsy, keyword searching, examination of deleted files and artifacts, and evidence export.

---

## Case Information

| Field | Details |
|---|---|
| Case Reference | NWise_DF001 |
| Role | Junior Digital Forensic Analyst |
| Investigation Type | Digital Forensics |
| Dataset | nps-2009-ntfs1 |
| Forensic Image | ntfs1-gen2.E01 |
| Forensic Tool | Autopsy 4.23.1 |
| Hash Algorithm | SHA-256 |
| Environment | Windows |

---

## Investigation Objectives

The main objectives of the investigation were to:

- Create a structured forensic investigation workspace.
- Acquire forensic evidence from Digital Corpora.
- Preserve the original evidence.
- Create a separate working copy for analysis.
- Verify evidence integrity using SHA-256.
- Create a forensic investigation case in Autopsy.
- Examine the available NTFS file-system structure.
- Search for potentially relevant information using keywords.
- Examine deleted-file and activity artifacts.
- Export relevant evidence.
- Document findings in a professional forensic investigation report.

---

## Investigation Folder Structure

The following folder structure was used to maintain evidence separation and organization:

```text
NWise_DF001/
│
├── 01_Original_Evidence/
│
├── 02_Working_Copy/
│
├── 03_Autopsy_Case/
│
├── 04_Exports/
│   └── EFS-key-info.txt
│
├── 05_Notes/
│   └── Screenshots/
│
└── 06_Report/
    └── NWise_DF001_Final_Verified_Investigation_Report.pdf
