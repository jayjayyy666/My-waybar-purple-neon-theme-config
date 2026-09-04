# Waybar Neon Bubble Config

A clean, modern, and unified **Waybar** configuration designed for **Hyprland** (tested on CachyOS). It features a distinct three-bubble layout, dark backgrounds, and vibrant neon-fuchsia aesthetics.

## 🎨 Features

- **Bubble Layout**: Separated left, center, and right modules styled as floating dark glass bubbles.
- **Neon Fuchsia Theme**: Unified custom CSS with glowing accents (`#e879f9`) and dynamic status colors for battery, charging, and alerts.
- **English Localization**: All labels, status indicators, and hover tooltips are fully translated to English.
- **Interactive Tooltips**: Detailed hover info for weather, network, memory, CPU, temperature, and brightness.
- **Smart Wi-Fi & Battery**: Clean icon representation for network status and toggleable alternative time display for battery life.

## 📂 File Structure

```text
~/.config/waybar/
├── config.jsonc         # Module layout and behavior configuration
├── style.css            # Neon fuchsia styling and bubble aesthetics
└── scripts/
    └── waybar-wttr.py   # Python script fetching live weather data and forecasts from wttr.in
