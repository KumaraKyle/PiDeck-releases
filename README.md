# PiDeck downloads

Get the Windows app from [the latest release](https://github.com/KumaraKyle/PiDeck-releases/releases/latest). This repository hosts app packages and public app information; the application source is maintained separately.

## Installation

Download `PiDeck-windows-x64.zip` and extract it into a writable folder. Run:

```powershell
powershell -ExecutionPolicy Bypass -File start.ps1
```

When upgrading a build older than v0.2.0, first stop the running app with `powershell -ExecutionPolicy Bypass -File start.ps1 -Stop`, then extract the new package and start it again. Those older builds need this one-time installation to gain the OTA updater.

## In-app updates

The notification bell contains release announcements, release notes and update preferences. Choose notification-only updates or automatic installation when an update is available. PiDeck briefly restarts during installation and retains a rollback backup.

## Google Calendar

Official v0.2.1 builds include the shared PiDeck desktop OAuth app configuration. Click **Sign in with Google** and authorize your own account; no developer credential setup is needed. Personal account tokens, calendar feed links and settings are never included in downloads. The Google app is in production, but Google's unverified-app warning and 100-user cap remain until Google verification is completed.

[App information](https://kumarakyle.github.io/PiDeck-releases/) · [Privacy policy](https://kumarakyle.github.io/PiDeck-releases/privacy.html)

Runtime scripts for receivers are included, but Windows app updates do not change a remote Linux machine or its operating system.
