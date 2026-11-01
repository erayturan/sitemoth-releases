# Changelog

<!-- release:1.3.0 -->
## 1.3.0 — 2026-11-01

macOS ARM64 · Windows x64

- Website (all platforms): Added actual interface previews, AI/MCP and report-workflow sections, a desktop illustration with a wallpaper and unobstructed app icon, client logos with balanced spacing and expanded FAQs in English and Turkish. Interface screenshots use example data.

- macOS ARM64 / Windows x64: Moved application updates to the top of Settings and local runtime details to a separate dialog.

- macOS ARM64 / Windows x64: Simplified AI connection setup with equal app selectors, one focused installation panel, and collapsible advanced options.

- macOS ARM64 / Windows x64: Consolidated AI domain permissions into one table with read, scan and note controls per domain and a single save action.

- macOS ARM64 / Windows x64: Added guided MCP setup for Cursor, VS Code / Copilot, Codex and Gemini CLI, plus connection guidance for ChatGPT and Gemini web.

- macOS ARM64 / Windows x64: AI scans now appear in a collapsible home-screen card alongside pinned and recent domains, with report access and scan cancellation directly in the card.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.3.0)
<!-- /release:1.3.0 -->

<!-- release:1.2.0 -->
## 1.2.0 — 2026-10-29

macOS ARM64 · Windows x64

### Added and fixed

- macOS ARM64 / Windows x64: DNS checks respect the scan timeout and skip domain-only record lookups for IP targets, preventing slow resolver responses from stalling a scan.

- macOS ARM64 / Windows x64: AI clients can start, track and cancel permitted scans for existing or new domains. Jobs persist across client disconnections and run independently of the app window.
- macOS ARM64 / Windows x64: AI evaluations can be saved as Markdown with revision history and exact references to earlier scans and notes; later sessions can retrieve that context. Reports can be exported locally as JSON, Markdown, HTML or CSV.

- macOS ARM64 / Windows x64: scan reports now include an AI notes panel with Markdown preview, revision history, source links and Markdown download; scanning and note-writing permissions are managed separately from read-only sharing.

- macOS ARM64 / Windows x64: AI clients can inspect sanitized module and finding details, search shared history, view trends and portfolio summaries, and compare findings with coverage limits. Saved reports are available as MCP resources with guided review prompts.

- macOS ARM64 / Windows x64: fixed the Claude Desktop extension entry point and stream relay for the built-in Node host; macOS users can select SiteMoth.app directly.

### Upgrade and distribution notes

- macOS ARM64 packages are Developer ID signed and notarized. The Windows x64 installer remains Authenticode-unsigned under the existing distribution policy; update packages are separately signature-verified.

- Existing read-only sharing stays read-only. Enable scan and note-writing permissions explicitly in AI connections; reconnect your AI client to discover the new tools.
- History gains a schema migration for notes. Back up exported domain history before testing this candidate; older app versions cannot open migrated history.
- AI client model access is provided by your chosen client. Public-only security scans use HTTP templates; unsupported or failed checks are not passing results.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.2.0)
<!-- /release:1.2.0 -->

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

