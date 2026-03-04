# 📊 Energy Consumption Forecasting in Office Buildings

## 📌 Project Overview

This project focuses on predicting **energy consumption in an office environment** using **time series analysis** and **machine learning models**.

The goal is to build and compare different forecasting approaches to improve energy efficiency and support smarter energy management strategies.

---

## 🎯 Objectives

- Perform **Exploratory Data Analysis (EDA)**
- Apply time series decomposition
- Engineer meaningful temporal features
- Train statistical and machine learning models
- Compare model performance using standard metrics
- Identify the most accurate forecasting approach

---

## 🗂 Dataset

The dataset contains historical energy consumption measurements recorded over time in an office building.

### Key Characteristics

- Timestamped energy usage data  
- Time-based seasonal patterns  
- Daily and weekly consumption cycles  

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

- Datetime conversion  
- Missing value handling  
- Feature scaling  
- Resampling (if applicable)  

### 2️⃣ Feature Engineering

- Hour, day, month extraction  
- Day of week encoding  
- Lag features  
- Rolling statistics  

### 3️⃣ Time Series Analysis

- Trend and seasonality decomposition  
- Visualization of temporal patterns  

### 4️⃣ Models Implemented

- Baseline Model (Naive Forecast)  
- ARIMA / SARIMA  
- Linear Regression  
- Random Forest  
- Gradient Boosting (if applicable)  

---

## 📏 Evaluation Metrics

Models were evaluated using:

- **MAE** — Mean Absolute Error  
- **RMSE** — Root Mean Squared Error  
- **R² Score** — Coefficient of Determination  

---

## 📊 Results

The comparison shows that:

- Feature engineering significantly improves predictive performance  
- Energy consumption exhibits strong seasonal behavior  
- Machine learning models can outperform traditional statistical models when sufficient features are included  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Statsmodels  

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Cross-validation for time series  
- Deep learning models (LSTM, GRU)  
- Deployment as an energy monitoring dashboard  

---

## 👤 Author

**Energy Data Analysis & Time Series Forecasting Project**  
Focused on predictive modeling for smart energy management.
