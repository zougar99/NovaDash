# ⚡ NovaDash - Advanced Desktop Widget Engine

A modern, beautiful desktop widget engine for Windows - a powerful alternative to Rainmeter.

![NovaDash](https://img.shields.io/badge/version-1.0.0-blue) ![Electron](https://img.shields.io/badge/electron-28-green) ![Widgets](https://img.shields.io/badge/widgets-53-purple)

## Features

### 🖥️ System Monitoring (7 widgets)
- **CPU Monitor** - Real-time usage, temperature, speed, history chart
- **RAM Monitor** - Memory usage with breakdown and live chart
- **Disk Monitor** - Storage space for all drives with progress bars
- **Network Monitor** - Download/Upload speed with live network graph
- **Battery** - Battery level, charging status, time remaining
- **Performance Graph** - Combined CPU & RAM live performance graph
- **System Info** - Detailed system, CPU, RAM, and GPU information

### 🕐 Time & Weather (4 widgets)
- **Clock** - Beautiful digital clock with date display
- **Weather** - Current weather, 3-day forecast, humidity, wind
- **Calendar** - Interactive monthly calendar with navigation
- **Stopwatch & Timer** - Precision stopwatch and countdown timer

### 🚀 Productivity (6 widgets)
- **Notes** - Sticky notes with color themes, saved locally
- **App Launcher** - Quick launch 12+ system apps with search
- **Quick Commands** - 10+ system commands at your fingertips
- **Search Bar** - Multi-engine: Google, Bing, YouTube, GitHub, DuckDuckGo
- **Quick Access Folders** - One-click access to 12 important folders
- **Recycle Bin** - Quick view and empty recycle bin

### 🎵 Media & More (3 widgets)
- **Now Playing** - Media playback controls
- **Volume Mixer** - Quick volume control with presets
- **Motivational Quotes** - 20+ inspiring quotes that auto-rotate

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
- **electron-store** - Persistent settings storage

## Building

```bash
# Package for distribution
npm run build
```
