# ConnectaTel_analisis_PROJECT_7
The main objective of this project is to analyze customer behavior at ConnectaTel by exploring usage patterns, cleaning and validating telecom data, identifying customer segments, detecting outliers, and generating business insights that can help improve customer retention strategies and optimize service plans

## 🎯 Project Objective

The main objective of this project is to analyze customer behavior at ConnectaTel by exploring telecom usage patterns, cleaning and validating the datasets, identifying customer segments, detecting outliers, and generating business insights that can help improve customer retention strategies and optimize service plans.

---

## 📂 Datasets Used

This project uses three datasets:

### `plans.csv`
Contains information about telecom plans:
- monthly price,
- included minutes,
- included GB,
- extra usage costs.

### `users_latam.csv`
Contains customer information:
- age,
- city,
- registration date,
- subscribed plan,
- churn status.

### `usage.csv`
Contains historical usage records:
- calls,
- messages,
- duration,
- service usage dates.

---

## 🧹 Analysis Stages

### 1. Data Loading and Exploration
- loading datasets,
- reviewing columns and data types,
- detecting missing values.

### 2. Data Cleaning
- correcting sentinels,
- handling invalid dates,
- managing missing values.

### 3. Exploratory Data Analysis (EDA)
- descriptive statistics,
- histograms,
- boxplots,
- distribution analysis.

### 4. Outlier Detection
- identifying extreme values using IQR,
- evaluating high-usage customers.

### 5. Customer Segmentation
- segmentation by usage level,
- segmentation by age group.

### 6. Executive Insights
- business recommendations,
- customer behavior insights,
- plan optimization opportunities.

---

## ▶️ How to Run the Notebook

### Option 1: Google Colab
1. Open the `.ipynb` notebook in Google Colab.
2. Upload the datasets into the `/datasets/` folder.
3. Run the notebook cells sequentially.

### Option 2: Jupyter Notebook

Install dependencies:

```bash
pip install pandas seaborn matplotlib
