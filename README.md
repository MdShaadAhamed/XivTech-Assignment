# XivTech-Assignment

# 🚀 Real-Time Crypto Price Tracker

A responsive React + Redux Toolkit app that displays simulated real-time cryptocurrency data updates. This project mimics live data feeds (like CoinMarketCap or Binance) by using mocked WebSocket-like updates via `setInterval`.

---

# 📸 Demo

> 🎥 [Add your video or GIF link here]

---

# 📦 Tech Stack

- **React** — UI library
- **Redux Toolkit** — State management
- **JavaScript (ES6)** — Core language
- **CSS Modules** — Responsive styling
- **Mocked WebSocket** — Simulated with `setInterval`

---

# 🧠 Features

- 📊 Displays 5 crypto assets in a responsive table
- 🔄 Real-time price updates every 1.5 seconds
- 🟢 Color-coded percentage changes (green/red)
- 📈 Static 7-day trend charts
- 💾 Redux for all data storage (no local state)

---

## 🧪 Sample Crypto Assets

- Bitcoin (BTC)
- Ethereum (ETH)
- Tether (USDT)
- Ripple (XRP)
- Binance Coin (BNB)

Each asset displays:
- Logo
- Name & Symbol
- Price
- % Change (1h, 24h, 7d)
- Market Cap
- 24h Volume
- Circulating / Max Supply
- Static 7-Day Chart

---

## 🛠️ How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/crypto-price-tracker.git
   cd crypto-price-tracker

2. Install dependencies:
      npm install
** Folder Structure

   src/
├── app/
│   └── store.js
├── assets/
│   └── (coin logos & chart svgs)
├── features/
│   └── crypto/
│       ├── cryptoSlice.js
│       ├── sampleData.js
│       └── CryptoTable.js
├── App.js
└── index.js
