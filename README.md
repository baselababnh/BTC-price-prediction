# 📈 BTC Price Prediction with GRU

A deep learning model that predicts future Bitcoin closing prices using:
- ✅ GRU (Gated Recurrent Unit) neural network
- ✅ Technical Indicators: EMA, RSI, MACD
- ✅ Real-time price comparison with CoinGecko API
- ✅ Candlestick chart for the next 3-hour forecast

---

## 🚀 Features

- 📅 Trained on hourly BTC price data from **2023–2025**
- 🔮 Multi-step (3-hour ahead) recursive forecasting
- 📊 Technical indicators calculated directly (no external TA library)
- ⚙️ Built with TensorFlow + Scikit-learn
- 📉 Candlestick plot combining real + predicted candles
- 🌐 Compares model predictions with **live BTC price** from CoinGecko

---

## 🧪 Sample Output

```
✅ RMSE: 555.20  
✅ MAE: 383.61  
✅ R²: 99.44%

🔮 Predicted BTC Closing Prices for Next 3 Hours:
Hour +1: $103181.87
Hour +2: $103290.41
Hour +3: $103412.59

📈 Live BTC Price: $103200.00
```

---

## 🛠️ Installation

Install required libraries using:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn plotly requests
```

---

## 🧠 How to Run

- Run the script `btc_prediction_gru.py`  
  **or**
- Open the notebook `btc_prediction_gru.ipynb` in **Google Colab / Jupyter**

---

## 📁 Files

| File | Description |
|------|-------------|
| `btc_prediction_gru.ipynb` | The full notebook with training + prediction |
| `btc_1h_data_2018_to_2025.csv` | Historical BTC data |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

---

## 📊 Dataset

**Source**: [Kaggle Bitcoin Historical Dataset](https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024)

Filtered for years **2023–2025** to better reflect real-time trends.

---

## ✨ Future Ideas

- Predict 12/24 hours ahead
- Include CoinGecko market sentiment & volume metrics
- Use LSTM + GRU hybrid model
- Build interactive dashboard with Streamlit

---

## 👤 Author

**Basel Ababneh**  
AI & Data Science Engineer  
📍 Jordan | 🧠 BTC Forecaster
