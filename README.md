<img src="https://raw.githubusercontent.com/jely2002/youtube-dl-gui/v2.0.0/renderer/img/icon.png" alt="logo" align="left" height="100"/>

# Open Video Downloader 简体中文版

**[English](./README_en.md)** | **中文**

![version badge](https://img.shields.io/github/v/release/XYL333FYQ/youtube-dl-gui?label=最新版本) ![GitHub](https://img.shields.io/github/license/XYL333FYQ/youtube-dl-gui) ![downloads](https://img.shields.io/github/downloads/XYL333FYQ/youtube-dl-gui/total)

基于 [jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui)（Open Video Downloader）的简体中文本地化版本。

原版是一个跨平台桌面应用，让你从 1800+ 个网站下载视频、音频、字幕和元数据。本 fork 在原版基础上新增了 **简体中文（zh-CN）** 界面支持。

> **致谢：** 本项目 fork 自 [jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui)，原作者 jely2002 及所有贡献者。本 fork 仅添加简体中文翻译，核心代码与原项目保持同步。

## 与原版的区别

- 新增 **简体中文（zh-CN）** 界面语言，可在设置中一键切换
- 保留原版全部功能和更新

## 功能特性

- **跨平台：** Windows、macOS、Linux 全支持
- **视频/音频下载：** 下载完整视频或仅提取音频
- **字幕和元数据：** 自动获取可用字幕和视频信息
- **画质选择：** 自选分辨率、帧率和输出格式（MP4/MKV）
- **播放列表：** 一次性下载整个播放列表
- **自定义输出：** 设置下载路径，使用预设或自定义模板命名文件
- **智能队列：** 自动平衡多任务下载，不卡电脑
- **身份验证：** 支持浏览器 Cookie、基本认证和视频密码
- **自动更新：** 应用和 yt-dlp 自动保持最新
- **深色/浅色模式：** 跟随系统主题
- **快捷键：** 用快捷键管理下载队列，通知推送进度

## 下载安装

前往 [Releases 页面](https://github.com/XYL333FYQ/youtube-dl-gui/releases) 下载最新版本。

| 你的电脑 | 下载文件 |
|---------|---------|
| **Windows** | `Open.Video.Downloader_x.x.x_x64-setup.exe` |
| **Mac（Intel）** | `Open.Video.Downloader_x.x.x_x64.dmg` |
| **Mac（Apple Silicon M1/M2/M3/M4）** | `Open.Video.Downloader_x.x.x_aarch64.dmg` |
| **Linux（x64）** | `Open.Video.Downloader_x.x.x_amd64.AppImage` |
| **Linux（aarch64）** | `Open.Video.Downloader_x.x.x_aarch64.AppImage` |
| **Linux Debian/Ubuntu（x64）** | `Open.Video.Downloader_x.x.x_amd64.deb` |
| **Linux Debian/Ubuntu（aarch64）** | `Open.Video.Downloader_x.x.x_arm64.deb` |
| **Linux Fedora/RHEL（x64）** | `Open.Video.Downloader_x.x.x-x_amd64.rpm` |
| **Linux Fedora/RHEL（aarch64）** | `Open.Video.Downloader_x.x.x-x_aarch64.rpm` |

### 切换中文

安装后打开应用 → **Settings（设置）** → **App（应用）** → **Language（语言）** → 选择 **中文（简体）**

## 技术栈

- 前端：Vue 3 + TypeScript
- 后端：Rust + [Tauri](https://tauri.app/)
- 下载引擎：[yt-dlp](https://github.com/yt-dlp/yt-dlp)

## 参与贡献

欢迎提交 Issue 和 PR！

开发环境需要 Node.js（v24+）和 Rust。

```bash
npm install
npm run tauri dev
```

## 许可证

本项目基于 [AGPL-3.0 许可证](./LICENSE) 开源。

### 免责声明

本应用按 AGPL-3.0 许可证（第 16 条）分发，维护者不对滥用行为承担责任。请遵守当地法律和平台服务条款。
