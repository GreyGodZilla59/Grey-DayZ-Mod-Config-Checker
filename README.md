# Grey GodZilla DayZ Mod Config Checker

Portable all-in-one DayZ mod & mission config validator — single `.exe`, no installer.

![Grey GodZilla](greygodzilla_logo.png)

## Download

Download from [GitHub Releases](https://github.com/GreyGodZilla59/Grey-DayZ-Mod-Config-Checker/releases/latest).

**v1.18.2** — Grey GodZilla branding standardized + version badge in header.

## Quick start

1. Download and unzip anywhere
2. Run `Grey GodZilla DayZ Mod Config Checker v1.18.2.exe`
3. **Config Checker** tab — drop a `config.cpp`, `@Mod` folder, mission path, or server folder
4. Press **Scan** (F5)

Windows SmartScreen may warn on first run — normal for unsigned indie apps. See **Antivirus** below.

## Antivirus / false positives

This app is **unsigned** (no code-signing certificate yet). Some scanners flag PyInstaller portable apps.

- Re-scan on [VirusTotal](https://www.virustotal.com) after each release
- Report false positives: [Microsoft Defender submission](https://www.microsoft.com/en-us/wdsi/filesubmission)
- v1.18.1+ removes bundled MinGW DLLs, drops unused heavy Python libs, embeds proper file version info, and runs the C++ engine from `%LOCALAPPDATA%\GreyGodZilla\DayZValidator\` instead of a temp folder

## Config Checker

- **Config.cpp scope:** File · @Mod · Deep
- Asset path audit · auto-fix · batch fix all `.cpp`
- RPT import · server profiles · CE audit

## Mission Editor

- Types, events, economy, globals, spawnable, presets, gameplay JSON
- Cross-search · deploy · vanilla sync · globals presets

## License

MIT — see LICENSE