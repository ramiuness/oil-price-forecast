# Oil Price Forecasting with Deep Learning

Forecasting short-term oil prices is a critical challenge in energy economics, with implications for trading, policy, and risk management. This project demonstrates the use of deep learning—specifically Long Short-Term Memory (LSTM) networks—to model and forecast crude oil returns using macro-financial indicators.

The pipeline integrates multiple data sources, applies robust preprocessing and feature engineering, and builds a predictive model optimized for capturing temporal dependencies in financial time series.

---

## Contents

- **Notebook**: A Jupyter notebook that walks through the full pipeline—from data collection and transformation to model training and evaluation.
- **Feature Engineering**: Includes log returns, volatility metrics, and lag structures crafted from macroeconomic indicators.
- **Modeling**: Sequence-to-one prediction using LSTM layers trained on windowed time series data.
- **Evaluation**: Multi-horizon forecasts visualized alongside realized returns and prices; metrics include RMSE, MAE, and R².

---

## 🛠 Tools & Technologies

### 🖥️ Language  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

### 📈 Data Sources  
![Yahoo Finance](https://img.shields.io/badge/Yahoo%20Finance-6001D2?logo=yahoo&logoColor=white)  
![FRED API](https://img.shields.io/badge/FRED-003057?logo=fred&logoColor=white)  
![EIA API](https://img.shields.io/badge/EIA%20API-005f73?logo=usenergy&logoColor=white)

### 🔍 Modeling  
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)  
![LSTM](https://img.shields.io/badge/LSTM-Recurrent%20Neural%20Network-orange)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-f7931e?logo=scikit-learn&logoColor=white)

### 📊 Data & Visualization  
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=matplotlib&logoColor=white)  
![Seaborn](https://img.shields.io/badge/Seaborn-008080?logo=python&logoColor=white)

### 📓 Notebook  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/oil-price-forecasting.git
   cd oil-price-forecasting
