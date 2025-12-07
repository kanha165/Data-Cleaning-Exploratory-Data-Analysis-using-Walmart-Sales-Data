# 📊 Walmart Sales Data – Data Cleaning & Exploratory Data Analysis (EDA)

This project focuses on cleaning, preprocessing, and analyzing the **Walmart Sales Dataset** sourced from Kaggle.  
The goal of this project is to transform raw, unstructured data into a clean, analysis-ready dataset and extract meaningful insights that can be used for future Machine Learning models.

---

## 📁 Dataset
**Walmart Sales Forecasting Dataset**  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast

The dataset contains:
- Store-wise weekly sales  
- Holiday information  
- Temperature  
- Fuel price  
- CPI  
- Unemployment rate  
- Date-wise records  

---

## 🎯 Project Objectives
- Clean missing and inconsistent data  
- Handle duplicates  
- Convert and format date fields  
- Perform Exploratory Data Analysis (EDA)  
- Understand sales trends over time  
- Study impact of holidays and economic factors  
- Prepare the dataset for ML model development  

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas** – Data cleaning  
- **NumPy** – Numerical operations  
- **Matplotlib** – Visualizations  
- **Seaborn** – Advanced EDA plots  
- **Jupyter Notebook**

---

## 🧹 Data Cleaning Steps

### ✔ Handling Missing Values
- Filled missing values in `Fuel_Price`, `CPI`, and `Unemployment` using **median**  
- Filled categorical missing values with fallback labels  
- Confirmed no remaining missing values using heatmap  

### ✔ Formatting & Conversion
- Converted `Date` column into `datetime` format  
- Sorted dataset by date  
- Created new features:
  - **Year**
  - **Month**
  - **Week**

### ✔ Removing Duplicate Records
Ensured dataset integrity by dropping all duplicate entries.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 1. Correlation Heatmap  
Shows relationships between Weekly Sales and economic factors such as Fuel Price, CPI, Unemployment.

### 🔹 2. Weekly Sales Trend  
A time-series visual representing Walmart’s sales patterns over weeks.

### 🔹 3. Monthly Sales Trend  
Highlights seasonal sales patterns across months.

### 🔹 4. Store-wise Sales Comparison  
Displays which stores perform the best and worst on average.

### 🔹 5. Fuel Price vs Weekly Sales (Scatter Plot)  
Shows insight into fuel price's influence on consumer spending.

---

## 📈 Sample Visuals
(Add your graphs in an /images folder)

```
images/
 ├── heatmap.png
 ├── weekly_trend.png
 ├── monthly_trend.png
 ├── store_comparison.png
 ├── fuel_vs_sales.png
```

---

## 🧠 Key Insights
- Certain stores consistently generate significantly higher sales  
- Holiday weeks show strong spikes in weekly sales  
- Fuel Price has a mild effect on sales but is not a strong predictor  
- Economic factors like CPI & Unemployment correlate with sales behavior  
- Sales show seasonal patterns with peaks in certain months  

---

## 🚀 Future Work
- Build Machine Learning models for sales prediction  
  - Linear Regression  
  - Random Forest  
  - XGBoost  
- Hyperparameter tuning  
- Feature engineering for improved accuracy  
- Deploying the model as an API or dashboard  

---

## 👨‍💻 Author
**Kanha Patidar**  
Intern AI/ML Engineer  
Technorizen Software Solution Pvt. Ltd., Indore  

GitHub: https://github.com/kanha165  
LinkedIn: https://www.linkedin.com/in/kanha-patidar-837421290/
---

## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!
