# ProTech Windows Care v3.6.2 — QA / UI Hardening Portable Preview

**PRE-RELEASE — NOT STABLE.** ProTech Windows Care is a Windows diagnostics and guarded maintenance utility. The EXE defaults to **Portable** mode (no installation). Optional `--setup-ui` opens the installer.

## Fixed
- Fixed empty vertical space in the Data Workspace after the context toolbar is hidden in focused details mode.
- Hardened CSV export against spreadsheet-formula injection with leading tabs, control characters, and whitespace.
- Windows Server builds are no longer mistaken for Windows 10/11 client systems.
- Version metadata and release information synchronized to 3.6.2.
- Preserved Back/Forward/Home/Refresh, navigation history, 7 specialist groups, searchable data grid and Arabic/English controls.

## Verification
- Windows 11 Pro x64 build 22621: WinForms GUI 84/84 checks; 14 regression groups; additional PowerShell 5.1 parser/WinGet safety/CSV checks; portable executable smoke and package checksum checks.
- Tests were read-only or synthetic and did not uninstall software, change Windows privacy settings, or apply system repairs.

## Unverified / precautions
- **Windows 10 x86/x64 and Windows 11 ARM64 were not independently executed or certified.** The source contains compatibility guards, but this alone is not proof of function parity.
- Real WinGet/AppX installation, upgrade, removal, application-data restoration, and recovery after interrupts need dedicated disposable Windows 10/11 VMs with snapshots.
- Code has **no Authenticode certificate**; SmartScreen may warn. All Rights Reserved is copyright, not digital signing.
- Do not rely on this preview for automatic destructive changes to a production computer.