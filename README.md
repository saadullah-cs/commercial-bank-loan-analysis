# 🏦 Commercial Bank Loan Portfolio Analysis & Default Prediction Pipeline

## 📌 Project Overview
An end-to-end exploratory data analysis (EDA) and statistical modeling pipeline designed to analyze a commercial bank's loan portfolio. The primary objective is to identify key drivers of loan default, engineer features for predictive modeling, and provide actionable business intelligence to reduce financial risk.

## ⚙️ Tech Stack & Methodologies
* **Languages:** Python
* **Data Processing:** `Pandas`, `NumPy`
* **Statistical Modeling:** `SciPy` (Independent T-Tests, Chi-Square, Confidence Intervals)
* **Visualization:** `Plotly` (Interactive Dashboards), `Seaborn`, `Matplotlib`
* **Engineering Techniques:** IQR Winsorization (Outlier Treatment), Grouped Median Imputation

## 🚀 Key Engineering Steps
1. **Automated Data Cleaning:** Developed robust preprocessing to handle missing values (via targeted imputation), correct mixed data types, and standardize text formatting.
2. **Outlier Treatment:** Applied Interquartile Range (IQR) detection and Winsorization to cap extreme loan amounts without losing critical data points.
3. **Statistical Rigor:** Moved beyond basic visualizations by executing hypothesis testing to mathematically prove the correlation between credit scores, employment types, and default rates.
4. **Interactive BI:** Built interactive Plotly visualizations to allow stakeholders to explore credit score distributions vs. loan amounts across different cities.

## 📊 Core Business Insights Extracted
* **Credit Score Thresholds:** Customers with credit scores below 600 default at more than 2x the rate of those above 700.
* **Employment Risk:** Freelance applicants carry a statistically higher risk of default compared to salaried employees.
* **Approval Metrics:** Validated that credit score and debt-to-income (DTI) ratio are the strongest predictors of loan approval.

## 💻 How to View
To view the full statistical breakdown, interactive charts, and data cleaning pipeline, simply click on the `Bank_Loan_Analysis.ipynb` file above. GitHub will automatically render the notebook in your browser.
