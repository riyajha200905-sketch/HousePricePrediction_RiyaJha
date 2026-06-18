# 🏡 House Price Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📖 Project Overview

Accurately estimating property values is a critical challenge in the real estate industry. Traditional valuation methods often rely on manual comparisons, historical pricing trends, and subjective judgment.

This project develops a machine learning-based house price prediction system capable of estimating residential property values using property characteristics such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other housing amenities.

In addition to price prediction, the project identifies the most influential factors affecting house prices through feature importance analysis.

---

## 🎯 Objectives

* Predict residential property prices using machine learning.
* Compare multiple regression algorithms.
* Evaluate model performance using industry-standard metrics.
* Identify the most influential property characteristics.
* Generate actionable business insights for real estate stakeholders.

---

## 📊 Dataset Information

| Attribute         | Value                  |
| ----------------- | ---------------------- |
| Dataset           | Housing Prices Dataset |
| Records           | 545                    |
| Original Features | 13                     |
| Missing Values    | 0                      |
| Duplicate Records | 0                      |
| Target Variable   | Price                  |

### Features

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

---

## ⚙️ Project Workflow

### 1️⃣ Data Exploration

* Dataset loading
* Structure analysis
* Missing value detection
* Duplicate record detection

### 2️⃣ Data Preprocessing

* One-Hot Encoding
* Feature selection
* Train-Test Split (80/20)

### 3️⃣ Exploratory Data Analysis

* House Price Distribution
* Correlation Heatmap
* Actual vs Predicted Prices
* Feature Importance Analysis

### 4️⃣ Machine Learning Models

* Linear Regression
* Random Forest Regressor

### 5️⃣ Model Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Model Performance

| Model             | MAE       | RMSE      | R² Score   |
| ----------------- | --------- | --------- | ---------- |
| Linear Regression | 970,043   | 1,324,507 | **0.6529** |
| Random Forest     | 1,013,969 | 1,398,116 | 0.6133     |

### 🏆 Best Model

**Linear Regression**

The Linear Regression model achieved the highest R² Score and lowest prediction error, demonstrating that housing prices in this dataset exhibit relatively strong linear relationships with the available features.

---

## 🔍 Key Findings

### Top Factors Influencing House Prices

| Rank | Feature          | Importance |
| ---- | ---------------- | ---------- |
| 1    | Area             | 46.85%     |
| 2    | Bathrooms        | 15.26%     |
| 3    | Air Conditioning | 6.02%      |
| 4    | Parking          | 5.73%      |
| 5    | Stories          | 5.71%      |

### Major Insight

Property area alone contributes nearly **47%** of the model's predictive power, making it the single most influential factor affecting residential property value.

---

## 📊 Visualizations

The project includes:

* Price Distribution Analysis
* Correlation Heatmap
* Actual vs Predicted Price Comparison
* Feature Importance Ranking

All visualizations are available in the `charts/` directory.

---

## 💡 Business Recommendations

Based on the findings:

* Prioritize property area during valuation.
* Highlight bathroom count and parking facilities in listings.
* Emphasize air conditioning and premium amenities during marketing.
* Incorporate data-driven pricing strategies to improve valuation accuracy.

---

## 📂 Project Structure

```text
HousePricePrediction_RiyaJha/

├── analysis.ipynb
├── Housing.csv
├── summary.docx
├── README.md

└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── feature_importance.png
```

## 🚀 Future Improvements

* XGBoost Implementation
* Hyperparameter Tuning
* Cross Validation
* Streamlit Web Application
* Real-Time Price Prediction Dashboard

---

## 👩‍💻 Author

**Riya Jha**

Information Technology Student
Manipal Institute of Technology

Interested in:

* Machine Learning
* Data Science
* Artificial Intelligence
* Software Development

---

⭐ If you found this project useful, consider giving it a star.
