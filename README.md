# 🚀 MCS-TG-CORE

> A high-performance, open-source core engine and centralized cloud synchronization framework for Telegram bots, powered by **RAM + GitHub storage** and real-time remote control management.

---

## ✨ Key Features

- **RAM + GitHub Storage:** Eliminates permanent local disk usage, keeping all runtime data safely synced directly with GitHub.
- **Remote Control & Kill Switch:** Built-in fail-closed remote management system to control bot uptime, global ban lists, and update notices remotely.
- **Smart Error Handling:** Advanced distinction between transient conflicts/server blips and critical token auth failures, preventing log spam.
- **Automatic Auto-Retry:** Handles high-concurrency race conditions and SHA mismatches seamlessly.

---

## 📂 Repository Structure

```text
MCS-TG-CORE/
├── public-bot-on-off.json    # Remote control switch (active status / kill switch)
├── public-bot-ban.json       # Global banned users list for the bot network
├── public-bot-update.json    # Centralized update notices and version tracker
└── README.md                 # Documentation and project overview
