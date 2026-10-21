# Reson Homebrew tap

Install the published Apple Silicon build on macOS 14 or newer:

```sh
brew install --cask olivecarney/tap/reson
```

Reson is ad-hoc signed and is not Apple-notarized. macOS may require approval in **System Settings → Privacy & Security**. The cask does not bypass Gatekeeper. Uninstall preserves your library, playlists, preferences and original music files.

The cask pins the immutable v0.5.3 release DMG and its verified SHA-256. This release includes MP3 playback, native Settings, track and folder removal, and exclusion restoration. This tap installs the published binary; it does not build from main.

Source and installation documentation: [olivecarney/reson](https://github.com/olivecarney/reson).
