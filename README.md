# 🔋 Battery Insight

> A modern, Deepin 25-inspired battery monitor for Linux.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![GTK 3.0](https://img.shields.io/badge/GTK-3.0-green.svg)](https://www.gtk.org/)
[![Deepin](https://img.shields.io/badge/Deepin-25-blue.svg)](https://www.deepin.org/)

**Battery Insight** reads directly from `/sys/class/power_supply` to display accurate, real-time information about your battery — no external dependency, fully offline, privacy-friendly.

![Battery Insight screenshot](docs/screenshot-light.png)

---

## ✨ Features

- 🔋 **Battery level gauge** with smooth adaptive gradient (red / orange / blue)
- 📋 **General information** — manufacturer, model, serial number, technology
- ⚡ **Charge status** — cycle count, current charge, state, remaining time
- 📈 **Energy indicators** — design capacity, full capacity, remaining energy, voltage
- ❤️ **Health assessment** with 5 severity levels and detailed recommendations
- 🔀 **Multi-battery support** — dedicated tabs per battery (tested on ThinkPad)
- 🌗 **Automatic light/dark theme** following your Deepin settings
- 🌐 **8 languages** — French, English, German, Spanish, Japanese, Portuguese, Thai, Chinese
- 🎨 **Deepin 25-inspired design** with subtle animations
- 🔒 **Fully offline, no telemetry, no ads**

---

## 📸 Screenshots

| Light mode | Dark mode |
|:---:|:---:|
| ![Light](docs/screenshot-light.png) | ![Dark](docs/screenshot-dark.png) |

| Multi-battery (ThinkPad) | No battery (desktop) |
|:---:|:---:|
| ![Dual](docs/screenshot-dual.png) | ![No battery](docs/screenshot-none.png) |

---

## 🚀 Installation

### From the Deepin Store

*Coming soon.*


**Dependencies:**

- Python 3.8+
- PyGObject (`python3-gi`)
- GTK 3.0
- Cairo for Python (`python3-gi-cairo`)
- Pango

On Debian / Ubuntu / Deepin:

```bash
sudo apt install python3 python3-gi python3-gi-cairo \
                 gir1.2-gtk-3.0 gir1.2-pango-1.0 gir1.2-gdkpixbuf-2.0
