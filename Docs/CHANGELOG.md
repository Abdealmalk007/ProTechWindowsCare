# CHANGELOG — ProTech Windows Care

## 3.3.1 — Responsive UI Portable Preview (2026-11-11)
- Fixed toolbar clipping caused by WrapContents=false and 53px static height.
- Added dynamic vertical reflow for command/toolbox panels, including scroll fallback when needed.
- Improved minimum-window layout and preserved a usable grid at 980×620.
- Implemented fixed-height owner-drawn right sidebar with text padding.
- Fixed Arabic selection badge character encoding via localization key.
- Replaced Unicode text icons with GDI+ drawn reusable icons; retained functional button colors.
- Updated visible product version and optional installer metadata.
- Normalized Dashboard shortcuts, troubleshooting actions and report cases.
- Kept gated batch execution safeguards, no unintended Windows changes during testing.

Known gaps: Actual WinGet/AppX modifying actions need isolated VM acceptance tests; no Authenticode certificate. Windows 10 and ARM64 remain unverified.
