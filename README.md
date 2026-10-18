# StatsAI Desktop downloads

This repository hosts the signed macOS builds of StatsAI Desktop and the feed
its built-in updater reads. It contains no source code.

- **Download:** the `.dmg` on the [latest release](https://github.com/StatsAIDev/statsai-desktop/releases/latest).
- **Homebrew:** `brew install --cask starkdmi/tap/statsai-desktop`
- **Updates:** the app checks `latest.json` on the latest release and installs
  updates signed with its updater key.

Every build is signed with a Developer ID certificate and notarized by Apple.

The command-line tool the app bundles is
[statsai](https://github.com/starkdmi/statsai), licensed under Apache-2.0.
The app's third-party notices are under Settings → About.
