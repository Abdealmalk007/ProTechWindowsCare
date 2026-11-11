# ProTech Windows Care v3.3.1 — Responsive Portable Preview

**Portable — no installation required.** Download and run `ProTech_Windows_Care_Setup.exe` directly. Use `--setup-ui` only if you want optional installation.

## Fixed
- Toolbar previously fixed at 53px no longer hides action buttons; it wraps into multiple visible rows and resizes with the window.
- Sidebar navigation is wider, owner-drawn, consistently spaced and padded so Arabic section names are not cut off.
- Selection counter renders correct Arabic text instead of corrupted encoding.
- Action buttons use GDI+ vector-style icons with task-specific colors.
- Improved distribution of vertical space so the data grid remains usable at smaller window sizes.
- Cleaned up adjacent inline statements affecting Dashboard shortcuts, troubleshooting and report actions.

## Tests
Responsive UI smoke: 980×620, 1280×800, 1592×829 and 1920×1080. Previous guarded batch engine and synthetic rollback tests are retained.

## Limits
**Preview only.** WinGet/AppX modifying paths require approvals, verified backup and newly verified System Restore Point, but real upgrades/uninstalls have NOT been VM-certified. Windows 10/ARM64 remain unverified. This EXE is **unsigned**; Unknown Publisher / SmartScreen warnings are possible.

**© 2026 ProTech — All Rights Reserved** for ProTech original source. Third-party programs keep their own licenses.
