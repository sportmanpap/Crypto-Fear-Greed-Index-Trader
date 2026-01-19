<p align="center">
  <img src="https://via.placeholder.com/1280x640/0b0f1a/00ff9d?text=Crypto+Fear+%26+Greed+Trader" alt="Crypto Fear & Greed Trader — 2026" width="900"/>
  <br/>
  <sub>Торгуй не только графиком. Торгуй эмоциями рынка.</sub>
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
  Один из самых стильных и понятных десктопных инструментов 2026 года,<br/>
  который показывает цену BTC/USDT и <strong>Fear & Greed Index</strong> в одном окне — как на профессиональном терминале.
</p>

## ✨ Что ты получаешь сразу после запуска

- Живой **Fear & Greed Index** прямо с alternative.me (обновляется каждые 5–15 минут)
- Чёткий сигнал: **BUY 🟢** / **HOLD ⚪** / **SELL 🔴**
- Тёмный неоновый интерфейс в духе TradingView + Binance
- Лёгкий запуск — один .exe файл (~60 МБ), Python не нужен
- База для будущего: свечи, алерты, мульти-пары, Telegram-уведомления

<p align="center">
  <img src="assets/screenshot-main-2026.png.jpg" width="900" alt="Главный экран — цена + Fear & Greed"/>
  <br/>
  <sub>Тёмная тема, неон, чистота — всё, что любят трейдеры в 2026</sub>
</p>

## Как пользоваться (30 секунд)

1. Скачай последнюю версию → **[Releases → CryptoFearGreedTrader.exe](https://github.com/hikkaq/crypto-fear-greed-trader/releases)**
2. Запусти файл
3. Смотри текущий индекс и сигнал

Готово. Никакой установки, никаких ключей API (пока).

## Логика сигналов (классика 2018–2026)

| Fear & Greed     | Зона              | Сигнал     | Эмоция рынка          |
|------------------|-------------------|------------|-----------------------|
| 0–24             | Extreme Fear      | **BUY**    | Паника → дно?         |
| 25–49            | Fear              | **BUY**    | Страх → хорошая цена  |
| 50–74            | Neutral → Greed   | **HOLD**   | Рынок спокоен         |
| 75–100           | Greed / Extreme   | **SELL**   | Эйфория → вершина?    |

## 🛠 Технологии под капотом

- **customtkinter** — самый красивый GUI для Python в 2025–2026
- **matplotlib** — надёжные графики
- **requests** — живые данные Fear & Greed
- **PyInstaller** → один .exe для Windows

## 🚀 Что можно добавить (и я помогу)

- Реальные японские свечи (lightweight-charts или binance websocket)
- Цветные зоны страха/жадности прямо на графике
- Уведомления в Telegram / Windows Toast
- Поддержка ETH, SOL, BNB и других пар
- Настраиваемые пороги (не 30/70, а свои)
- Лёгкий backtest стратегии
- Кроссплатформенность (macOS / Linux)

## Установка из исходников (для разработчиков)

```bash
git clone https://github.com/hikkaq/crypto-fear-greed-trader.git
cd crypto-fear-greed-trader
pip install -r requirements.txt
python src/main.py
