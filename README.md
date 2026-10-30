# ScanBridge Releases

Public downloads for **ScanBridge** — Android barcode scanner for Windows/Linux desktop over Wi-Fi/LAN.

The application source code is private. This repository contains only release binaries and
SHA-256 checksums.

## Download

Open [Releases](https://github.com/Vaskodegamo01/ScanBridge-Releases/releases/latest) and download:

| File | Platform |
|---|---|
| `ScanBridge-Setup-0.1.0.exe` | Windows 10/11 x64 |
| `ScanBridge-0.1.0-x86_64.AppImage` | Linux x86_64 (X11) |
| `ScanBridge-0.1.0-amd64.deb` | Debian/Ubuntu x86_64 (X11) |
| `ScanBridge-0.1.0-android.apk` | Android 9+ (sideload) |

`SHA256SUMS.txt` contains the checksums for all files in the release.

## Verify SHA-256

`SHA256SUMS.txt` uses the standard `sha256sum` format:

```bash
sha256sum -c SHA256SUMS.txt
```

On Windows PowerShell:

```powershell
Get-FileHash .\ScanBridge-Setup-0.1.0.exe -Algorithm SHA256
```

The APK is signed with the Android debug key for sideload testing; it is not a Google Play build.
The desktop builds are unsigned, so Windows SmartScreen may show a warning.

## Links

- Landing: https://landing.mydiskstation.ddns-ip.net (temporary domain)
- Security/contact: the contact address is published on the landing privacy page.
