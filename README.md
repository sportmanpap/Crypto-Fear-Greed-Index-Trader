<p align="center">
  <img src="assets/screenshot-main2-2026.png" width="900" alt="Main screen — Price + Fear & Greed">
  <br/>
  <sub>Trade not just the chart. Trade market emotions.</sub>
</p>

<h1 align="center">Crypto Fear & Greed Index Trader</h1>

<p align="center">
  <a href="https://github.com/hikkaq/crypto-fear-greed-trader/stargazers">
    <img src="https://img.shields.io/github/stars/hikkaq/crypto-fear-greed-trader?style=for-the-badge&color=00ff9d&logoColor=white" alt="Stars"/>
  </a>
  <a href="https://github.com/hikkaq/crypto-fear-greed-trader/releases">
    <img src="https://img.shields.io/github/v/release/hikkaq/crypto-fear-greed-trader?color=9d00ff&label=latest%20.exe&style=for-the-badge&logo=windows11" alt="Latest Release"/>
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/hikkaq/crypto-fear-greed-trader?color=ff3366&style=for-the-badge" alt="License"/>
  </a>
  <br/>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Windows-ready-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/TradingView-inspired-1e90ff?style=for-the-badge" alt="TradingView style"/>
</p>

<p align="center">
  One of the most stylish and intuitive desktop tools of 2026,<br/>
  combining BTC/USDT price and the <strong>Fear & Greed Index</strong> in a single professional-grade window.
</p>

## ✨ What you get right after launch

- Live **Fear & Greed Index** from alternative.me (updates every 5–15 minutes)
- Clear signal: **BUY 🟢** / **HOLD ⚪** / **SELL 🔴**
- Dark neon interface inspired by TradingView + Binance
- One-click launch — single .exe file (~60 MB), no Python installation required
- Solid foundation for future features: candlesticks, alerts, multi-pair support, Telegram notifications

<p align="center">
  <img src="assets/screenshot-main-2026.png" width="900" alt="Main screen — Price + Fear & Greed"/>
  <br/>
  <sub>Dark theme, neon accents, clean layout — everything traders love in 2026</sub>
</p>

## How to use (30 seconds)

1. Download the latest version → **[Releases → CryptoFearGreedTrader.exe](https://github.com/hikkaq/crypto-fear-greed-trader/releases)**
2. Run the file
3. Watch the current index and signal

Done. No installation, no API keys (for now).

## Signal logic (classic 2018–2026)

| Fear & Greed   | Zone              | Signal     | Market Emotion             |
|----------------|-------------------|------------|----------------------------|
| 0–24           | Extreme Fear      | **BUY**    | Panic → bottom?            |
| 25–49          | Fear              | **BUY**    | Fear → attractive price    |
| 50–74          | Neutral → Greed   | **HOLD**   | Market is calm             |
| 75–100         | Greed / Extreme   | **SELL**   | Euphoria → top?            |

## 🛠 Technologies under the hood

- **customtkinter** — the most beautiful GUI for Python in 2025–2026
- **matplotlib** — reliable charting
- **requests** — live Fear & Greed data
- **PyInstaller** → single .exe for Windows

## 🚀 Planned features (happy to help implement)

- Real Japanese candlesticks (lightweight-charts or Binance websocket)
- Colored Fear/Greed zones directly on the chart
- Notifications via Telegram / Windows Toast
- Support for ETH, SOL, BNB and other pairs
- Customizable thresholds (not just 30/70)
- Simple backtesting of the strategy
- Cross-platform support (macOS / Linux)

## Installation from source (for developers)

```bash
git clone https://github.com/hikkaq/crypto-fear-greed-trader.git
cd crypto-fear-greed-trader
pip install -r requirements.txt
python src/main.py
