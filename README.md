# FBI Crime Forecasting

## 📌 Overview

The FBI Crime Forecasting project leverages machine learning and time series techniques to predict monthly crime incident counts across various crime categories. The goal is to assist law enforcement and city planners in anticipating crime patterns, improving resource allocation, and enhancing public safety.

---

## 🎯 Problem Statement

Law enforcement agencies face increasing difficulty in responding to dynamic crime trends across urban areas. This project addresses that challenge by developing a predictive model that estimates the number of monthly crime incidents using historical spatial and temporal data.

---

## 🧠 Technologies Used

- **Python**
- **Pandas, NumPy** – Data processing
- **Matplotlib, Seaborn** – Visualization
- **XGBoost** – Predictive modeling
- **Scikit-learn** – Evaluation metrics
- **Statsmodels (SARIMAX)** – Time series forecasting
- **Jupyter Notebook** – Analysis environment

---

## 📂 Project Structure

- `data/` – Contains training and testing datasets.
- `notebooks/` – Jupyter notebook with full code and analysis.
- `outputs/` – Contains predicted test set results.
- `visuals/` – (Optional) Exported plots for EDA and insights.
- `requirements.txt` – Python dependencies.

---

## 📊 Key Steps

1. **Data Preprocessing**
   - Cleaning, datetime parsing, aggregation by month and crime type.

2. **Exploratory Data Analysis**
   - Crime trends by month/year/type.
   - Heatmaps, line plots for seasonality.

3. **Model Building**
   - XGBoost Regressor
   - SARIMAX Time Series Model

4. **Evaluation**
   - Root Mean Squared Error (RMSE): `~48.95` for XGBoost model.

5. **Prediction**
   - Forecasted monthly crime incident counts saved in `Predicted_Crime_Incidents.csv`.

---

## 📈 Results & Insights

- Crimes exhibit clear monthly trends and category-specific patterns.
- The model helps identify high-risk crime periods and informs patrol scheduling.
- Insights aid in targeted safety infrastructure and policy decisions.

---

## ✅ Future Improvements

- LSTM or Prophet for improved time series forecasting.
- Hyperparameter tuning and cross-validation.
- Geospatial heatmap clustering for hotspot prediction.

---


## 📥 Installation

To install the required packages:

```bash
pip install -r requirements.txt
