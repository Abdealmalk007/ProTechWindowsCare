# ProTech Windows Care v3.3.0 — Portable Batch Preview

**Portable / No installation required** — Download and double-click `ProTech_Windows_Care_Setup.exe`.

### Features
- Multi-select and Select All (eligible items only), preview and contextual colored icon buttons.
- Real batch execution paths wired for approved WinGet install/upgrade/uninstall and current-user allowlisted AppX removal; each runs through a separate Windows PowerShell process.
- Per-item impact preview and journal, SHA256 backup checks, explicit user approval and UAC.
- New, verified Windows System Restore point mandatory before the first Windows modification. Missing privileges, disabled protection or the daily checkpoint limit blocks all changes.
- Cancel pending items and inspect individual operation outcomes.
- Arabic/English UI and Windows hardware/repair diagnostics.

### Verified QA
13/13 test groups, 38 WinForms assertions, 20-item synthetic batch and rollback, three-item separate PowerShell process test, fail-closed restore point test. **No real program was deleted or upgraded during development.**

### Limitations
This release is **Preview**, not Stable: no end-to-end installation/removal on isolated VM; no guaranteed recovery of deleted application data; Windows 10/ARM64 not validated; no Authenticode certificate. Antivirus/SmartScreen may warn about an unsigned publisher. See QA_REPORT.md and KNOWN_LIMITATIONS.md.

### Legal
Copyright © 2026 ProTech. **All Rights Reserved** for original ProTech components. Microsoft and third-party assets under their respective licenses.
