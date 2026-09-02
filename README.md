# iNoon Updates

Shared Sparkle/NetSparkle appcast and signed release metadata for iNoon on macOS and Windows.

- Mac enclosures use `sparkle:os="macos"`.
- Windows enclosures use `sparkle:os="windows"`.
- Release assets live on GitHub Releases and `inoon.app`; large binaries are not committed here.
- Canonical release notes and immutable release records live under
  `releases/<platform>/<version>-<build>/`.

Publishers must preserve the other platform's entries and retain the newest three entries per
platform. A release must update from a clean, current `main` checkout and fail if `origin/main`
moves concurrently.
