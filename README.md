# ScanBridge Releases

[English](#english) · [Русский](#русский)

---

## English

Public downloads for **ScanBridge** — an Android barcode scanner that sends scans to a
Windows/Linux desktop over Wi-Fi/LAN.

The application source code is private. This repository contains only release binaries and
SHA-256 checksums.

### Download

Open [Releases](https://github.com/Vaskodegamo01/ScanBridge-Releases/releases/latest) and download:

| File | Platform |
|---|---|
| `ScanBridge-Setup-0.1.0.exe` | Windows 10/11 x64 |
| `ScanBridge-0.1.0-x86_64.AppImage` | Linux x86_64 (X11) |
| `ScanBridge-0.1.0-amd64.deb` | Debian/Ubuntu x86_64 (X11) |
| `ScanBridge-0.1.0-android.apk` | Android 9+ (sideload) |

`SHA256SUMS.txt` contains the checksums for all files in the release.

### Verify SHA-256

`SHA256SUMS.txt` uses the standard `sha256sum` format:

```bash
sha256sum -c SHA256SUMS.txt
```

On Windows PowerShell:

```powershell
Get-FileHash .\ScanBridge-Setup-0.1.0.exe -Algorithm SHA256
```

### Notes

- The APK is signed with the Android debug key for sideload testing; it is not a Google Play build.
- The desktop builds are unsigned, so Windows SmartScreen may show a warning.
- Linux support requires an X11 session; Wayland is not supported.
- The application works locally over Wi-Fi/LAN. There is no cloud mode, account, or COM port yet.
- The “ScanBridge” name is temporary.

### Links

- Landing: <https://landing.mydiskstation.ddns-ip.net> (temporary domain)
- Contact details are published on the landing privacy page.

---

## Русский

Публичные сборки **ScanBridge** — Android-сканера, который отправляет штрихкоды на компьютер
с Windows/Linux по Wi-Fi/LAN.

Исходный код приложения приватный. В этом репозитории только бинарники релизов и контрольные
суммы SHA-256.

### Скачивание

Откройте [Releases](https://github.com/Vaskodegamo01/ScanBridge-Releases/releases/latest) и скачайте:

| Файл | Платформа |
|---|---|
| `ScanBridge-Setup-0.1.0.exe` | Windows 10/11 x64 |
| `ScanBridge-0.1.0-x86_64.AppImage` | Linux x86_64 (X11) |
| `ScanBridge-0.1.0-amd64.deb` | Debian/Ubuntu x86_64 (X11) |
| `ScanBridge-0.1.0-android.apk` | Android 9+ (sideload) |

`SHA256SUMS.txt` содержит контрольные суммы всех файлов релиза.

### Проверка SHA-256

`SHA256SUMS.txt` использует стандартный формат `sha256sum`:

```bash
sha256sum -c SHA256SUMS.txt
```

В Windows PowerShell:

```powershell
Get-FileHash .\ScanBridge-Setup-0.1.0.exe -Algorithm SHA256
```

### Примечания

- APK подписан отладочным ключом Android для установки вручную; это не сборка Google Play.
- Desktop-сборки не подписаны, поэтому Windows SmartScreen может показать предупреждение.
- Для Linux нужна сессия X11; Wayland не поддерживается.
- Приложение работает локально по Wi-Fi/LAN. Облачного режима, аккаунта и COM-порта пока нет.
- Название «ScanBridge» временное.

### Ссылки

- Лендинг: <https://landing.mydiskstation.ddns-ip.net> (временный домен)
- Контакты опубликованы на странице приватности лендинга.
