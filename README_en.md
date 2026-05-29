<img src="https://raw.githubusercontent.com/jely2002/youtube-dl-gui/v2.0.0/renderer/img/icon.png" alt="logo" align="left" height="100"/>

# Open Video Downloader (Simplified Chinese Edition)

**English** | **[中文](./README.md)**

![version badge](https://img.shields.io/github/v/release/XYL333FYQ/youtube-dl-gui?label=latest) ![GitHub](https://img.shields.io/github/license/XYL333FYQ/youtube-dl-gui) ![downloads](https://img.shields.io/github/downloads/XYL333FYQ/youtube-dl-gui/total)

A Simplified Chinese localized fork of [jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui) (Open Video Downloader).

The original is a cross-platform desktop app for downloading videos, audio, subtitles and metadata from 1800+ websites. This fork adds **Simplified Chinese (zh-CN)** interface support on top of the original.

> **Credits:** Forked from [jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui) by jely2002 and contributors. This fork only adds Simplified Chinese translation and keeps core code in sync with upstream.

## What's Different

- Added **Simplified Chinese (zh-CN)** as a selectable UI language
- All original features and updates preserved

## Features

- **Cross-platform:** Windows, macOS and Linux
- **Audio or video downloads:** grab full videos or extract audio only
- **Subtitles and metadata:** automatically saves available captions and video info
- **Quality control:** choose resolution, frame rate, and output format (MP4/MKV)
- **Playlists:** download entire playlists at once
- **Custom output:** set download location and filename templates
- **Smart queueing:** balances multiple downloads automatically
- **Authentication:** supports browser cookies, basic auth and video passwords
- **Automatic updates:** both the app and yt-dlp stay up to date
- **Light and dark mode:** follows your system theme
- **Shortcuts:** manage downloads with keyboard shortcuts and notifications

## Download

Get the latest version from the [Releases page](https://github.com/XYL333FYQ/youtube-dl-gui/releases).

| Your Computer | Download |
|--------------|----------|
| **Windows** | `Open.Video.Downloader_x.x.x_x64-setup.exe` |
| **Mac (Intel)** | `Open.Video.Downloader_x.x.x_x64.dmg` |
| **Mac (Apple Silicon M1/M2/M3/M4)** | `Open.Video.Downloader_x.x.x_aarch64.dmg` |
| **Linux (x64)** | `Open.Video.Downloader_x.x.x_amd64.AppImage` |
| **Linux (aarch64)** | `Open.Video.Downloader_x.x.x_aarch64.AppImage` |
| **Linux Debian/Ubuntu (x64)** | `Open.Video.Downloader_x.x.x_amd64.deb` |
| **Linux Debian/Ubuntu (aarch64)** | `Open.Video.Downloader_x.x.x_arm64.deb` |
| **Linux Fedora/RHEL (x64)** | `Open.Video.Downloader_x.x.x-x_amd64.rpm` |
| **Linux Fedora/RHEL (aarch64)** | `Open.Video.Downloader_x.x.x-x_aarch64.rpm` |

### Switch to Chinese

After installing: **Settings** → **App** → **Language** → select **中文（简体）**

## Tech Stack

- Frontend: Vue 3 + TypeScript
- Backend: Rust + [Tauri](https://tauri.app/)
- Download engine: [yt-dlp](https://github.com/yt-dlp/yt-dlp)

## Contributing

Issues and PRs are welcome!

You'll need Node.js (v24+) and Rust.

```bash
npm install
npm run tauri dev
```

## License

Distributed under the [AGPL-3.0 license](./LICENSE).

### Disclaimer
The maintainers cannot be held liable for misuse of this application, as stated in the AGPL-3.0 license (section 16). Please comply with local laws and platform terms of service.
