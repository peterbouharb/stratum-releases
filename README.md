# Cledion Stratum — Downloads

Public download home for **Cledion Stratum**, the desktop app for data-center
monitoring (SNMP device discovery, sensors, dashboards, alerting — all local,
no server to stand up).

The application source is developed in a private repository; this repository
hosts only the release installers so that anyone can download them.

**Download page: https://peterbouharb.github.io/stratum-releases/**

Or grab the latest build directly:

| Platform | Download |
| --- | --- |
| Windows installer (recommended) | [Cledion-Stratum-Setup.exe](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum-Setup.exe) |
| Windows MSI | [Cledion-Stratum.msi](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum.msi) |
| macOS (Apple Silicon) | [Cledion-Stratum-arm64.dmg](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum-arm64.dmg) |
| macOS (Intel) | [Cledion-Stratum-x64.dmg](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum-x64.dmg) |
| Linux (Debian/Ubuntu) | [Cledion-Stratum.deb](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum.deb) |
| Linux (AppImage) | [Cledion-Stratum.AppImage](https://github.com/peterbouharb/stratum-releases/releases/latest/download/Cledion-Stratum.AppImage) |

## Verify your download

Every release includes a `SHA256SUMS.txt` asset. After downloading, compare
the hash of your file against the one listed there:

- **Windows (PowerShell):** `Get-FileHash .\Cledion-Stratum-Setup.exe -Algorithm SHA256`
- **macOS / Linux:** `shasum -a 256 Cledion-Stratum-Setup.exe`

If the hash doesn't match the entry in `SHA256SUMS.txt`, don't run the
installer — re-download it from this repository only.

## About unsigned pre-release builds

Current builds are **unsigned pre-release builds** (code signing is being set
up). Operating systems will warn on first run:

- **Windows SmartScreen** — "Windows protected your PC": click
  **More info → Run anyway**.
- **macOS Gatekeeper** — right-click the app → **Open**, or allow it under
  **System Settings → Privacy & Security → Open Anyway**.

Only download Cledion Stratum from this repository or the download page
above — no other source is official.
