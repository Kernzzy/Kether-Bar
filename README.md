<div align="center">

#  KetherBar

### A premium glass YASB theme inspired by macOS, crafted for a clean Windows experience.

![GitHub stars](https://img.shields.io/github/stars/CrazzyTude/Kether-Bar?style=for-the-badge)
![GitHub License](https://img.shields.io/github/license/CrazzyTude/Kether-Bar?style=for-the-badge)
![GitHub Downloads](https://img.shields.io/github/downloads/CrazzyTude/Kether-Bar/total?style=for-the-badge)

</div>

---

## ✨ Preview


<img width="1917" height="32" alt="image" src="https://github.com/user-attachments/assets/9372e298-c85a-4277-8828-d283b089db92" />

<!-- Add screenshots here -->



---

# Features

- 🍎 macOS Sonoma inspired design
- 🪟 Designed specifically for Windows 11
- 🌫️ Premium glass UI
- 🎨 SF Pro Rounded typography
- 📱 Modern Fluent iconography
- 🎵 Beautiful media controls
- 🌤️ Weather integration
- 🔋 Modern battery widget
- 📶 Wi-Fi & Bluetooth widgets
- 🎙️ Microphone controls
- 📅 Elegant calendar popup
- ⚡ Optimized for YASB
- 🎯 Clean and minimal layout

---

# Requirements

- Windows 11 (23H2 / 24H2 Recommended)
- Latest YASB
- SF Pro Rounded font
- JetBrainsMono Nerd Font (`JetBrainsMono NFP`), needed for the Wi-Fi, Bluetooth, battery and weather icons
- Segoe Fluent Icons (included with Windows 11)
- A free [WeatherAPI](https://www.weatherapi.com/) key for the weather widget
- Optional: VS Code (`code` on PATH), Windows Terminal (`wt`) for the app launcher buttons

---

# Installation

## 1. Install YASB

Follow the official installation guide:

https://yasb.dev

---

## 2. Install SF Pro Rounded

Download and install the SF Pro Rounded font.

Restart YASB afterwards.

---

## 3. Copy the configuration

Replace your existing

```
config.yaml
styles.css
```

with the files from this repository.

---

## 4. Personalize `config.yaml`

Open `config.yaml` and change these lines before restarting:

| Setting | Where | What to do |
|---------|-------|------------|
| `api_key` | `widgets.weather` | Paste your free WeatherAPI key |
| `location` | `widgets.weather` | Set your own location, e.g. `USA Los Angeles 90006` or just a city |
| Browser button | `widgets.apps` | Replace the Zen Browser path with your browser's `.exe` path |
| App buttons | `widgets.apps` | Edit or remove File / Code / Terminal / Notepad as you like |
| Komorebi | top of file | Only used if you run komorebi, otherwise ignored |

Without a key and location the weather widget will not load. Everything else works out of the box.

---

## 5. Restart YASB

Either

- Reload from the tray icon

or

- Restart the application.

---

# Customization

Every widget can be customized.

Examples include:

- Colors
- Blur
- Typography
- Icon packs
- Popup radius
- Hover effects
- Widget spacing

---

# Widgets

- Home
- Apps
- System Tray
- Weather
- Battery
- Bluetooth
- Wi-Fi
- Clock
- Media
- Microphone
- Quick Launch (ALT+SPACE)

---

# Roadmap

- [ ] Sonoma Media Popup
- [ ] Dynamic Accent Colors
- [ ] Better Calendar
- [ ] Control Center Style Popups
- [ ] Auto Location Weather
- [ ] Music Player Improvements
- [ ] More Themes
- [ ] OLED Mode

---

# Screenshots

| Desktop | Media Popup | Quick Launch Popup | Home Popup | Calendar Popup |
|---------|-------------|--------------------|------------|----------------|


<img width="1917" height="32" alt="image" src="https://github.com/user-attachments/assets/9372e298-c85a-4277-8828-d283b089db92" />
<img width="530" height="247" alt="image" src="https://github.com/user-attachments/assets/0879d363-ceb7-4caf-add2-d15e00d8b84a" />
<img width="932" height="565" alt="image" src="https://github.com/user-attachments/assets/9fdbdf4a-b974-4772-8068-0a88941d5237" />
<img width="547" height="660" alt="image" src="https://github.com/user-attachments/assets/ab747076-b447-435c-afcd-9a0d5e0f8d60" />
<img width="655" height="237" alt="image" src="https://github.com/user-attachments/assets/8a6a0deb-5323-4900-b148-21d377b59bbe" />

---

# Credits

Huge thanks to

- YASB
- Microsoft Fluent Icons
- Apple (Design Inspiration)

---

# Contributing

Pull requests, feature requests and issues are always welcome.

If you have ideas for improving KetherBar, feel free to open an issue or submit a PR.

---

# Support

If you enjoy KetherBar, consider giving the repository a ⭐.

It helps others discover the project.

---

<div align="center">

### Crafted with ❤️ for the Windows customization community.

**KetherBar**

Elegant • Minimal • Native

</div>
