# Centauri Carbon Manager v2.0

A fast, lightweight, and local file management tool designed for Elegoo (and Centauri) 3D printers.

## Overview
As a 3D printing enthusiast, I encountered frustrations with the native printer interface, such as lag, slow file management, and cloud dependencies. **Centauri Carbon Manager** is my solution – a clean, local-first dashboard.

It is built following the **KISS** (Keep It Simple, Stupid) and **DRY** (Don't Repeat Yourself) principles. It requires no installation, no external CSS/JS libraries, and no complex backend; simply open the file in your browser and connect to your printer on your local LAN.

<img width="777" height="963" alt="image" src="https://github.com/user-attachments/assets/c0b6424c-aac4-49ef-a707-0b20538c5b2f" />


## Key Features
* **100% Local & Offline Control:** Communicates directly with your printer via WebSockets. No cloud, no tracking, and zero external dependencies (works perfectly on an isolated network).
* **Auto-Connect:** Bookmark your printer! Add `?ip=192.168.0.x` to the URL to automatically connect on load.
* **Modern, Non-Blocking UI:** Features custom modals, toast notifications, and dark mode (saves your preference). No annoying browser `alert()` pop-ups.
* **Efficient File Management:** Rapidly sort (A-Z / Size), filter, and delete files or print history.
* **Wildcard Filtering:** Quickly find specific files using advanced wildcard support (e.g., `*.gcode` or `*PLA*`).
* **Multilingual UI:** Built-in language support for English, Danish, German, French, Spanish, and Italian.
* **Responsive Design:** Optimized for both desktop and mobile browsers.

## How to use
1. Download the [`centauri-manager.html`](centauri-manager.html) file from this repository.
2. Open it in any modern web browser (Chrome, Edge, Safari, or Firefox).
3. Enter your printer's local IP address and click **Connect** (or use the `?ip=` URL parameter for automatic login).
4. Manage your files effortlessly.

## Technical Details
* **Framework:** Vanilla HTML5, CSS3, and JavaScript (Zero external dependencies).
* **Communication:** WebSocket protocol with custom JSON payloads.
* **Branding:** Developed by [Broby IT](https://broby-it.dk).

## Licensing
This project is open-source and licensed under the [MIT License](LICENSE).

## Feedback & Contributions
This tool was created to solve a community-driven pain point. Feedback, suggestions, and pull requests are highly appreciated. If you encounter any bugs, please open an issue!

---
*Created by [Broby IT](https://broby-it.dk) | Version 2.0*
