# ProTech Windows Care — v3.3.1 Responsive Portable Preview

![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)
![Preview](https://img.shields.io/badge/Release-Portable%20Preview-orange)
![Windows](https://img.shields.io/badge/QA-Windows%2011%20x64-blue)
![Unsigned](https://img.shields.io/badge/Authenticode-NotSigned-orange)

ProTech Windows Care is a Windows diagnostics and maintenance utility with guarded package operations. This is a **Preview, not Stable**.

## Two editions — choose one

1. **Portable, no installation:** [EXE direct](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.3.1-responsive-portable-preview/ProTech_Windows_Care_Setup.exe) or [Portable ZIP](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.3.1-responsive-portable-preview/ProTech_Windows_Care_Portable.zip). The historical EXE filename includes Setup, but its default mode is **portable**.
2. **Separate Setup installer:** [ProTech_Windows_Care_Installer_v3.3.1.exe](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/download/v3.3.1-responsive-portable-preview/ProTech_Windows_Care_Installer_v3.3.1.exe). This unsigned Windows IExpress wrapper extracts the same ProTech EXE and launches it with the **--setup-ui** argument, opening the optional installation interface. Actual installation was not acceptance-tested inside a VM.

[Verify SHA256 hashes](SHA256SUMS.txt) | [Release page](https://github.com/Abdealmalk007/ProTechWindowsCare/releases/tag/v3.3.1-responsive-portable-preview)

## Improvements in 3.3.1

- Responsive toolbar wraps controls instead of hiding them when the window is resized.
- Fixes corrupted Arabic selection-counter text, improves the RTL owner-drawn sidebar and spacing.
- GDI+ task icons with clearer colors and improved room for grids, fixes for Dashboard, reports and troubleshooting actions.

## Safety, validation and license

Recorded tests: **14/14 regression groups and 40/40 WinForms GUI assertions** on Windows 11 Pro x64, at 980x620, 1280x800, 1592x829 and 1920x1080. Synthetic 20-item batch and separate PowerShell runner passed. Real WinGet/AppX package removal, upgrade and app-data recovery are **not VM-certified**; Windows 10 and ARM64 remain unverified. Use a disposable test system and independent backups. System Restore does not guarantee restoration of application data.

**Unsigned:** both editions have no trusted Authenticode publisher signature and may cause Unknown Publisher/SmartScreen warnings. All Rights Reserved is a copyright notice, not code signing.

Copyright © 2026 ProTech — **All Rights Reserved** for original ProTech materials; Microsoft and third-party components retain their licenses. Public personal and internal business use of authentic unmodified releases follows [LICENSE](LICENSE). This repository does not publish proprietary application source.

## Documentation
- [Arabic](README_AR.md) | [English](README_EN.md)
- [QA results](QA_REPORT.md) | [Structured QA](QA/FINAL_QA_PUBLIC.json)
- [What was fixed](Docs/RESPONSIVE_FIX_REPORT_AR.md) | [Known limitations](Docs/KNOWN_LIMITATIONS.md)
- [Setup modes](SETUP_MODES.md) | [Security](SECURITY.md)

Website: https://alghad.digital/programs/care/ | Support: protech.2025.2026@gmail.com
