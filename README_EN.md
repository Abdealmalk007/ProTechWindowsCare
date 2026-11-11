# ProTech Windows Care v3.3.0 — Portable Preview

**PORTABLE — NO INSTALLATION REQUIRED.**

Run **ProTech_Windows_Care_Setup.exe** directly from the desktop or a USB drive. Installing is optional through `--setup-ui`. The single-file executable contains the ProTech app and runs using built-in Windows PowerShell 5.1 and .NET Framework.

### Features
- Select All (eligible items only), Clear/Invert, live selection count, and color-coded icon buttons.
- Select several curated WinGet apps, then **Install**, **Upgrade**, or **Uninstall**; select allowlisted optional AppX apps for current-user removal.
- Before any changing batch: detailed per-item impact preview, SHA256-verified backup, explicit user confirmations, an elevated PowerShell runner and a freshly created and verified System Restore point.
- Sequential results and cancellation at safe points; no silent retry of previously completed batches.
- Backups, logs and history; limited automatic Undo only for genuinely reversible operations.

### Important safety caveats
System Restore generally permits **one new restore point per 24 hours** in Windows PowerShell 5.1. If no *new verified* restore point is possible, no modifying batch runs. Restore points and package identity backups do NOT guarantee restoring uninstalled app data. WinGet/AppX uninstall requires additional risk confirmation.

**Live installation, upgrade and uninstall on isolated Windows VMs have not yet been validated.** These action paths are implemented but should be regarded as experimental, not fully certified for production systems. Tested on Windows 11 Pro x64 for read-only and synthetic operations. Windows 10 and ARM64 compatibility remain unverified.

**© 2026 ProTech — All Rights Reserved** for original source, branding and documentation. Third-party software retains its original rights. This Preview is **unsigned**; SmartScreen may warn. Code copyright and Authenticode signing are different.
