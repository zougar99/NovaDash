# ⚡ NovaDash - Advanced Desktop Widget Engine

A modern, beautiful desktop widget engine for Windows - a powerful alternative to Rainmeter.

![NovaDash](https://img.shields.io/badge/version-1.0.0-blue) ![Electron](https://img.shields.io/badge/electron-42-green) ![Widgets](https://img.shields.io/badge/widgets-53-purple)

## Features — 53 Widgets

### 🖥️ System Monitoring (8)
- **CPU Monitor** — Real-time usage, temperature, speed, history chart
- **CPU Per-Core** — Individual usage for every core with live bars
- **RAM Monitor** — Memory usage with breakdown and live chart
- **Disk Monitor** — Storage space for all drives with progress bars
- **Network Monitor** — Download/Upload speed with live graph
- **Battery** — Battery level, charging status, time remaining
- **Performance Graph** — Combined CPU & RAM live canvas chart
- **System Info** — Detailed system, CPU, RAM, and GPU information

### 🌐 Network & Connectivity (4)
- **IP Info** — Public IP, ISP, location, country, local IPs
- **WiFi Info** — Signal strength, SSID, channel, security
- **Speed Test** — Test internet download speed and latency
- **Task Killer** — View running processes by CPU/RAM and kill them

### 🕐 Time & Weather (5)
- **Clock** — Beautiful digital clock with date display
- **Weather** — Current weather, 3-day forecast, humidity, wind, UV
- **Calendar** — Interactive monthly calendar with navigation
- **Stopwatch & Timer** — Precision stopwatch and countdown timer
- **Countdown** — Countdown to events, holidays, and deadlines

### 🚀 Productivity (8)
- **Notes** — Sticky notes with color themes, saved locally
- **Todo List** — Task manager with priorities, checkboxes, sorting
- **App Launcher** — Quick launch 12+ system apps with search
- **Quick Commands** — 10+ system commands at your fingertips
- **Search Bar** — Multi-engine: Google, Bing, YouTube, GitHub, DDG
- **Quick Access Folders** — One-click access to 12 important folders
- **Clipboard Manager** — Auto-tracks clipboard history, click to copy
- **Recycle Bin** — Quick view item count and empty recycle bin

### 🔧 Tools & Utilities (7)
- **Password Generator** — Secure passwords with strength meter & copy
- **Currency Converter** — Live exchange rates for 17+ currencies
- **Unit Converter** — Length, weight, temp, speed, data, time
- **Color Picker** — Pick with RGB sliders, HEX/RGB/HSL output
- **Screenshot** — Full screen, snip area, and active window capture
- **Keyboard Shortcuts** — 40+ Windows & browser shortcuts reference
- **Motivational Quotes** — 20+ inspiring quotes that auto-rotate

### 🎵 Media & Entertainment (2)
- **Now Playing** — Media playback controls with play/pause/skip
- **Volume Mixer** — Quick volume control with presets and mute

### 🛠️ Advanced Tools (19)
- **Pomodoro Timer** — Focus timer with work/break intervals
- **World Clock** — Multiple timezone clocks with day/night indicator
- **Hash Generator** — MD5, SHA-1, SHA-256, SHA-512, CRC32
- **Translator** — Quick text translation between 17+ languages
- **System Uptime** — Live uptime counter with boot time info
- **Epoch & Time** — Unix seconds/ms, ISO, local timestamp tools
- **Regex Tester** — Pattern + flags, matches with indices & copy
- **Contrast (WCAG)** — Foreground/background luminance & AA/AAA
- **Algorithm Lab** — Base64/URI, GCD/LCM, primes, Luhn, JSON fmt
- **UUID Generator** — RFC 4122 v4 IDs with copy and history
- **JSON Formatter** — Format, validate & minify JSON instantly
- **Text Tools** — Case converter, char/word counter & statistics
- **Crypto Tracker** — Live BTC, ETH, SOL, XRP, ADA prices
- **Base64 Tool** — Encode & decode Base64 text with copy
- **Markdown Preview** — Write Markdown with live preview toggle
- **Date Calculator** — Days between dates, add/subtract days
- **ASCII Art** — Turn text into ASCII art with multiple fonts
- **Port Scanner** — Scan 16 common ports on any host/IP
- **BMI Calculator** — Calculate BMI with category and visual bar

## Quick Start

```bash
# Install dependencies
npm install

# Run the application
npm start
```

## Design
- **Glassmorphism UI** - Transparent, blurred widget backgrounds
- **Draggable & Resizable** - All widgets can be moved and resized
- **Pin & Lock** - Pin widgets on top or lock their position
- **Widget Dashboard** - Beautiful gallery to browse and manage widgets
- **System Tray** - Runs silently in the background
- **Auto-save** - Widget positions and settings are saved automatically

## Tech Stack
- **Electron** - Desktop application framework
- **systeminformation** - System data collection
- **JSON file store** - Persistent settings storage (replaces electron-store)

## Building

```bash
# Package for distribution
npm run build
```
