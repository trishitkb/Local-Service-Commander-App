# Local Service Commander — Public Releases Repository

> **One control panel for everything running in your local development environment.**

[![Download](https://img.shields.io/github/v/release/trishitkb/local-service-commander-app?label=download&style=flat-square&color=1e40af)](https://github.com/trishitkb/local-service-commander-app/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)](https://github.com/trishitkb/local-service-commander-app/releases)
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-amber?style=flat-square)](https://buymeacoffee.com/trishitkb)
[![License](https://img.shields.io/badge/license-Proprietary-orange?style=flat-square)](#license)

---

## What is Local Service Commander?

Local Service Commander is a **lightweight Windows desktop application** that gives developers real-time visibility and control over every process, service, and development server running on their machine.

No more juggling Task Manager, multiple terminals, Docker Desktop, and Windows Services Manager simultaneously. Commander consolidates everything into a single, information-dense dashboard.

---

## Features

- **Auto Discovery** — Automatically identifies Redis, PostgreSQL, MySQL, MongoDB, Docker, Vite, Next.js, Node.js, Python servers, Java, .NET, and 20+ more
- **Live Telemetry** — Real CPU %, RAM, thread count, and TCP socket state from Windows OS APIs — no estimates
- **Process Control** — Stop, restart, or kill any process with confirmation guards for protected system processes
- **Custom Process Definitions** — Define and save your own project commands (e.g. `npm run dev` in a specific directory) that persist across restarts
- **Collections** — Group services into named stacks and start/stop the whole collection in one click
- **Port Matrix** — See every listening TCP port, which process owns it, and how many active clients are connected
- **Log Streaming** — Real-time stdout/stderr tailing for every managed process
- **Dark & Light Themes** — Persistent theme preference with high-contrast design
- **Offline-First** — No cloud, no telemetry, no accounts. Everything stays on your machine.

---

## Download

**[⬇ Download Latest Release (v0.1.0)](https://github.com/trishitkb/Local-Service-Commander-App/releases/tag/v0.1.0)**

| File | Type | Direct Download |
|---|---|---|
| `Local.Service.Commander_0.1.0_x64-setup.exe` | NSIS Setup (Recommended) | [Download .exe](https://github.com/trishitkb/Local-Service-Commander-App/releases/download/v0.1.0/Local.Service.Commander_0.1.0_x64-setup.exe) |
| `Local.Service.Commander_0.1.0_x64_en-US.msi` | Windows Installer | [Download .msi](https://github.com/trishitkb/Local-Service-Commander-App/releases/download/v0.1.0/Local.Service.Commander_0.1.0_x64_en-US.msi) |

---

## System Requirements

- **OS**: Windows 10 (version 1903+) or Windows 11 (64-bit)
- **Runtime**: WebView2 (pre-installed on Windows 10/11)
- **RAM**: ~30 MB idle
- **Prerequisites**: None — 100% self-contained standalone app

---

## Installation

1. Download the installer from [Releases](https://github.com/trishitkb/local-service-commander-app/releases)
2. Run `Local Service Commander_0.1.0_x64-setup.exe`
3. Launch from the Start menu or Desktop shortcut

---

## Support & Feedback

- Found a bug or want to request a feature? Please [open an issue](https://github.com/trishitkb/local-service-commander-app/issues).
- Enjoying Local Service Commander? [Buy me a coffee](https://buymeacoffee.com/trishitkb) to support development!
| `LocalServiceCommander-x64.msi` | MSI installer for enterprise / GPO deployment |

**System Requirements:** Windows 10 (1803+) or Windows 11, x64, ~12 MB disk space.  
No Node.js or runtime dependencies required.

---

## Installation

1. Download the installer from [Releases](https://github.com/trishitkb/local-service-commander-app/releases)
2. Run `LocalServiceCommander-Setup-x64.exe`
3. Follow the installer prompts (per-user or machine-wide install)
4. Launch from the Start Menu or Desktop shortcut

---

## Supported Services (Auto-Detected)

Redis · PostgreSQL · MySQL / MariaDB · MongoDB · Docker Engine · Node.js · Vite · Next.js · React Dev Server · Vue · Angular · Python · FastAPI · Django · Flask · Java / Spring Boot · .NET / ASP.NET · Nginx · Apache · RabbitMQ · Elasticsearch · Bun · Deno · Custom Processes

---

## Security Model

- The companion API is **bound exclusively to `127.0.0.1`** — it is never exposed to the network
- The stop/kill endpoint **requires explicit user confirmation** in the UI
- A **protected process list** prevents accidentally terminating system-critical processes (LSASS, CSRSS, SMSS, etc.)
- No data leaves the machine — no analytics, no crash reporting, no cloud sync

---

## Reporting Issues

Found a bug or want to request a feature? Please [open an issue](https://github.com/trishitkb/local-service-commander-app/issues).

Include:
- Windows version
- Commander version
- Steps to reproduce
- What you expected vs. what happened

---

## License

Local Service Commander is **proprietary software**. The binary releases are free to use for personal and commercial development purposes.  
The source code is not publicly available.

© 2026 Local Service Commander Contributors. All rights reserved.
