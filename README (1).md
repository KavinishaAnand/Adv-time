# Advanced Time Series Forecasting: Prophet vs LSTM

This project compares two powerful forecasting techniques—Facebook Prophet and LSTM Neural Networks—using a synthetically generated multivariate time series dataset. It demonstrates modern forecasting workflows, model evaluation, and visualization of predictions.

## 📌 Project Features

- Generates 730 days of synthetic time series data  
- Adds multiple engineered features:
  - Temperature  
  - Humidity  
  - Holiday flag  
  - Day of week & month  
  - Trend  
  - Daily & weekly seasonality  
- Builds and trains:
  - Prophet forecasting model
  - LSTM deep learning model
- Compares prediction accuracy  
- Visualizes actual vs predicted values  

## 📁 Dataset Overview

| Column | Description |
|--------|-------------|
| ds | Date column |
| y | Target variable |
| temperature | Daily temperature |
| humidity | Daily humidity |
| holiday_flag | Holiday indicator (0/1) |
| day_of_week | Day index |
| month | Month index |
| trend | Long-term trend |
| daily_seasonality | Daily pattern |
| weekly_seasonality | Weekly pattern |

## 🧠 Models Implemented

### 1. Prophet Model
- Handles trend and seasonality automatically  
- Fast and interpretable  

### 2. LSTM Model
- Learns complex sequential patterns  
- Suitable for non-linear relationships  

## 🚀 Workflow

1. Generate synthetic dataset  
2. Preprocess data  
3. Train Prophet and LSTM models  
4. Generate forecasts  
5. Compare results  
6. Plot predictions  

## ▶️ How to Run

```bash
pip install -r requirements.txt
python adv_time.py
```

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras  
- Prophet  

## 🤝 Contributions

Feel free to fork this project or open issues for improvements.
