# 📈 Stock Price Prediction using LSTM

This project uses an LSTM (Long Short-Term Memory) neural network to predict the future stock prices of Netflix based on historical data from March 2019 to March 2022.

## 🔍 Problem Statement

Stock prices are highly volatile and affected by numerous factors. This project aims to predict closing stock prices using historical data, focusing on modeling time dependencies via LSTM.

## 🧠 Key Concepts

- Time Series Analysis
- Data Normalization
- LSTM Neural Networks
- Evaluation Metrics (RMSE, MAPE)

## 📁 Dataset

- Source: Yahoo Finance (Netflix: `NFLX`)
- Period: March 2019 – March 2022
- File: `Netflix_Dataset.csv`

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Matplotlib
- TensorFlow/Keras
- Scikit-learn

## 📊 Model Overview

- **Model**: LSTM Neural Network
- **Input**: Past 60 days' closing prices
- **Output**: Next day's predicted price
- **Loss**: Mean Squared Error
- **Optimizer**: Adam

## 🖼️ Results

![Prediction Graph](outputs/predictions.png)

## 📈 RMSE Score

```text
RMSE: [insert value here]
```

## 📁 Repository Structure
```css
Copy code
📦 stock-price-prediction-lstm
│
├── 📄 README.md
├── 📄 requirements.txt
├── 📁 data
│   └── Netflix_Dataset.csv
├── 📁 notebooks
│   └── stock_price_prediction.ipynb
├── 📁 src
│   └── model.py
│   └── utils.py
├── 📁 outputs
│   └── predictions.png
 ```

---

## 📌 Future Improvements
-Add technical indicators as features (e.g., RSI, MACD)

-Use Dropout for regularization

-Try other models like GRU, Transformer, or Prophet

---

## 📄 License
MIT License

