# Cledion Stratum Downloads

Public download home for **Cledion Stratum**, the desktop app for data-center
monitoring. The application source is developed privately; this repository
hosts only the download page, installers, and checksums.

Download page:
<https://peterbouharb.github.io/stratum-releases/>

Current Free v0.1.2 downloads:

| Platform | Download |
| --- | --- |
| Windows installer (recommended) | [Cledion-Stratum-Free-Setup.exe](https://github.com/peterbouharb/stratum-releases/releases/download/free-v0.1.2/Cledion-Stratum-Free-Setup.exe) |
| Windows MSI | [Cledion-Stratum-Free.msi](https://github.com/peterbouharb/stratum-releases/releases/download/free-v0.1.2/Cledion-Stratum-Free.msi) |
| Debian / Ubuntu | [Cledion-Stratum-Free.deb](https://github.com/peterbouharb/stratum-releases/releases/download/free-v0.1.2/Cledion-Stratum-Free.deb) |
| Linux AppImage | [Cledion-Stratum-Free.AppImage](https://github.com/peterbouharb/stratum-releases/releases/download/free-v0.1.2/Cledion-Stratum-Free.AppImage) |
| SHA-256 checksums | [SHA256SUMS.txt](https://github.com/peterbouharb/stratum-releases/releases/download/free-v0.1.2/SHA256SUMS.txt) |

macOS is not published yet.

## Verify Your Download

Every installer has an entry in `SHA256SUMS.txt`.

Windows PowerShell:

```powershell
Get-FileHash .\Cledion-Stratum-Free-Setup.exe -Algorithm SHA256
```

If the hash does not match the entry in `SHA256SUMS.txt`, do not run the
installer. Re-download it from this repository only.

## Signing

The Windows `.exe`, `.msi`, and embedded application executables are
Authenticode-signed by **Cledion, Inc.** through Azure Trusted Signing.
Linux packages follow the platform norm and are not code-signed; verify them
with `SHA256SUMS.txt`.
