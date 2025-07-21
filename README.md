# 📈 Stock Market Price Prediction (Web-App)

This is a **web-based machine learning project** that predicts stock prices using historical data and deep learning (LSTM). Built with **Python**, **Streamlit**, and data fetched via **Yahoo Finance**, this interactive dashboard allows users to explore stock history, moving averages, and forecast trends with visual plots.

---

## 👨‍💻 Author

**Gautam Yadav**
- 📧 gautamyadav1406@gmail.com
- 📅 Project Date: July 21, 2025

---

## 🔍 Project Overview

The app allows users to:
- Enter a stock ticker symbol (e.g., `MSFT`, `AAPL`)
- View historical stock data (Open, Close, High, Low, Volume)
- Visualize Moving Averages (MA50, MA100, MA200)
- Compare real vs predicted stock prices using an LSTM model
- Interact through a clean and responsive web UI

---

## 💡 Key Features

- 📊 **Streamlit-powered web UI** for fast and interactive use
- 🧠 **LSTM model** trained on historical stock prices (Close values)
- 🕐 Uses **10 years of stock data** (2015–2025)
- 🔁 Shows **Moving Averages** with MA_50, MA_100, and MA_200
- 🔮 Predicts stock trends and shows **Original vs Predicted** price graphs

---

## ⚙️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (Pandas, NumPy, Matplotlib, Seaborn, yfinance)
- **Machine Learning**: TensorFlow/Keras (LSTM)
- **Data Source**: Yahoo Finance API via `yfinance`

---

## 🧠 LSTM Model Architecture

- 4 stacked **LSTM layers** with Dropout for regularization
- Trained with **100 past days** to predict the next day’s price
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- 50 epochs for training

---

## 📘 Dataset Info

- Source: Yahoo Finance via yfinance
- Example stock symbol: MSFT
- Timeframe: 2015-01-01 to 2025-07-09
- Features used: Open, High, Low, Close, Volume

---

## 📜 Project Report
Detailed description of the methodology, results, and performance is available in `Stock_Price_Prediction_Model.pdf`

---

## How it Looks

![Screenshot 1](https://github.com/nextgautam/Stock_Price_Prediction_System/blob/48910f6c7a75ec80f7614852c318051936a64fa1/Screenshots_of_Web-app/Screenshot%202025-07-21%20185951.png)
![Screenshot 2](https://github.com/nextgautam/Stock_Price_Prediction_System/blob/d6a2484c83d4bc4dd984436fc2ccc04aa7fca952/Screenshots_of_Web-app/Screenshot%202025-07-21%20190021.png)
![Screenshot 3](https://github.com/nextgautam/Stock_Price_Prediction_System/blob/d6a2484c83d4bc4dd984436fc2ccc04aa7fca952/Screenshots_of_Web-app/Screenshot%202025-07-21%20190102.png)
![Screenshot 4](https://github.com/nextgautam/Stock_Price_Prediction_System/blob/d6a2484c83d4bc4dd984436fc2ccc04aa7fca952/Screenshots_of_Web-app/Screenshot%202025-07-21%20190132.png)
![Screenshot 5](https://github.com/nextgautam/Stock_Price_Prediction_System/blob/d6a2484c83d4bc4dd984436fc2ccc04aa7fca952/Screenshots_of_Web-app/Screenshot%202025-07-21%20190154.png)

---

## 📌 Acknowledgements

- Yahoo Finance for providing free market data
- Streamlit for simplifying web-based ML deployment
- TensorFlow for deep learning capabilities
