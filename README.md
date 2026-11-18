# gallery-dl Nightly Builds

Automated [gallery-dl](https://codeberg.org/mikf/gallery-dl)
builds using [PyInstaller](https://github.com/pyinstaller/pyinstaller)\
Built from [master](https://codeberg.org/mikf/gallery-dl/src/branch/master),
released daily at 00:00 UTC

Included optional dependencies:
- `yt-dlp[extra]`
- `PySocks`
- `PyYAML`
- `truststore`
- `SecretStorage` (for Linux builds)

GitHub Actions workflow: [workflows/executables.yml](https://github.com/mikf/gallery-dl/blob/master/.github/workflows/executables.yml)
