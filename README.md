# ⚡ Pocket Option 24/7 Live REST API & Signal Engine

> **Production-grade 24/7 self-healing REST API & WebSocket wrapper for Pocket Option (Real & OTC asset pairs).**

[![Official Telegram Channel](https://img.shields.io/badge/Join_Telegram-CB_Traders_BD-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/+R_kEsY9yqkA1NDI1)
[![Direct Contact](https://img.shields.io/badge/Chat_on_Telegram-@YouKnowWho__am-blue?style=for-the-badge&logo=telegram)](https://t.me/YouKnowWho_am)
[![AI Signals Bot Demo](https://img.shields.io/badge/Live_Signals_Bot-@cbsignalsproai__bot-red?style=for-the-badge&logo=telegram)](https://t.me/cbsignalsproai_bot?start=1)
[![Account Verify Bot](https://img.shields.io/badge/Account_Verify_Bot-@cbtradersbd__bot-purple?style=for-the-badge&logo=telegram)](https://t.me/cbtradersbd_bot?start=1)
[![FastAPI Docs](https://img.shields.io/badge/Live_API-Swagger_Docs-009688?style=for-the-badge&logo=fastapi)](https://api1.api.cbtradersbd.com/docs)
[![License](https://img.shields.io/badge/License-Commercial_Source_Code-green?style=for-the-badge)](https://t.me/YouKnowWho_am)

---

## 🚀 Live Interactive Swagger API Documentation
Check all live endpoints, test requests, and live WebSocket feeds directly on our server:  
👉 **[https://api1.api.cbtradersbd.com/docs](https://api1.api.cbtradersbd.com/docs)**

---

## 🤖 Try Our Live Telegram Bots & Demos
* 🎯 **AI Trading Signals Bot (90%+ Winrate):** [https://t.me/cbsignalsproai_bot?start=1](https://t.me/cbsignalsproai_bot?start=1)
* 🛡️ **Affiliate ID Account Verification Bot:** [https://t.me/cbtradersbd_bot?start=1](https://t.me/cbtradersbd_bot?start=1)

---

## ✨ System Architecture & Features
- 🕒 **24/7 Real & OTC Coverage**: Real-time market data streaming for Pocket Option.
- 📊 **Non-Repaint History**: Closed M1/M5 candle history database.
- 💰 **Live Payout Tracking**: Accurate payout percentage monitor per minute.
- 🛡️ **Self-Healing Architecture**: Auto-reconnect & session recovery.
- 🤖 **Multi-Bot Ready**: Connect to Telegram alerts, MT4/MT5, or TradingView webhooks.

---

## 📂 Project Directory Structure

```
├── config/
│   └── settings.json          # Server & WebSocket configurations
├── src/
│   ├── core/
│   │   ├── client.py          # High-throughput API client
│   │   └── config.py          # Pydantic environment settings
│   └── utils/
│       └── logger.py          # Formatted logging system
├── examples/
│   ├── quickstart.py          # 1-Click live feed connector
│   └── stream_candles.py      # 24/7 OTC streaming demonstration
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 📡 Live API Endpoints Overview

| Endpoint | Method | Description |
| :--- | :--- | :--- |
| `/docs` | `GET` | Interactive Swagger API documentation |
| `/api/pocket option/live-price` | `GET` | Real-time price stream & tick updates |
| `/api/pocket option/candles` | `GET` | Closed M1/M5 historical candle datasets |
| `/api/pocket option/payouts` | `GET` | Live payout percentage monitor across all pairs |
| `/api/pocket option/signals` | `POST` | Strategy webhook trigger & alert dispatcher |

---

## 🛒 Purchase Full Unlocked Source Code & Commercial License

Looking for the production-ready source code with complete rights and 1-on-1 developer support?

### What’s Included in the Full Package:
- 📦 **100% Full Unlocked Python Source Code** (`app.py`, workers, database controllers, WebSocket core).
- 🚀 **1-Click Automated Windows & Ubuntu VPS Launchers**.
- ⚡ **Unlimited Deployment Rights** (Personal & Commercial Use).
- 🛠️ **24/7 Developer Support & Setup Assistance**.
- 🔄 **Lifetime Code Updates & Bug Fixes**.

### 📩 Contact to Purchase / Inquiries:
- 📩 **Telegram (Direct):** [@YouKnowWho_am](https://t.me/YouKnowWho_am)
- 📢 **Official Telegram Channel:** [CB Traders BD](https://t.me/+R_kEsY9yqkA1NDI1)
- 🤖 **AI Signals Bot Demo:** [@cbsignalsproai_bot](https://t.me/cbsignalsproai_bot?start=1)
- 🛡️ **UID Account Verify Bot:** [@cbtradersbd_bot](https://t.me/cbtradersbd_bot?start=1)
- 💳 **Accepted Payment Methods:** USDT (TRC20/BEP20), Binance Pay, Crypto, Local Mobile Banking.

---

## 🌐 CB Traders BD Ecosystem — Explore All Broker APIs & Bots

Cross-platform algorithmic trading tools, real-time WebSocket feeds, and AI signal engines:

| Platform | Official REST & WebSocket API | Signals & Telegram Bots | Data Tools & Bridges |
| :--- | :--- | :--- | :--- |
| **Quotex** | [Quotex-API](https://github.com/cbtradersbd/Quotex-API) | [quotex-otc-signal-engine](https://github.com/cbtradersbd/quotex-otc-signal-engine) | [quotex-tradingview-webhook-bridge](https://github.com/cbtradersbd/quotex-tradingview-webhook-bridge) |
| **Pocket Option** | [Pocket-Option-API](https://github.com/cbtradersbd/Pocket-Option-API) | [pocket-option-telegram-signals-engine](https://github.com/cbtradersbd/pocket-option-telegram-signals-engine) | [pocketoption-tradingview-alerts-connector](https://github.com/cbtradersbd/pocketoption-tradingview-alerts-connector) |
| **IQ Option** | [IQ-Option-API](https://github.com/cbtradersbd/IQ-Option-API) | [iq-option-telegram-signal-bot](https://github.com/cbtradersbd/iq-option-telegram-signal-bot) | [iq-option-market-data-api](https://github.com/cbtradersbd/iq-option-market-data-api) |
| **Binolla** | [Binolla-API](https://github.com/cbtradersbd/Binolla-API) | [binolla-live-signals-bot](https://github.com/cbtradersbd/binolla-live-signals-bot) | [binolla-tradingview-webhook-bot](https://github.com/cbtradersbd/binolla-tradingview-webhook-bot) |

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>1. How do I get started and connect to the live API endpoints?</b></summary>
Explore interactive Swagger documentation, test live endpoints, and inspect schemas directly at <a href="https://api1.api.cbtradersbd.com/docs">https://api1.api.cbtradersbd.com/docs</a>. Clone this repository, install dependencies with <code>pip install -r requirements.txt</code>, and configure credentials in <code>.env</code>.
</details>

<details>
<summary><b>2. Are 24/7 OTC asset pairs supported for continuous trading?</b></summary>
Yes! Our systems provide continuous round-the-clock streaming for OTC asset pairs alongside standard financial currency pairs with real-time candlestick feeds and low-latency execution.
</details>

<details>
<summary><b>3. Can I automate binary options trades directly from TradingView alerts?</b></summary>
Yes! Our TradingView webhook bridges convert Pine Script alert webhooks into instant automated trade executions with customizable risk management, martingale, and stop-loss rules.
</details>

<details>
<summary><b>4. How do the copy trading bridge and signal engines work?</b></summary>
The copy trading bridge mirrors trades from master accounts to target accounts with zero latency. The signal engines utilize non-repaint technical indicators and volatility filters to dispatch high-accuracy alerts to Telegram or webhook endpoints.
</details>

---

## 🏷️ Search & Discovery Keywords
`quotex-api` • `pocket-option-api` • `iq-option-api` • `binolla-api` • `binary-options-bot` • `algorithmic-trading` • `tradingview-webhook-bridge` • `247-otc-market-data` • `fastapi-websocket-stream` • `copy-trading-bot` • `automated-trading-python` • `live-payout-monitor`

---

## ⭐ Star This Project
If this toolkit assisted your algorithmic trading research or bot deployment, please give it a **Star on GitHub** to support active open-source development and help other traders find it!

