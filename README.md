# Cledion Stratum Downloads

Public download home for **Cledion Stratum**, the desktop app for data-center
monitoring. The application source is developed privately; this repository
hosts only the download page, installers, and checksums.

Download page:
<https://peterbouharb.github.io/stratum-releases/>

Direct Windows downloads:

| Platform | Download |
| --- | --- |
| Windows installer (recommended) | [Cledion-Stratum-Setup.exe](https://peterbouharb.github.io/stratum-releases/downloads/Cledion-Stratum-Setup.exe) |
| Windows MSI | [Cledion-Stratum.msi](https://peterbouharb.github.io/stratum-releases/downloads/Cledion-Stratum.msi) |
| Checksums | [SHA256SUMS.txt](https://peterbouharb.github.io/stratum-releases/downloads/SHA256SUMS.txt) |

macOS and Linux builds are not published yet.

## Verify Your Download

Every installer has an entry in `SHA256SUMS.txt`.

Windows PowerShell:

```powershell
Get-FileHash .\Cledion-Stratum-Setup.exe -Algorithm SHA256
```

If the hash does not match the entry in `SHA256SUMS.txt`, do not run the
installer. Re-download it from this repository only.

## Unsigned Pre-Release

Current builds are unsigned pre-release builds while code signing is being set
up. Windows SmartScreen may show "Windows protected your PC"; use **More info**
then **Run anyway** only if the file hash matches `SHA256SUMS.txt`.
