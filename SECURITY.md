# Security and release policy

Public release assets must never contain:

- Account tokens, API keys, refresh tokens, passwords, or usernames.
- Kodi or add-on settings files that can hold account credentials.
- Viewing, search, resume, cache, provider-account, or metadata databases.
- Logs, QR authentication images, profiles, sources, or device-specific paths.
- Complete third-party add-on or provider bundles unless redistribution has
  been reviewed and explicitly approved.

Each release asset must be generated from an allowlist, scanned, and matched to
the SHA-256 checksum published in `manifest.json`.

