# DynamicSub for Mac

Captions, text-behind, lighting and sound for talking-head videos — running on your own laptop.
Hinglish, हिन्दी and English. No credits, no watermark.

Web version: https://dynamicsub.reyansh7447.workers.dev

## Install (easiest)

Open **Terminal** (⌘ Space, type "Terminal") and paste:

```sh
curl -fsSL https://dynamicsub.reyansh7447.workers.dev/install.sh | sh
```

It downloads the latest release into Applications and opens it. No warnings. [Read the script](https://dynamicsub.reyansh7447.workers.dev/install.sh) before you run it if you like; it only touches `DynamicSub.app`.

## Or download the .dmg

**[Download for Mac (Apple silicon)](https://github.com/Reyansh17/dynamicsub-releases/releases/latest/download/DynamicSub-mac-arm64.dmg)**

1. Open the `.dmg` and drag **DynamicSub** into **Applications**.
2. Open DynamicSub. macOS says it can't verify the app — click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to "DynamicSub was blocked". Enter your Mac password.

You only do this once. The app is signed by us but not yet notarized by Apple, which is why macOS asks.

## Requirements

- A Mac with Apple silicon (M1 or newer), macOS 12 or later
- About 400 MB of free space

This repository only hosts the installers; there is no source code here.
