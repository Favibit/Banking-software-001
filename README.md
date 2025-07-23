# Multi-Channel CI/CD Project

This project supports building Web, Android, Windows, and Desktop (Electron) apps with a single CI/CD pipeline using GitHub Actions.

## Folders

- `web/` — Web app source code
- `android/` — Android app
- `windows/` — Windows (MSIX/UWP) app
- `desktop/` — Desktop app (Electron)
- `shared/` — Shared code (optional)
- `.github/workflows/` — CI/CD pipelines

## How CI/CD Works

On every pull request, GitHub Actions will:
- Build and test the web app
- Build the Android APK
- Build the Windows MSIX
- Build the desktop installer

You can add your actual project code in each channel's folder as you develop.# Banking-software-001
