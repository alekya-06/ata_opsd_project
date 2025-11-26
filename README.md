⚡ OPSD PowerDesk: Day-Ahead Load Forecasting
📋 Project Overview
Complete implementation of a day-ahead electric load forecasting system for three European countries (AT, CH, FR) with anomaly detection and online adaptation.

🎯 Features
1. Forecasting: SARIMA, LSTM, GRU models (24-hour ahead)
2. Anomaly Detection: Z-score + ML classification
3. Online Adaptation: LSTM tiny neural fine-tune
4. Dashboard
5. Analysis: STL decomposition, ACF/PACF, model comparison

📁 Repository Structure
opsd-powerdesk/
├── OPSD_PowerDesk.ipynb          # Main Colab notebook
├── outputs/                      # Generated artifacts
│   ├── EDA/               # Plots used for EDA
│   ├── Forecasts and Backtesting/     # validation and test forecasts 
│   ├── live_adaptation/         # Live adaption logs + images
│   └── dashboard/                   # dashboard images
└── README.md


Dashboard: Live monitoring interface

