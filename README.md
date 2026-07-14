# digitallife（数字人生）

**English** | [简体中文](README.zh.md)

> A native macOS activity monitor — **all your data stays on your own Mac.**

digitallife quietly records what happens on your Mac day to day: which apps you use and for how long, network and battery/power usage, file changes, apps installed and removed… then presents it all through a polished native menu-bar app as clear daily / weekly / monthly reports. No cloud, no account, nothing uploaded.

---

## ✨ What you can see

- **App usage time** and daily rankings (with app icons)
- **Battery & power trends**, per-app energy ranking (optional)
- **Network traffic** per app
- **File activity**: created / deleted / modified — directory, type, and originating app
- **CPU / memory** top list
- **Window titles & idle time**, menu-bar / background-resident apps
- **App install / uninstall** history
- **Disk space scan** (locating large folders / files) and **junk cleanup**
- **Daily / weekly / monthly reports**, screen time vs. the previous period
- Data can be cleared by day / category, with **JSON / CSV export**

---

## 💻 Requirements

- **macOS 13 (Ventura) or later**
- **Apple Silicon** (M-series chip)

---

## ⬇️ Download & Install

1. Download the latest `DigitalLife-<version>.dmg` from **[Releases](https://github.com/Link-X/digitallife-releases/releases/latest)**
2. Open the DMG and **drag the app (数字人生) into Applications**
3. **Double-click to launch** — the app is **notarized by Apple**, so there's no "damaged" / "unverified developer" block and no need to "right-click → Open"
4. On first run, open **权限设置…** (Permissions) from the menu bar and grant the system permissions as guided

### Permissions (grant as needed; if one is missing, only that feature degrades — nothing else breaks)

| Permission | Purpose |
|------------|---------|
| Full Disk Access | Browser history, etc. |
| Accessibility | Identify the foreground app |
| Screen Recording | Read window titles (**no screenshots**) |
| Automation (System Events) | Foreground app / window |

---

## 🔒 Privacy

This is what digitallife cares about most:

- **100% of your data stays local**, written to a database on your own Mac, with **no network reporting** whatsoever
- **The only network request** happens when **you manually click "Check for Updates"** — it fetches just a version number and sends none of your data; otherwise the app is fully offline
- For stronger protection, you can **enable database encryption** in Settings (the key is stored in the system Keychain)

---

## 🔄 Check for Updates

App menu **关于数字人生 (About) → 检查更新 (Check for Updates)**: click once manually; if a newer version exists, you'll be prompted with a download link. No background polling, no automatic downloads.

---

## 📄 License

**Proprietary software · All rights reserved** — Copyright © 2026 许道斌 (Daobin Xu). All Rights Reserved.

- **Source code is closed**: except for the author, no use, copying, modification, reverse-engineering, or distribution of the source code is permitted without prior written authorization; **"visible" does not mean "usable."**
- **Official app free for non-commercial use**: individuals (study / research / hobby), non-profit organizations, educational & research institutions, and government bodies may **use free of charge** the officially released, unmodified, signed & notarized app from this repository.
- **Official channel, personal use only**: download from this repository's [Releases](https://github.com/Link-X/digitallife-releases/releases/latest) for your own use; **redistribution, forwarding, copying, modification, and reverse-engineering are not permitted.**
- **Commercial use requires authorization**: any commercial use — **including use by a for-profit organization (company / enterprise) in the course of business, even solely internal employee use** — requires prior written authorization.

> "Non-commercial" means use not primarily intended for commercial advantage or monetary compensation: personal use, non-profits, educational & research institutions, and government bodies within their non-profit / public functions.

For licensing inquiries, contact **许道斌 (Daobin Xu)** (<15555537368xu@gmail.com>). Full bilingual terms are in [LICENSE](LICENSE).
