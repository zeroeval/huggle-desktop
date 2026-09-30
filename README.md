# huggle-desktop

Release assets for the Huggle desktop application.

Supported public assets:

- `Huggle-arm64.dmg` — signed and notarized macOS build for Apple Silicon.
- `Huggle-x64.dmg` — signed and notarized macOS build for Intel.
- `Huggle-Setup-x64.exe` — Authenticode-signed Windows x64 installer.
- `Huggle-<version>-full.nupkg` and `RELEASES` — Squirrel.Windows release data.
- `SHA256SUMS.txt` — Windows release checksums.

Website download routes resolve through the latest GitHub release, so every
published release must retain both macOS DMGs before Windows assets are added.
Builds are produced from
[zeroeval/huggle](https://github.com/zeroeval/huggle); this repository stores
release artifacts rather than application source.
