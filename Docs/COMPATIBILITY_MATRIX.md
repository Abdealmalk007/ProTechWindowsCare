# ProTech Windows Care 3.3.1 — test matrix

| Item | Verification |
|---|---|
| Windows 11 Pro x64 build 22621 | PASS: GUI, read-only diagnostics and synthetic tests |
| WinForms layout 980×620 | PASS |
| WinForms layout 1280×800 | PASS |
| WinForms layout 1592×829 (user's screenshot size) | PASS |
| WinForms layout 1920×1080 | PASS |
| Arabic selection counter | PASS UTF-8 localization |
| Sidebar labels and navigation | PASS owner-drawn fixed 32px items |
| All toolbar command icons | PASS GDI+ image exists |
| Select All / Clear selection | PASS button click tests |
| Dashboard shortcut to optional apps | PASS button click |
| Synthetic 20-item batch execute & Undo | PASS |
| Separate PowerShell runner synthetic batch | PASS |
| Backup/restore-point guard | PASS synthetic fail-closed |
| Real WinGet/ AppX updates & deletion in a VM | NOT TESTED |
| Windows 10 x86/x64 / ARM64 | NOT VERIFIED |
| Physical monitors at 125/150% system DPI | NOT VERIFIED |
| Authenticode digital signature | NOT SIGNED |

**Preview only:** success for layout and synthetic operations must not be presented as stable certification for system-changing tasks. Restore points cannot guarantee application data recovery.
