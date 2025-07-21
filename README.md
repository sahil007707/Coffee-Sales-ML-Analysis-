# ☕ Coffee Sales Forecasting using Machine Learning

Welcome to a data science project that dives into **coffee sales trends** and builds machine learning models to **predict future sales performance**. This project combines data cleaning, EDA (exploratory data analysis), and ML modeling to create actionable insights for businesses in the coffee retail domain.

---

## 📚 Table of Contents

- [📍 Project Objective](#-project-objective)
- [📦 Dataset Overview](#-dataset-overview)
- [🔎 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [🤖 Machine Learning Pipeline](#-machine-learning-pipeline)
- [📊 Key Findings & Visuals](#-key-findings--visuals)
- [🛠️ Tools & Technologies](#-tools--technologies)
- [🚀 Future Enhancements](#-future-enhancements)
- [📁 Project Structure](#-project-structure)
- [📬 Contact & Credits](#-contact--credits)

---

## 📍 Project Objective

The primary goal of this project is to analyze historical coffee sales data and develop a **robust regression model** that can forecast future sales performance across various segments.

This analysis helps in:
- Understanding regional performance trends
- Evaluating product category sales
- Forecasting future demand to assist inventory & marketing teams

---

## 📦 Dataset Overview

The dataset includes various features related to coffee sales, such as:

- `Date` — Sales transaction date
- `Product Category` — Type of coffee product (e.g., Espresso, Cappuccino, Latte)
- `Units Sold` — Total quantity sold
- `Revenue` — Sales revenue generated
- `Region` — Geographic region of the sale
- `Profit` — Revenue after deducting costs

🧹 **Cleaning Process Included:**
- Handling missing values
- Correcting date formats and data types
- Removing outliers in sales and profit columns

---

## 🔎 Exploratory Data Analysis (EDA)

Extensive EDA was performed to derive meaningful insights from the dataset. Major highlights include:

### 💡 Insights Uncovered:

- **Best Performing Products:** Which coffee types drive the most revenue
- **Seasonality:** Identified peak seasons (e.g., winter spikes in hot drink sales)
- **Regional Demand:** Mapped sales across regions to uncover geographic trends
- **Profit Margins:** Compared profitability across product lines

### 📊 Visualization Types:

- Time series plots
- Heatmaps and pair plots
- Region-wise bar charts
- Correlation matrices

---

## 🤖 Machine Learning Pipeline

After the data was prepared, several regression models were trained to forecast **sales revenue**.

### 🔧 Preprocessing:
- Label encoding and one-hot encoding for categorical variables
- Feature scaling using StandardScaler
- Feature selection based on correlation and importance scores

### 🚀 Models Implemented:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

### 📏 Model Evaluation:

Used the following metrics to assess performance:

| Model                     | MAE   | RMSE  | R² Score |
|--------------------------|-------|-------|----------|
| Linear Regression        | High  | High  | Moderate |
| Random Forest Regressor  | Low   | Low   | 0.88     |
| XGBoost Regressor        | Best  | Best  | 0.91     |

✅ **XGBoost** gave the best results with the lowest error metrics and highest predictive power.

---

## 📊 Key Findings & Visuals

- **Cappuccino** and **Latte** generate the highest revenue
- **Northern region** consistently performs better across all months
- **Sales dip** during mid-year months and **peak during winter holidays**
- XGBoost and Random Forest models outperformed linear models significantly

> “Coffee isn't just a drink—it's data waiting to be brewed.”

---

## 🛠️ Tools & Technologies

- **Python**: Core scripting
- **Pandas & NumPy**: Data processing
- **Matplotlib & Seaborn**: Visualization
- **Scikit-learn**: ML models & metrics
- **XGBoost**: Advanced gradient boosting
- **Jupyter Notebook**: Analysis environment

---

## 🚀 Future Enhancements

- 📈 Add **time series forecasting** using models like ARIMA or Prophet
- 📍 Integrate **geospatial mapping** for regional visualization
- 🛒 Use **customer segmentation** for personalized product recommendations
- 📊 Deploy a **dashboard** with Streamlit or Dash for real-time sales analysis

---
