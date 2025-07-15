# Google Trends Analysis — Bitcoin vs Altcoins (2020–2025)

📊 This project visualizes historical **Google Trends** data for Bitcoin and Altcoins inside **TradingView** using custom Pine Script.

It shows how public interest (search volume) has changed over the past five years and makes it easy to overlay with price action.

---

## 🔧 Files Included

- `Bitcoin_Google_Trends_DateBased_PineScript_v6.txt`: Trend values for "Bitcoin"
- `Altcoin_Google_Trends_DateBased_PineScript_v6.txt`: Trend values for "Altcoin"

Each script uses weekly values normalized by Google Trends (0–100 scale), mapped to exact week/year using `weekofyear` and `year`.

---

## 🧠 Purpose

This is useful for:
- Studying **retail investor interest** over time
- Correlating **price pumps/dumps** with search demand
- Exploring **bull/bear market sentiment**
To help spot momentum shifts in search interest, a 9-period Exponential Moving Average (EMA) was added on top of the Google Trends plot.

🔸 When the trend curve crosses above the 9 EMA, it may suggest rising public interest (bullish momentum confirmation)

🔹 When it drops below, it may indicate fading sentiment

---

## 📸 How it looks

> ![BTC vs Altcoin Google Trends](https://github.com/Sianap8/google-trends-btc-vs-alts/assets/YOUR-ASSET-ID)


---

## 📈 How to Use in TradingView

1. Open [https://tradingview.com](https://tradingview.com)
2. Open Pine Editor (bottom panel)
3. Paste the content of one `.txt` file (e.g., Bitcoin)
4. Click **Add to Chart**

Repeat with the other script to overlay both on the same chart.

---

## 📁 License

MIT — free to use, modify, and share.
