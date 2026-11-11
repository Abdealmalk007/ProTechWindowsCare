# ProTech Windows Care Changelog

## v3.3.0 — Portable Batch Preview (2026-11-11)

- Added BatchEngine.psm1 with durable batch IDs and journals for up to 25 selected items.
- Added batch impact preview, verified SHA256 backup manifest and separate data-loss risk approval.
- Added Runner.Batch.ps1 for process-isolated PowerShell execution with Windows UAC on real changes.
- Wired package Install/Upgrade/Uninstall and optional current-user AppX removal to reviewed batch commands.
- Added hard checkpoint gate: create and verify a new Windows Restore Point before the first system change or block all changes.
- Added safe cancellation requests, per-item success/failure journal, partial status, and refused duplicate executions.
- Extended existing color-coded icons/Select All while preventing protected AppX selection.
- Tested 20 synthetic items (execute + rollback), separate PowerShell runner, restore-point fail-closed and GUI.
- Portable EXE and license All Rights Reserved for original ProTech code.
- Release remains Preview because destructive VM tests, full Windows 10/ARM64 support, and digital signing are outstanding.
