# Centauri Carbon Manager

A fast, lightweight, and local file management tool designed for Elegoo 3D printers.

## Overview
As a 3D printing enthusiast, I encountered frustrations with the native printer interface, such as lag, slow file management, and cloud dependencies. **Centauri Carbon Manager** is my solution – a clean, local-first dashboard.

It is built following the **KISS** (Keep It Simple, Stupid) and **DRY** (Don't Repeat Yourself) principles. It requires no installation or complex backend; simply open the file in your browser and connect.
<img width="726" height="992" alt="image" src="https://github.com/user-attachments/assets/094bf94f-567c-40e2-bfa0-14024b30f570" />

## Key Features
* **100% Local Control:** Communicates directly with your printer via WebSockets. No cloud, no tracking.
* **Efficient File Management:** Rapidly delete files and print history.
* **Wildcard Filtering:** Quickly find specific files or file types using wildcard support (e.g., `*.gcode` or `*PLA*`).
* **Multilingual UI:** Built-in language support for English, Danish, German, French, Spanish, and Italian.
* **Responsive Design:** Optimized for both desktop and mobile browsers.

## How to use
1. Download the [centauri-manager.html](centauri-manager.html) file from this repository.
2. Open it in any modern web browser (Chrome, Edge, or Firefox).
3. Enter your printer's local IP address and click **Connect**.
4. Manage your files effortlessly.

## Technical Details
* **Framework:** Vanilla HTML5, CSS3, and JavaScript (No external dependencies).
* **Communication:** WebSocket protocol with custom JSON payloads.
* **Branding:** Developed by [Broby IT](https://broby-it.dk).

## Licensing
This project is open-source and licensed under the [MIT License](LICENSE).

## Feedback & Contributions
This tool was created to solve a community-driven pain point. Feedback, suggestions, and pull requests are highly appreciated. If you encounter any bugs, please open an issue!

---
*Created by [Broby IT](https://broby-it.dk) | Version 1.0*
