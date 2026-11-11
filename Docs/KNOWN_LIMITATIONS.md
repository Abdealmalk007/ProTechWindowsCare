# Known limitations — ProTech Windows Care 3.3.1

- The button/layout and navigation repair has been tested on Windows 11 Pro x64 at 980×620, 1280×800, 1592×829 and 1920×1080, but high-DPI physical monitors and accessibility screen readers still need independent validation.
- At minimum window sizes with many section-specific actions, some actions may require scrolling within that section's toolbar; they are not removed.
- Actual WinGet/AppX install/upgrade/uninstall commands have a guarded code path, but require controlled VM tests before Stable release.
- Windows System Restore commonly limits creating a new checkpoint to one in 24 hours. The program blocks modifying actions rather than bypassing this policy.
- Restore Points and package inventory backups do not guarantee recovery of user application data after removal.
- Repairs without verified rollback, protected Windows components, firmware flashing, TPM clearing and security-service disabling are not automatically executed.
- Windows 10 x86/x64 and ARM64 compatibility are not independently validated.
- The EXE is not Authenticode-signed; SmartScreen/Unknown Publisher warnings are possible. The All Rights Reserved notice does not constitute a digital signature.
