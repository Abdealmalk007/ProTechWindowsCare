# ProTech Windows Care v3.3.1 — Portable Preview

**PORTABLE — NO INSTALLATION REQUIRED.** Run `ProTech_Windows_Care_Setup.exe` directly from a folder or USB drive. Optional installation is available using `--setup-ui`. This standalone launcher includes ProTech resources and uses the Windows-provided PowerShell 5.1 / .NET Framework runtime.

## What's fixed in this update
- Responsive WinForms toolbars automatically wrap buttons and resize vertically instead of hiding commands outside the window.
- Corrected the Arabic selection counter's corrupt text encoding.
- Increased sidebar width and used owner-drawn, consistently spaced navigation items with safe padding.
- Replaced unreliable font glyphs with crisp GDI+ icon drawings, preserving role-specific button colors.
- Reduced excessive unused spacing and preserved usable grid space in narrow windows.
- Separated adjacent command statements in the Dashboard, troubleshooting and report handlers.
- Retained Select All, Clear/Invert Selection, itemized preview, batch journaling and verified-backup guards.

## How modifying operations work
Supported curated WinGet installs, upgrades and uninstalls and optional current-user AppX removal are routed through the PowerShell batch runner. They require a preview, a SHA256-verified backup, explicit user approval, an Administrator/UAC prompt, and a **new verified System Restore point before any system change**. The runner stops on an error and records per-item outcomes.

Restore points do not guarantee recovery of all deleted application data, and a new point can be rate-limited (commonly once per 24 hours). Do not treat app removal as automatically reversible.

**Version 3.3.1 is Preview, not Stable.** Windows 11 Pro x64 GUI and synthetic batch testing passed. Destructive app operations have not yet been validated in a clean VM, and Windows 10/ARM64 are not independently verified. The EXE is **unsigned**, so SmartScreen may warn.

**© 2026 ProTech — All Rights Reserved** for original ProTech code, design and documents; third-party components retain their own rights.
