# Changelog

## v1.18.2 — 2026-06-28

- **Grey GodZilla** branding standardized across app title, window, and publisher metadata
- App renamed to `Grey GodZilla DayZ Mod Config Checker`
- Version badge in header matches DayZ Validator UI style

## v1.18.1 — 2026-06-28

- **AV hardening:** removed bundled MinGW DLLs (static-linked engine)
- Excluded unused numpy/psutil/etc. from PyInstaller bundle (smaller exe)
- Windows **version resource** + **asInvoker** manifest (no admin request)
- C++ engine installs to `%LOCALAPPDATA%\GreyGodZilla\DayZValidator\` (not temp `_MEIPASS`)
- Removed `CREATE_NO_WINDOW` subprocess flag (common malware heuristic)

## v1.18.0 — 2026-06-28

- Config.cpp panel — File / @Mod / Deep scope, Fix all .cpp, Diff button

## v1.17.0

- RPT import, server profiles, vanilla sync, globals presets, CE registry audit