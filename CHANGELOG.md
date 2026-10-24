# Changelog

<!-- release:1.1.0 -->
## 1.1.0 — 2026-10-24

macOS ARM64 · Windows x64

### New features

- macOS ARM64 / Windows x64: compatible AI clients can read saved reports for explicitly selected domains through an optional local, read-only MCP connection. Selecting domains grants access; clearing the last selection revokes it. Changes save immediately.
- macOS ARM64 / Windows x64: Settings offers a Claude Desktop connection button with its brand icon and permission guidance.
- macOS ARM64 / Windows x64: added manual update checks and optional daily automatic checks. Update packages are signature-verified; installation and restart require confirmation and wait for active scans and local AI sessions.

- Windows x64: fixed drive-letter paths when AI clients read local scan history.

### Interface improvements

- macOS ARM64 / Windows x64: added locally bundled Manrope with its license; aligned the transparent opening icon and wordmark, and moved AI settings above runtime information.
- Website: English uses root URLs and Turkish uses `/tr`; legal links, sitemap and metadata follow the same language structure. Download links track each platform’s published release separately.

### Upgrade and distribution

- Install this first updater-enabled version manually. Future updates will be offered through Settings after a newer stable release is published.
- AI access and automatic update checks are off by default. Update checks connect to GitHub without sending reports or domain lists. Review the updated privacy notice.
- macOS uses Developer ID signing and notarization. Windows remains unsigned with respect to Authenticode; update-package signatures are verified separately.
- Browser-based checks require an installed Chrome or Edge browser.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.1.0)
<!-- /release:1.1.0 -->

<!-- release:1.0.3 -->
## 1.0.3 — 2026-10-24

macOS ARM64 · Windows x64

### Fixed

- New Windows installations use the 64-bit Program Files directory. Existing installations may keep their previous installation directory.

### Distribution notes

- Windows is distributed unsigned. macOS distribution uses Developer ID signing and notarization.
- Browser-based checks require an installed Chrome or Edge browser.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.0.3)
<!-- /release:1.0.3 -->

