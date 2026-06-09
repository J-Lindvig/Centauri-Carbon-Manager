# Centauri Carbon Manager 🚀

A lightning-fast, zero-dependency, local Web UI replacement for the Elegoo Centauri Carbon 3D printer. Built strictly on **KISS** (Keep It Simple, Stupid) and **DRY** (Don't Repeat Yourself) principles.

Created by **Broby IT**.

## 📌 Overview
The Centauri Carbon Manager connects directly to your printer via your Local Area Network (LAN) using the SDCP (Smart Device Control Protocol) over WebSockets. It gives you instant, local access to your print files, history logs, live camera stream, and timelapse videos.

**Compatibility:** This application is specifically designed to work exclusively with the Elegoo Centauri Carbon (CC1) running either the Original Firmware or OpenCentauri.

Because it is built as a single, standalone HTML file with Vanilla JavaScript, there are no dependencies to install and no local servers to run.

## ✨ Features
* **Lightning Fast:** Instant WebSocket communication directly with the printer's motherboard.
* **File Management:** List, sort, filter, and batch-delete local GCODE files.
* **Smart Print History:** View past print jobs complete with print durations and thumbnail images.
* **Cross-Tab Thumbnails:** The manager maps history thumbnails to your local files automatically.
* **Live Camera Stream:** Integrated modal for viewing the printer's live MJPEG stream.
* **Timelapse Downloads:** Directly unlock and download MP4 timelapse videos from the printer.
* **Built-in SDCP API Reference:** Includes a reverse-engineered manual of the WebSocket commands.
* **Multi-Language & Theming:** Supports 6 languages (EN, DA, DE, FR, ES, IT) and Dark/Light mode.

## 🛠️ Usage
1. Download the [`centauri-manager.html`](https://github.com/J-Lindvig/Centauri-Carbon-Manager/releases/latest/download/centauri-manager.html) file.
2. Open it in any modern web browser.
3. Enter your printer's IP address and click **Connect**.

*Pro-tip:* You can bookmark the URL with your IP included to auto-connect in the future:
`file:///path/to/centauri-manager.html?ip=192.168.0.17`

## 🧠 Architecture
This application is driven by a centralized `State` object to handle asynchronous WebSocket responses seamlessly. UI elements are rendered dynamically using `DocumentFragment` for maximum performance, and native browser alerts have been replaced with a custom async/await modal system.
