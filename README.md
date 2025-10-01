# 🌅 DAWN BOT - Auto Validator & Token Manager

**DAWN-BOT BY DROPSTERMIND**
Automated Dawn Internet validator management with multi-threading and proxy support.

<p align="center">
  <img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="Python 3.8+">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License MIT">
  <img src="https://img.shields.io/github/stars/dropstermind/dawn-bot.svg" alt="GitHub Stars">
</p>

---

## 📋 Table of Contents

* [Overview](#-overview)
* [Features](#-features)
* [Requirements](#-requirements)
* [Installation](#-installation)
* [Configuration](#️-configuration)
* [Usage](#-usage)
* [File Structure](#-file-structure)
* [Proxy Support](#-proxy-support)
* [Bot Features Detail](#-bot-features-detail)
* [Logging Examples](#-logging-examples)
* [Troubleshooting](#-troubleshooting)
* [Contributing](#-contributing)
* [Support](#-support)
* [Disclaimer](#️-disclaimer)
* [License](#-license)
* [Quick Start Summary](#-quick-start-summary)

---

## 🎯 Overview

**DAWN-BOT BY DROPSTERMIND** is an advanced automated tool designed to manage Dawn Internet validator nodes efficiently.
It provides seamless proxy integration, multi-account support, and automated keep-alive functionality to ensure optimal validator performance.

🔗 [Get Started: Register on Dawn Internet](https://dashboard.dawninternet.com/signup)
🎁 **Referral Code:** `20SN4HNL`
📥 [Download Chrome Extension](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp?hl=en)

---

## ✨ Features

* 🤖 Automated Token Setup — Auto-fetch bearer tokens with OTP verification
* 🔄 Multi-Account Support — Handle multiple accounts simultaneously
* 🌐 Smart Proxy Rotation — Automatic rotation of invalid proxies
* 💰 Real-time Earning Monitor — Track points and earnings in real-time
* 💓 Auto Keep-Alive System — Automated ping every 10 minutes
* 🎨 Beautiful Console UI — Professional logging with `colorama`
* 🔒 Secure Token Management — Safe storage of session tokens
* ⚡ High Performance — Asynchronous operations with `aiohttp`

---

## 📋 Requirements

* Python: **3.8+**
* pip: Latest version recommended
* Chrome Extension: **Dawn Validator Chrome Extension**

---

## 🛠 Installation

```bash
# 1. Clone the Repository
git clone https://github.com/DropsterMind/DAWN-DM.git
cd DAWN-DM

# 2. Install Dependencies
pip3 install -r requirements.txt
```

### Dependencies Overview

```
aiohttp==3.11.10          # Async HTTP requests
aiohttp-socks==0.9.1      # SOCKS proxy support
fake-useragent==1.5.1     # Random user agents
colorama==0.4.6           # Colored console output
pytz==2024.1              # Timezone handling
```

---

## ⚙️ Configuration

### Account Setup

Create a `emails.txt` file:

```
your_email_1@gmail.com
your_email_2@yahoo.com
your_email_3@outlook.com
```

### Proxy Setup (Optional)

Create a `proxy.txt` file:

```
# HTTP/HTTPS
http://username:password@host:port
https://host:port

# SOCKS
socks5://username:password@host:port
socks4://host:port

# Simple format
192.168.1.1:8080
```

---

## 🚀 Usage

### Step 1: Setup Tokens

```bash
python3 setup.py
```

What happens:
✅ OTP verification
✅ Token extraction & storage
✅ Referral code application
✅ Secure saving to `tokens.json`

### Step 2: Run Main Bot

```bash
python3 bot.py
```

**Bot Operations:**

* 📊 Real-time earning monitor
* 💓 Keep-alive pings
* 🔄 Proxy rotation
* 📈 Multi-account management

---

## 📁 File Structure

```
dawn-bot/
├── setup.py        # Token setup bot
├── bot.py          # Main validator bot
├── requirements.txt
├── emails.txt      # Email accounts
├── proxy.txt       # Proxy list
├── tokens.json     # Auto-generated tokens
└── README.md
```

---

## 🌐 Proxy Support

* **HTTP/HTTPS** — Standard
* **SOCKS4/5** — Secure sockets
* **Authenticated Proxies** — User:pass support
* **Rotating Proxies** — Auto rotation

**Benefits:**
🛡️ Privacy | 🌍 Geo flexibility | 🔄 Load balance | ⚡ Rate-limit bypass

---

## 🎯 Bot Features Detail

### `setup.py`

* 🔐 OTP authentication
* 📧 Email validation
* 🎯 Referral code application
* 💾 Secure token storage
* 🔄 Retry mechanism

### `bot.py`

* 📊 Real-time points monitoring
* 💓 10-minute pings
* 🔄 Multi-account concurrent handling
* 📈 Node + referral earnings tracking
* 🚦 Connection health checks

---

## 💻 Logging Examples

**Successful Setup**

```
[21:45:30] 🔧 Action: Request OTP • ✅ Success • OTP sent
```

**Earning Monitor**

```
[21:45:35] 👤 mas***ki@gmail.com • 🌐 192.168.1.1:8080 • 💰 150 PTS
```

**Keep-Alive**

```
[21:55:30] 👤 mas***ki@gmail.com • ✅ PING Success • Message: Ping received
```

---

## 🛠 Troubleshooting

**Common Issues**

* OTP not received → Check spam / connection
* Token expired → Rerun `setup.py`
* Proxy failed → Verify `proxy.txt`
* Rate limited → Add delays / use better proxies

**Error Messages**

* ❌ Connection Failed → Network/proxy issue
* ❌ Token Expired → Re-authenticate
* ❌ Rate Limited → Too many requests
* ✅ Success → Operation complete

---

## 🤝 Contributing

* ⭐ Star the repo
* 🐛 Report bugs in Issues
* 💡 Suggest new features
* 🔧 Submit PRs
* 📚 Improve docs

---

## 📞 Support

* Developer: **Dropstermind**
* Issues: [GitHub Issues](https://github.com/DropsterMind/DAWN-DM/issues)
* Docs: This README

---

## ⚠️ Disclaimer

This bot is for **educational & personal use only**.
Users are responsible for:

* 🔒 Following Dawn Internet ToS
* 📜 Complying with laws
* ⚖️ Ethical use
* 🔐 Keeping account secure

The developers are **not responsible** for account restrictions or issues arising from usage.

---

## 📄 License

This project is licensed under the **MIT License**.

---

Made with ❤️ by **Dropstermind**
**DAWN-BOT BY DROPSTERMIND** - Professional Automation Solutions

If this project helped you, consider giving it a ⭐ on GitHub!

---

## 🚀 Quick Start Summary

```bash
# Clone & Install
git clone https://github.com/DropsterMind/DAWN-DM.git
cd dawn-bot
pip install -r requirements.txt

# Configure
# → Add emails to emails.txt
# → Add proxies to proxy.txt (optional)

# Setup
python3 setup.py

# Run
python3 bot.py
```

🎉 Enjoy automated Dawn Internet validation!
