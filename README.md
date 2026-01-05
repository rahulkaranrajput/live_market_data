# FYERS 5-Minute Candle Generator

A Python project that connects to the FYERS Trading API to fetch live market
data and generate 5-minute OHLC candles in real time.

---

## 📌 Features (Planned)
- FYERS API authentication
- Live market data fetching
- 5-minute OHLC candle construction
- CSV / Database storage
- Extendable architecture for:
  - Indicators
  - Strategies
  - Backtesting
  - Alerts

---

## 🧱 Tech Stack
- Python 3.10+
- FYERS Trading API
- Pandas
- YAML-based configuration

---

## 📂 Project Structure

Live_Market_Data/
├── config/ # Configuration & secrets
├── src/ # Application source code
│ ├── fyers/ # FYERS API logic
│ ├── candles/ # Candle building logic
│ └── utils/ # Helper utilities
├── data/ # Generated candle data
├── logs/ # Logs
├── docs/ # Architecture & documentation


---

## ⚠️ Disclaimer
This project is for educational purposes only.
Trading in financial markets involves risk.
The author is not responsible for any financial loss.

---

## 🚧 Status
Work in progress 🚀
