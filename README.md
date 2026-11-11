# ProTech Windows Care — 3.3.0 Portable Preview

![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)
![Platform](https://img.shields.io/badge/Tested-Windows%2011%20x64-blue)
![Preview](https://img.shields.io/badge/Channel-Portable%20Preview-orange)
![Unsigned](https://img.shields.io/badge/Authenticode-NotSigned-orange)

ProTech Windows Care is a portable Windows maintenance and diagnostics preview. The default executable runs directly, without installation. Despite its name, ProTech_Windows_Care_Setup.exe is portable by default; optional UI-based installation is available with --setup-ui.

## Official download
- [Direct portable EXE](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.3.0-portable-preview/ProTech_Windows_Care_Setup.exe)
- [Portable ZIP with documentation](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.3.0-portable-preview/ProTech_Windows_Care_Portable.zip)
- [Release and warnings](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/tag/v3.3.0-portable-preview)
- Verify the hash: [SHA256SUMS.txt](SHA256SUMS.txt)

## Features
- Select All and multi-selection for eligible items, preview with itemized impact and color-coded icons.
- Curated WinGet installation, upgrade and uninstall, and allowlisted current-user AppX removal through separate PowerShell process.
- SHA256-verified backup, explicit approvals, UAC elevation and a fresh verified System Restore point before changes.
- Cancellation at safe points and detailed journal, with Undo only where a supported reversal is actually possible.
- Arabic/English interface and Windows diagnostics.

## Critical limitations
This is an **experimental PREVIEW, not Stable**. Actual WinGet/AppX installation, upgrades, removal and application-data recovery were **not validated end-to-end in an isolated VM**. System Restore cannot guarantee recovery of application data. Do not use destructive actions on production computers.

Recorded QA: **13/13 groups and 38 GUI assertions passed** on Windows 11 Pro x64 build 22621. Windows 10 and ARM64 remain unverified. The program requires Windows PowerShell 5.1, .NET Framework and optional WinGet.

**NotSigned:** The EXE is not Authenticode signed and may trigger Unknown Publisher/SmartScreen prompts. Copyright is not code signing.

## Copyright and third-party components
Copyright © 2026 ProTech. **All Rights Reserved** for original ProTech-owned software and documentation. Microsoft and third-party materials remain under their respective licenses. The public end-user license allows users to download, retain backup copies and run unchanged authentic versions.

## Documentation and support
- [Arabic documentation](README_AR.md)
- [English documentation](README_EN.md)
- [QA and limitations](QA_REPORT.md)
- [Compatibility matrix](Docs/COMPATIBILITY_MATRIX.md)
- [Known limitations](Docs/KNOWN_LIMITATIONS.md)
- [Security and hash verification](SECURITY.md)
- [License](LICENSE)

Website: https://alghad.digital | Email: protech.2025.2026@gmail.com

The application's use with Windows PowerShell is not a claim that it embeds or runs an MCP server.
