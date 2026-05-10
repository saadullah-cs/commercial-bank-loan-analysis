# 🏦 Commercial Bank Loan Portfolio Analysis & Default Prediction Pipeline

[<img width="2225" height="1471" alt="analysis_dashboard_static" src="https://github.com/user-attachments/assets/3505e6a6-c7a1-41f3-be9e-9e79f4794cf3" />
]
*Above: High-level portfolio risk dashboard highlighting default concentrations by credit score, loan amount, and application status.*

## 📌 Project Overview
An end-to-end exploratory data analysis (EDA) and statistical modeling pipeline designed to analyze a commercial bank's loan portfolio. The primary objective is to identify key drivers of loan default, engineer features for predictive modeling, and provide actionable business intelligence to reduce financial risk.

## ⚙️ Tech Stack & Methodologies
* **Languages:** Python
* **Data Processing:** `Pandas`, `NumPy`
* **Statistical Modeling:** `SciPy` (Independent T-Tests, Chi-Square, Confidence Intervals)
* **Visualization:** `Plotly` (Interactive Dashboards), `Seaborn`, `Matplotlib`
* **Engineering Techniques:** IQR Winsorization, Grouped Median Imputation, Hypothesis Testing

---

## 🚀 Key Engineering Steps

### 1. Automated Data Cleaning & Formatting
Developed robust preprocessing to handle missing values via targeted imputation, correct mixed data types, and standardize unstructured text formatting for downstream modeling.

### 2. Outlier Treatment & Variance Neutralization
[<img width="1924" height="591" alt="outlier_comparison" src="https://github.com/user-attachments/assets/8b635df6-eb0c-4933-84cf-416775bf0ae5" />
]
*Data Engineering: Applying IQR Winsorization to right-skewed loan amounts to preserve vital records while neutralizing mathematical bias.*

Instead of blindly dropping outliers (which results in a loss of valuable information), I applied Interquartile Range (IQR) detection and Winsorization to cap extreme loan amounts. This neutralizes the variance while keeping the records in the training set.

### 3. Statistical Rigor & Hypothesis Testing
[<img width="1324" height="727" alt="stat_ttest" src="https://github.com/user-attachments/assets/bee4ffa5-702b-48b3-a030-576f9d5afa7b" />
]
*Statistical Validation: Independent T-Test proving the mathematical significance of credit scores between approved and rejected applications.*

Moved beyond basic visualizations by executing strict hypothesis testing to mathematically prove the correlation between credit scores, employment types, and default rates (p < 0.05).

---

## 📊 Core Business Insights Extracted

[<img width="1744" height="877" alt="eda_heatmap_default" src="https://github.com/user-attachments/assets/1ace3a28-a5f0-4301-b1dc-d3c3b4695bd1" />
]
*Multivariate Risk Analysis: Identifying high-risk lending zones across different cities and loan categories.*

* **Credit Score Thresholds:** Customers with credit scores below 600 default at more than 2x the rate of those above 700.
* **Employment Risk:** Freelance applicants carry a statistically higher risk of default compared to salaried employees.
* **Approval Metrics:** Validated that credit score and debt-to-income (DTI) ratio are the strongest predictors of loan approval.

---

## 💻 How to View the Code
To view the full statistical breakdown, interactive Plotly charts, and the complete data cleaning pipeline, click on the `Bank_Loan_Analysis.ipynb` file in this repository. GitHub will automatically render the notebook in your browser.

---

## 📬 Let's Build Something
I am the founder and lead developer at **NexGen Builds**, specializing in automated data pipelines, MLOps, and intelligent data extraction workflows. 

Whether you need to clean a messy dataset, build a predictive model, or automate your lead generation, let's connect.
* **Email:** hello@nexgenbuilds.tech
* **LinkedIn:** [[Insert your LinkedIn profile link here](https://www.linkedin.com/in/saad-ullah-cs/)]<img width="2225" height="1471" alt="analysis_dashboard_static" src="https://github.com/user-attachments/assets/a02fd2f9-2d60-4456-9c24-728fde33aad7" />
