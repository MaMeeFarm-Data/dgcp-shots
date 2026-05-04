# DGCP™ Corporate Scan OTS Registry

Date: 2026-05-04
Timezone: Asia/Bangkok
Location: MaMeeFarm (Primary DGCP Site)

---

## Record Type

corporate_scan_ots_registry

---

## Context

This file initializes the DGCP™ Corporate Scan OTS structure for the year 2026.

The registry must exist before storing any OpenTimestamps (.ots) files in this path to prevent uncontrolled folder distribution.

---

## Folder Definition

Path:
corporate/ots2026/

---

## Naming Standard

- YYYY-MM-DD_DGCP_CorporateScan_000X.md.ots

---

## Sequence Control

Start: 0001
Current: 0005
Next: 0006

---

## Structure Principle

- One Corporate Scan log = one OTS file
- OTS files must follow defined naming
- All files must stay within this declared path

---

## Integrity Rules

- Append-only
- No retroactive modification
- Registry precedes storage
- Filename must match source log

---

License:
DGCP | MMFARM-POL-2025
