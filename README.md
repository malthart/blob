# Blob

A native macOS app for managing [Apple's `container`](https://github.com/apple/container)
runtime — containers, images, networks, and volumes in a clean SwiftUI interface, with live
logs, stats, and an interactive shell.

> Early release (0.1.0). Apple silicon, macOS 14+.

## Install

1. Download the latest **`Blob.dmg`** from the
   [Releases page](https://github.com/malthart/blob/releases/latest).
2. Open it and drag **Blob** into **Applications**.
3. Blob is Developer ID-signed and notarized, so it opens normally. If macOS ever shows a
   Gatekeeper prompt, right-click the app → **Open** (or approve it under *System Settings →
   Privacy & Security*) and it'll remember the choice.

Blob is a front-end for Apple's `container` runtime, so you also need:

- An **Apple silicon** Mac on **macOS 14+**. (The `container` runtime itself targets macOS 26
  and runs degraded on macOS 15.)
- The [`container`](https://github.com/apple/container) CLI installed, with
  `container system start` run once. Blob detects a missing CLI or a stopped daemon and walks
  you through it.

## Features

- **Containers** — live list with status, a three-pane browser, start / stop / restart /
  delete, and a "Run Container" sheet.
- **Detail tabs** — Overview (live CPU & memory), **Logs** (streaming), **Stats**, and raw
  **Inspect** JSON.
- **Images, networks, volumes** — list, create / pull, inspect, remove.
- **Interactive `exec` terminal** — a real shell into a running container.
- **Daemon control** — one-click `container system start` when it's down.

## Updates

Blob updates itself via [Sparkle](https://sparkle-project.org): it checks for new releases
automatically, and you can check anytime from **Blob → Check for Updates…**. Every update is
cryptographically signed and verified before it installs.

## License

Copyright © 2026 Malthe Hartmann. All rights reserved. See [LICENSE](LICENSE).

Blob bundles third-party open-source components listed in
[THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).
