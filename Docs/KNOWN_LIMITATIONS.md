# Known limitations — v3.3.0 Preview

1. Real WinGet and AppX actions are implemented and wired into the UI, but have not undergone destructive VM acceptance tests. Do not treat them as Stable-certified for important machines.
2. The batch backup records application identity/version and does not guarantee restoration of app data. There is no automatic Undo for WinGet/AppX uninstalls; users must confirm the irreversible-data risk.
3. The System Restore gate requires a *newly created* and verified restore point. Windows PowerShell 5.1 generally allows one checkpoint in a 24-hour period. No bypass or reuse of an old checkpoint occurs.
4. Privilege escalation uses Windows User Account Control. If UAC is canceled or a standard-user admin profile cannot access the originating user data root, the operation fails safely.
5. WinGet package state and version read-back are not fully independently verified in an isolated VM; engine reports process exit status and stops on nonzero error.
6. Windows Update repair/installation, full privacy and startup batch adapters, and Win11 Creator remain incomplete or read-only; BIOS flash/TPM Clear/Defender disabling are not automated.
7. Windows 10 x86/x64 and Windows 11 ARM64 compatibility and clean-machine DPI accessibility testing are not validated.
8. No Authenticode signing certificate is available. The executable may show Unknown Publisher / SmartScreen warnings. All Rights Reserved is copyright, not digital signing.
9. The single executable contains ProTech resources, but relies on system Windows PowerShell 5.1, .NET Framework and optional WinGet.
10. The result is a Portable Preview suitable for evaluation and transparent beta/pre-release publishing, not a certified general Stable release.
