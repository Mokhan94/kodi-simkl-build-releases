# Kodi Simkl Build — Update Channel

Public update metadata and release assets for the Kodi Simkl Build.

This repository intentionally does **not** contain the complete Kodi profile,
private build source, credentials, viewing history, scraper/provider packages,
or bundled third-party add-ons. Its purpose is to provide an anonymously
readable update manifest and carefully scoped release assets to installed
copies of **Build Setup**.

## Channel

- Manifest: `manifest.json`
- Current build version: `0.1.6`
- Minimum Kodi version: 21

Release packages are ZIP files whose installable files are contained under a
`payload/` directory. Clients verify the SHA-256 value in the manifest before
installation and preserve account settings, databases, logs, profiles, Kodi
sources, and updater state.

For a fresh Kodi 21 installation, download `mokhan-build-installer-0.1.6.zip`
from the latest release, install it with Kodi's **Install from zip file** menu,
then open **Build Setup** and choose **Install Build**.

Kodi can also add the GitHub Pages address as a File Manager source:
`https://mokhan94.github.io/kodi-simkl-build-releases/`
