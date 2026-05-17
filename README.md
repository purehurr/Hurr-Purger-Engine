‎# 💨 Hurr Purger Engine (v1.1)
‎**Developed by [purehurr](https://instagram.com/purehurr)**
‎
‎---
‎
‎### ✨ Main Features
‎* ⚡ **Ultra-Speed:** Blazing fast message deletion using asynchronous chunking processing (15 messages/batch).
‎* 🛡️ **Anti-429 Protection:** Advanced built-in sleep timers (`550ms` - `600ms`) to completely prevent rate limits and account bans.
‎* 🛑 **Instant Interruption:** Press `Ctrl + Space` at any time to safely cancel the running process and instantly jump back to the main menu.
‎* 🔄 **Self-Updating Core:** The execution command automatically pulls the latest code from GitHub on every launch, ensuring you are always up to date.
‎* 📱 **Termux Optimized:** Light environment build crafted specifically for seamless mobile and desktop terminal execution.
‎
‎---
‎
‎### 📥 Quick Installation & Auto-Update
‎* Copy and paste this single command into your Termux/Terminal to install dependencies and fetch/run the latest updates instantly:
‎
‎```bash
‎if [ ! -d "node_modules" ]; then pkg update -y && pkg upgrade -y && pkg install nodejs git -y && npm install discord.js-selfbot-v13 readline-sync readline; fi && curl -sL [https://raw.githubusercontent.com/purehurr/Hurr-Purger-Engine/refs/heads/main/hurr.js](https://raw.githubusercontent.com/purehurr/Hurr-Purger-Engine/refs/heads/main/hurr.js) -o hurr.js && clear && node hurr.js
‎
‎```
‎---
‎
‎### 🎮 Command Menu
‎|Option|Action|Description|
‎| --- | --- | --- |
‎| 1 | 👤 Friends | Removes all friends from your relationship cache with a safe delay |
‎| 2 | 🌐 Servers | One-click automatic server leave for all non-owned guilds |
‎| 3 | 🌊 Deep Purge | Full automated sweep to scan and delete your messages from all active DMs. |
‎| 4 | 🎯 ID Target | Targets a specific User ID or Server ID to clear your message footprint |
‎| 5 | 📘 All Servers| Loops through all joined servers and clears your messages from text channels |
‎| 6 | 🔗 Developer | Displays the developer verified info and social media contact links |
‎| 0 | 🚪 Exit | Safely terminates the script execution and returns to terminal control |
‎
‎---
‎
‎### ⚠️ Security Disclaimer
‎* This script is developed for educational, administrative, and data management purposes only. The developer (purehurr) is not responsible for any misuse, data loss, or violations of Discord's Terms of Service. Your usage of this tool is strictly at your own risk.
‎
‎### ​❕ Account Token Requirement
‎* ​To initialize the engine connection, you must provide your account token.
‎---
‎### ❗ Found a bug? Contact me bellow:
‎
‎* 🔒 [My Discord](https://discord.gg/DywPf3tcGZ)
‎* 🐦 [My X/Twitter](https://x.com/PureHurr)
‎* 🎬 [My Instagram](https://instagram.com/purehurr)
‎
