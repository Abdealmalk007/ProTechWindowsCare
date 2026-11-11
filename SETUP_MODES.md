# Portable vs Setup: v3.3.1

- **Portable EXE:** ProTech_Windows_Care_Setup.exe runs the app directly without installation.
- **Portable ZIP:** Contains the same executable, with guidance and proprietary license.
- **Separate Setup EXE:** ProTech_Windows_Care_Installer_v3.3.1.exe is a Windows-native IExpress self-extracting package that launches the verified executable with --setup-ui.
- Original app SHA256: 1EB1E61542C99A1A623177B63B10DE47D4EA69E0E572E60453CF88AEE903D419
- Setup wrapper SHA256: 0898F8DE8D0DB6F1F1B6FF540CCB9D0CFEC7CFC1622239A2A10E2F98BF615E10

The CAB was extracted and its embedded app validated by SHA256 **without executing the installer**. The installation workflow itself was NOT tested in a disposable VM. Both programs are unsigned, and the full WinGet/AppX destructive pathways remain experimental.
