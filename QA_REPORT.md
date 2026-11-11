# QA Report â€” ProTech Windows Care 3.3.1

14/14 test groups pass; 40 WinForms assertions pass; tests include 980Ã—620, 1280Ã—800, 1592Ã—829 and 1920Ã—1080 window sizes. The Arabic selection counter, sidebar rendering, color-coded drawn icons, batch-creation and navigation actions passed. Synthetic 20-item batch/rollback and a 3-item separate PowerShell runner passed.
Test host: Windows 11 Pro x64 Build 22621.

The release is Preview, not Stable. No actual production package removal/upgrade was performed during this development session. Isolated VM tests for real WinGet/AppX changes and application-data recovery, Windows 10/ARM64 platforms and Authenticode signing remain outstanding. Restore Point verification and separate user approval are required before changing operations; restore points are not full application data backups.