# 📈 Stock Price Prediction Web App (Time‑Series Demo)

A **time‑series modeling demo** that predicts stock closing prices using an **LSTM neural network** and visualizes results through a **Flask web application**.

⚠️ **Disclaimer**: This project is **for learning and demonstration only**. It is **NOT financial advice** and should **not** be used for real trading decisions.

---

## 🚀 Features

* Fetches historical stock data using **Yahoo Finance (yfinance)**
* Uses **LSTM (Keras/TensorFlow)** for time‑series prediction
* Predicts:

  * Historical test vs predicted prices
  * Future prices for user‑selected days
* Interactive **Flask web interface**
* Dynamic **Matplotlib plots rendered in HTML** (no static image files)

---

## 🧠 Model Overview

* **Model Type**: LSTM (Recurrent Neural Network)
* **Input Window**: 100 previous closing prices
* **Scaling**: MinMaxScaler (0–1)
* **Prediction Type**: Regression (Close price)

---

## 📂 Project Structure

```
stock-price-prediction/
│
├── app.py                # Flask application
├── model.keras           # Trained LSTM model
├── requirements.txt      # Python dependencies
├── templates/
│   ├── index.html        # Home page
│   └── result.html       # Results page
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
https://github.com/Pragya26-techie/stock-price-prediction-lstm-flask.git
cd stock-price-prediction
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the App

```bash
python app.py
```

Open browser at: **[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

## 📊 Output Visualizations

1. **Historical Close Prices**
2. **Original vs Predicted Test Data**
3. **Future Price Predictions**

All plots are dynamically generated and embedded into HTML using Base64 encoding.

---

# Limitation

* **Market Reality**:
  Stock markets are **non‑stationary** and influenced by news, sentiment, and macro‑events.

* **No Trading Strategy**:
  This app does **not** include risk management, indicators, or buy/sell signals.

---

## 🧪 Tech Stack

* Python
* Flask
* TensorFlow / Keras
* yfinance
* Pandas, NumPy
* Matplotlib
* Scikit‑learn

## 👩‍💻 Author

Built by **Pragya** as a Machine Learning portfolio project.

---


