# Reson Homebrew tap

Install the published Apple Silicon build on macOS 14 or newer:

```sh
brew install --cask olivecarney/tap/reson
```

Reson is ad-hoc signed and is not Apple-notarized. macOS may require approval in **System Settings → Privacy & Security**. The cask does not bypass Gatekeeper. Uninstall preserves your library, playlists, preferences and original music files.

The cask pins the immutable v0.5.2 release DMG and its verified SHA-256. That published binary predates the library-management and MP3 changes on main; those changes require a source build until a new release is explicitly published. This tap does not build from main.

Source and installation documentation: [olivecarney/reson](https://github.com/olivecarney/reson).
