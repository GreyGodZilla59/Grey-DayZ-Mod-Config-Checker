# Grey DayZ Mod Config Checker

Portable all-in-one DayZ mod & mission config validator — single `.exe`, no installer.

![Grey Godzilla](greygodzilla_logo.png)

## Download

Download from [GitHub Releases](https://github.com/GreyGodZilla59/Grey-DayZ-Mod-Config-Checker/releases/latest).

**v1.18.0** — Config.cpp scan scope (File / @Mod / Deep), asset audit toggle, batch fix all `.cpp`, mod folder browse.

**SHA256:** `81F0A0B2A20CB83424AFB857B1AF58BAD7181D05259E953FF69F5E15CFF7468C`

## Quick start

1. Download and unzip anywhere
2. Run `Grey DayZ Mod Config Checker v1.18.0.exe`
3. **Config Checker** tab — drop a `config.cpp`, `@Mod` folder, mission path, or server folder
4. Press **Scan** (F5) or use **Mission Editor** for types/events/globals XML

Windows SmartScreen may warn on first run — normal for unsigned indie apps.

## Config Checker (page 1)

- Validate `config.cpp`, `meta.cpp`, mission XML/JSON, `serverDZ.cfg`
- **Config.cpp scope:** File (single file) · @Mod (meta + addons) · Deep (full tree)
- Asset path audit (`.p3d`, `.paa`, `.rvmat`)
- Auto-fix with diff preview · batch **Fix all .cpp**
- RPT log import (`Ctrl+Shift+R`) · config diff (`Ctrl+Shift+C`)
- Server profiles · CE audit · suppressions

## Mission Editor (page 2)

- Visual editors for types, events, economy, globals, spawnable, presets, gameplay JSON
- Cross-search `Ctrl+Shift+F` · mission diff · deploy · vanilla sync
- Globals presets · folder watch · CSV import/export for types

## Shortcuts

| Key | Action |
|-----|--------|
| F5 | Scan |
| Ctrl+Shift+R | Import RPT log |
| Ctrl+Shift+C | Config diff |
| Ctrl+P | Quick open mission file |
| Ctrl+Shift+F | Search all mission files |
| Ctrl+Shift+V | Vanilla sync |
| Ctrl+Shift+G | Globals presets |

## Requirements

- Windows 10/11 (64-bit)
- DayZ modding: local `config.cpp` or mission folder paths

## Feedback

Open a [GitHub Issue](https://github.com/GreyGodZilla59/Grey-DayZ-Mod-Config-Checker/issues) with:
- What you scanned (mod / mission / server path)
- Screenshot of findings if something looks wrong

## License

MIT — see LICENSE