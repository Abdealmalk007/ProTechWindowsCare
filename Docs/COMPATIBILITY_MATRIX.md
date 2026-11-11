# Compatibility and validation matrix — v3.3.0

| Environment / function | Result |
|---|---|
| Windows 11 Pro x64, Build 22621 | PASS: GUI, read-only inspection, synthetic batch execution |
| 20-item MockFileSet batch and Undo | PASS |
| Standalone PowerShell runner, 3 synthetic items | PASS |
| Restore point refuses execution without Administrator/effective checkpoint | PASS |
| Protected AppX not selectable | PASS |
| Single EXE Portable with no sidecars | PASS |
| Optional installer in isolated path | PASS |
| Actual WinGet Install/Upgrade/Uninstall in VM | UNVERIFIED |
| Actual AppX removal and application data recovery in VM | UNVERIFIED |
| Windows Update repair execution | NOT IMPLEMENTED in BatchEngine |
| Windows 10 x64 / x86 | UNVERIFIED |
| Windows 11 ARM64 | UNVERIFIED |
| Authenticode code signature | NOT SIGNED |
| Win11 custom ISO Creator build | READINESS ONLY / BLOCKED |
| System Restore new checkpoint on real device | NOT RUN DURING DEVELOPMENT |

**Never infer Stable certification from successful synthetic tests.** Browser/UI/PowerShell changes on production Windows require user's per-operation approval and verified restore point. Windows 10 reached end of general support on 2025-10-14; this tool cannot supply OS security updates.
