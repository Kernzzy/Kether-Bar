<div align="center">

# KETHER BAR

**A glass status bar for Windows 11, inspired by macOS Sonoma.**

Minimal. Translucent. Native.

<br>

![Stars](https://img.shields.io/github/stars/Kernzzy/Kether-Bar?style=flat-square&color=white&labelColor=1c1c1e)
![Platform](https://img.shields.io/badge/Windows_11-YASB-white?style=flat-square&labelColor=1c1c1e)

<br>

<img width="1917" height="32" alt="KetherBar" src="https://github.com/user-attachments/assets/9372e298-c85a-4277-8828-d283b089db92" />

<br>

[Features](#features) · [Install](#install) · [Configure](#configure) · [Gallery](#gallery)

</div>

---

## Features

- **Glass material.** Blurred, translucent bar and popups that share one consistent look.
- **Sonoma typography.** SF Pro Rounded throughout, with Fluent and Nerd Font icons.
- **Compact media control.** One button on the bar; the full player lives in a popup.
- **Quick Launch.** Search apps, files and the web with `Alt + Space`.
- **Everyday widgets.** Home menu, app launcher, system tray, weather, battery, Wi-Fi, Bluetooth, microphone and clock with calendar.

---

## Requirements

| | |
|---|---|
| OS | Windows 11 |
| Bar | Latest [YASB](https://yasb.dev) |
| Fonts | SF Pro Rounded and JetBrainsMono Nerd Font (`JetBrainsMono NFP`) |
| Icons | Segoe Fluent Icons (included with Windows 11) |
| Weather | A free [WeatherAPI](https://www.weatherapi.com/) key |

---

## Install

1. Install YASB and the fonts above.
2. Replace your YASB `config.yaml` and `styles.css` with the files from this repository.
3. Personalize the config (see below).
4. Restart YASB from the tray icon.

---

## Configure

Open `config.yaml` and set these before restarting:

| Setting | Section | Action |
|---|---|---|
| `api_key` | `widgets.weather` | Paste your WeatherAPI key |
| `location` | `widgets.weather` | Set your location, e.g. `USA Los Angeles 90006` or just a city |
| Browser button | `widgets.apps` | Point it to your browser's `.exe` |
| App buttons | `widgets.apps` | Edit or remove File, Code, Terminal and Notepad |

Without a key and location the weather widget stays empty. Everything else works out of the box. Komorebi settings at the top of the file are ignored unless you use komorebi.

---

## Gallery

**Media**

<img width="530" height="247" alt="Media popup" src="https://github.com/user-attachments/assets/0879d363-ceb7-4caf-add2-d15e00d8b84a" />

**Quick Launch**

<img width="932" height="565" alt="Quick Launch popup" src="https://github.com/user-attachments/assets/9fdbdf4a-b974-4772-8068-0a88941d5237" />

**Home**

<img width="547" height="660" alt="Home popup" src="https://github.com/user-attachments/assets/ab747076-b447-435c-afcd-9a0d5e0f8d60" />

**Calendar**

<img width="655" height="237" alt="Calendar popup" src="https://github.com/user-attachments/assets/8a6a0deb-5323-4900-b148-21d377b59bbe" />

---

<div align="center">

Designed & built by **Kenzzy**

Built on [YASB](https://yasb.dev) · Microsoft Fluent Icons · Design inspired by Apple

</div>
