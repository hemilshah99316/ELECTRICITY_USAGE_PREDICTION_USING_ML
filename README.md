# 🔋**TimeSeries Forecasting of Electricity Consumption** ⚡

### Predicting Future Energy Demand using Machine Learning 🚀

![XGBoost](https://img.shields.io/badge/Algorithm-XGBoost-blue)
![Forecasting](https://img.shields.io/badge/Forecasting-Time%20Series-orange)
![Python](https://img.shields.io/badge/Language-Python-green)
![Jupyter Notebook](https://img.shields.io/badge/Environment-Jupyter%20Notebook-lightgrey)

## 📝 **Project Overview**

This project utilizes **Time Series Forecasting** techniques to predict **electricity consumption** using the **XGBoost** algorithm. The dataset contains **hourly electricity usage** from PJM West, which is used to train the model. Through **feature engineering** and **hyperparameter tuning**, I have aimed to create an accurate model that forecasts future electricity demand.

---

## 📁 **Dataset Overview**

The dataset consists of hourly electricity consumption values over time. Here's a small sample:

| **Datetime**       | **PJME_MW** |
|--------------------|-------------|
| 12/31/2002 1:00    | 26498       |
| 12/31/2002 2:00    | 25147       |
| 12/31/2002 3:00    | 24574       |
| 12/31/2002 4:00    | 24393       |
| 12/31/2002 5:00    | 24860       |

#### **Feature-Engineered Data**
After feature engineering, the dataset looks like this:

| **Feature**    | **Data Type**  |
|----------------|----------------|
| Datetime       | `datetime64[ns]` |
| PJME_MW        | `float64`      |
| Year           | `int32`        |
| DayOfMonth     | `int32`        |
| Month          | `int32`        |
| Hour           | `int32`        |
| DayOfWeek      | `int32`        |
| DayOfYear      | `int32`        |
| Quarter        | `int32`        |

---

## 🧠 **Modeling**

### **Algorithm Used**:
- **XGBoost Regressor** For Time Series Forecasting.
- **Hyperparameter Tuning** using **RandomizedSearchCV** to optimize model performance.

## 📊 **Visualization & Insights**

Some of the charts used in this analysis:

- **Actual vs Predicted Consumption** 📉
- **Electricity Consumption Trend Over Time** 🕒
- **Residuals of Predictions** 🧮

---

## ⚙️ **Future Work** & **Improvements**

- **Additional Features**: Incorporate **weather forecasts**, **holiday data**, and other external factors.
- **Model Comparisons**: Test other machine learning algorithms such as **LSTM** or **ARIMA**.
- **Refinement of Hyperparameters**: Use **GridSearchCV** for more exhaustive hyperparameter optimization.

---

## 🏆 **Conclusion**

By leveraging **XGBoost** and robust **feature engineering**, we successfully predicted future electricity consumption. This model can serve as a valuable tool for planning electricity demand and supply management.

---

## 🚀 **Getting Started**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hemilshah99316/ELECTRICITY_USAGE_PREDICTION_USING_ML.git
   ```
   OR
   Download ZIP File
   
2. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook forecasting.ipynb
   ```

---
