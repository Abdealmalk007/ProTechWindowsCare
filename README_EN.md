# ProTech Windows Care v3.6.2 — QA & UI Hardening Portable Preview

**PRE-RELEASE / NOT STABLE** — Copyright © 2026 ProTech, All Rights Reserved.

ProTech Windows Care provides Windows diagnostics, organized maintenance tools, Back/Forward/Home/Refresh navigation, a searchable professional data view, Arabic/English interface, reporting and guarded package workflows.

## Downloads
- [Portable EXE (no installation)](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.6.2-qa-portable-preview/ProTech_Windows_Care_Setup.exe)
- [Setup EXE (installer interface)](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.6.2-qa-portable-preview/ProTech_Windows_Care_Installer_v3.6.2.exe)
- [Portable ZIP](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.6.2-qa-portable-preview/ProTech_Windows_Care_Portable.zip)
- [SHA-256 checksums](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.6.2-qa-portable-preview/SHA256SUMS.txt)

**Important:** The historical Portable EXE filename contains the word `Setup` but its default behavior is portable. Use the separate `Installer_v3.6.2.exe` file for a visible installation interface.

## What changed in v3.6.2
- Corrected hidden toolbar layout wasting vertical space in focused data details.
- Strengthened CSV spreadsheet formula neutralization against whitespace/control prefixes.
- Corrected Windows Server misdetection and synchronized release/EXE metadata.
- Preserved seven workspaces and 237 legacy review-only entries. Imported legacy commands cannot execute.

## Verification
- Windows 11 Pro x64 (build 22621): **84/84 GUI assertions**, **14/14 regression test groups**, 72 PowerShell scripts parsed, plus targeted security/compatibility checks.
- Portable and installer executables passed embedded-archive smoke checks. Master ZIP hashes validated after extraction.
- Windows system mutations were **not** performed during the QA runs.

**Windows 10 (x86/x64) and Windows 11 ARM64 remain unverified on real systems.** Real WinGet/AppX installation/removal, recovery and restore behavior must be certified in disposable VMs before a Stable release. There is no Authenticode signature; SmartScreen may warn.

Website: https://alghad.digital/programs/care/
