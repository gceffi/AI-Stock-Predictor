# AI-Stock-Predictor  
**Stock Market Prediction Using Deep Learning**

## Project Overview  
This project applies deep learning models to predict future stock prices based on historical time-series data sourced from Yahoo Finance. By leveraging models like **SimpleRNN** and **CNN**, we aim to capture both long-term dependencies and short-term patterns in stock movements.

The goal is to explore different architectures, evaluate their performance, and identify the most effective modeling approach for stock forecasting using metrics like **MSE** and **R² Score**.

---

## 🔧 Models Implemented
- **SimpleRNN**  
  - Uses sequence of past prices to predict the next-day price  
  - Stable training with good generalization  
- **CNN**  
  - Uses 1D convolution layers to capture local trends  
  - Shows higher precision in short-term forecasting

---

## Tools Used
- Python, Pandas, NumPy
- TensorFlow/Keras
- Scikit-learn
- Yahoo Finance API (`yfinance`)

---

## Authors
- Godswill Effi
- Andy Nguyen
- Tsz Kan Ho