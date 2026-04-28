# AutoFlow

> Smart Windows automation for repetitive tasks — click, type, capture, and conditionally branch your way through any app or game.

[![Latest Release](https://img.shields.io/github/v/release/Rcorp-AutoFlow/AutoFlow-Release?label=download&color=brightgreen)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Rcorp-AutoFlow/AutoFlow-Release/total?color=blue)](../../releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey)](#system-requirements)

---

## ⬇️ Download

Grab the latest installer from the [**Releases**](../../releases/latest) page.

| File                      | Description                                                                   |
| ------------------------- | ----------------------------------------------------------------------------- |
| `AutoFlow_Setup_vX.Y.exe` | Windows installer — one-click install, creates Start Menu + desktop shortcuts |

After install, AutoFlow checks for new versions automatically — you don't have to come back here.

---

## ✨ Features

- **Visual step builder** — drag-and-drop click, type, wait, conditional, loop, and label/jump steps
- **Image search & click** — find templates on screen or inside a target window, click the match
- **OCR conditionals** — read text from a region and branch on it (offline + online engines)
- **Color & memory conditionals** — pixel sampling and persistent variables across runs
- **Background window mode** — drive an app while it's not focused; works while you use your PC
- **Global hotkeys** — start/stop scripts even when AutoFlow is minimized
- **Loop & jump** — repeat sections N times or jump to labels for free-form flow
- **Themed UI** — dark and light modes, persistent settings
- **Script library** — save, load, duplicate, and organize multiple scripts
- **Auto-updater** — new versions land in-app within an hour of release

---

## 🆓 Free vs ⭐ Pro

| Feature                | Free     | Pro       |
| ---------------------- | -------- | --------- |
| Steps per script       | 20 steps | Unlimited |
| Run time per script    | 30 min   | Unlimited |
| Background window mode | ✖        | ✔         |
| AI OCR (online)        | ✖        | ✔         |
| Updates & support      | ✔        | ✔         |

Subscription is hardware-bound (one PC per license). The Hardware ID is shown inside the app under **Subscription**.

---

## 💻 System Requirements

- Windows 10 (1809+) or Windows 11
- 64-bit CPU
- ~150 MB disk space
- Internet connection on first launch (license check) and for online OCR / updates

The installer bundles all runtime dependencies — no separate .NET install needed.

---

## 🔄 Auto-Update

AutoFlow checks this repository for new releases:

- **Once at startup**, ~3 seconds after launch
- **Every hour** while the app is running
- **Manually**, via right-click on the license badge → _Check for Update…_

When an update is found you'll see a dialog with the changelog and a **Download & Install** button. Click it and AutoFlow will:

1. Download the installer to your `%TEMP%` folder
2. Launch it
3. Close itself so the new version can replace the files cleanly

You can also choose **Skip This Version** to silence the popup until the next release.

---

## 🐛 Support / Bug Reports

Found a bug or have a feature request? Open an [issue](../../issues) — please include:

- AutoFlow version (shown next to the license badge)
- Windows version
- Steps to reproduce
- Screenshot of the log panel if relevant

---

## 📄 License

AutoFlow is proprietary commercial software. © Rcorp-AutoFlow. All rights reserved.
The installer and binaries hosted in this repository are distributed under the
end-user license agreement shipped with the installer.

---

<sub>This repository hosts release binaries only — the source code is not public.</sub>
