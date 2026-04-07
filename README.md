# 🚀 ETHUSDT Algorithmic Trading Bot

A Python-based algorithmic trading signal bot that analyzes ETH/USDT market data using technical indicators and sends real-time alerts via Telegram.

This project demonstrates automated market analysis using EMA, RSI, and CCI indicators along with scheduled execution and logging.

---

# 📌 Project Summary

The **ETHUSDT Trading Bot** fetches market data from the Delta Exchange API, processes technical indicators, generates trading signals, and sends alerts automatically.

The bot runs every **30 minutes**, detects **Long**, **Short**, and **Fake signals**, and logs signal history for future analysis.

---

# 🧠 Key Features

- 📊 Technical Indicator Analysis  
  - EMA (7)  
  - RSI (14)  
  - CCI (60)  
  - CCI EMA smoothing  

- 📈 Signal Generation  
  - Long & Short trade detection  
  - Fake signal filtering  
  - Trend continuation logic  

- 📡 Telegram Alerts  
  - Sends real-time trading signals  
  - Supports multiple users  

- ⏱ Automated Scheduling  
  - Runs every 30 minutes  
  - Continuous monitoring  

- 📂 Signal Logging  
  - Saves signals to CSV  
  - Enables historical tracking  

---

# 🏗 How It Works

1. Fetch market data from Delta Exchange API  
2. Calculate technical indicators  
3. Generate trading signals  
4. Detect fake signals  
5. Send Telegram alerts  
6. Save signals to CSV  

---

# 🛠 Tech Stack

- **Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - requests  
  - pytz  
  - apscheduler  

- **APIs Used:**  
  - Delta Exchange API  
  - Telegram Bot API  

---

# 📂 Project Structure
