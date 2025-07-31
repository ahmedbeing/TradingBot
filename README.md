# Email-Triggered Trading Bot 📧🤖

## 🎯 Project Overview
Automated cryptocurrency trading bot that executes trades based on email signals using Binance Futures API.

## ✨ Key Features
- **Email Integration**: Monitors inbox for trading signals
- **Multi-Asset Support**: Configurable for any USDT pair (XRP, BTC, ETH, SOL, etc.)
- **Leverage Trading**: Customizable leverage settings
- **Risk Management**: Balance validation & error handling
- **Real-time Execution**: Instant market orders
- **Secure Configuration**: Environment-based settings

## 🛠️ Tech Stack
- **Python 3.x**
- **Binance API** (Spot & Futures)
- **IMAP Protocol** for email monitoring
- **Environment Variables** for security
- **Error Handling & Logging**

## ⚙️ How It Works
1. Monitors email inbox for unread messages
2. Parses email subjects for "buy" or "sell" keywords
3. Executes corresponding trades on Binance Futures
4. Supports any cryptocurrency pair with USDT

## 🔧 Configuration
```env
TRADING_SYMBOL=XRPUSDT
LEVERAGE=50
EMAIL_SERVER=imap.gmail.com
EMAIL_PORT=993
