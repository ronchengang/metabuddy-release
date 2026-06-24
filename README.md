# metabuddy-release

Public distribution point for MetaBuddy release assets. The source lives
in a separate private repo; this repo only holds GitHub Releases so the
auto-updater can fetch them without authentication.

Each release tagged `v<X.Y.Z>` contains:
- `MetaBuddy_<X.Y.Z>_x64-setup.exe` — Windows NSIS installer (signed with the Tauri update key)
- `latest.json` — manifest the Tauri updater plugin fetches from
  `https://github.com/ronchengang/metabuddy-release/releases/latest/download/latest.json`
