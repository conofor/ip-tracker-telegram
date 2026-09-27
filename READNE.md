<div align="center">

# 🌐 IP Tracker

### Telegram Mini App for monitoring your IP address changes

**Track • Monitor • Export**

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg?style=flat-square)](LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-Mini_App-black?style=flat-square&logo=telegram)](https://core.telegram.org/bots/webapps)
[![No Server Required](https://img.shields.io/badge/Server-Not_Required-black?style=flat-square)](#)
[![Static](https://img.shields.io/badge/100%25-Static_HTML-black?style=flat-square)](#)

</div>

---

## 📖 About

**IP Tracker** is a lightweight, privacy-first Telegram Mini App that monitors your IP address changes over time. All data is stored **locally in your browser** — no server, no backend, no tracking.

It automatically checks your IP at configurable intervals and keeps a complete history of every change, showing you exactly when your ISP assigned you a new address and how long the previous one lasted.

> 💡 **Why?** Useful for users with dynamic IPs who need to track changes for port forwarding, remote access, DNS updates, or simply out of curiosity.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎨 **Auto Theme** | Seamlessly adapts to Telegram's light/dark theme |
| 📡 **IP Detection** | Uses multiple fallback APIs (ipify, ip.sb, ifconfig.me) |
| 📜 **Change History** | Full log of every IP change with timestamps |
| ⏱️ **Active Timer** | Live counter showing how long your current IP has been active |
| 🔁 **Smart Refresh** | Configurable auto-check interval (6h / 12h / 24h / 48h) |
| 🔔 **Seen Detection** | Notifies you if an IP was previously assigned to you |
| 💾 **Export & Backup** | Download your data as JSON or CSV |
| 📥 **Import** | Restore data from a previous backup |
| 📊 **Stats** | Total changes count and unique IPs seen |
| 🚀 **Zero Backend** | 100% static — works on any free hosting |
| 🔒 **Privacy First** | All data stays in your browser's localStorage |

---

## 🛠 Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, animations, flexbox
- **Vanilla JavaScript** — no frameworks, no dependencies
- **[Telegram Web App SDK](https://core.telegram.org/bots/webapps)** — theme integration
- **localStorage** — client-side data persistence

---
