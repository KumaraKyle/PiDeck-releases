# PiDeck downloads

Download the latest Windows app from [Releases](https://github.com/KumaraKyle/PiDeck-releases/releases/latest). This repository hosts app packages; the application source is maintained separately.

## First installation or upgrading an older build

Download `PiDeck-windows-x64.zip`, extract it into a writable folder, and run:

```powershell
powershell -ExecutionPolicy Bypass -File start.ps1
```

Use the app setup screen for the display and receiver connection. Each user keeps their own configuration and calendar/music credentials. No user credentials are included in these downloads.

## Updates

Version 0.2.0 introduces in-app updates. Existing older installations need this package once before they can receive OTA updates. The notification bell contains update notices, release notes, and update preferences. Choose notification-only updates or automatic installation when available. PiDeck briefly restarts during installation and retains a rollback backup.

Packages include receiver scripts, but Windows app updates do not alter a remote Linux machine or its operating system.
