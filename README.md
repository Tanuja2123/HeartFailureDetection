# Credit Risk Exploratory Data Analysis (EDA)

This project explores a credit-related dataset to understand customer behavior, loan repayment trends, and risk factors. The goal of this EDA is to derive insights from the data that can help financial institutions in making informed decisions about loan approvals and risk management.

## 📊 Objective

- Understand the distribution and correlation of features affecting credit risk.
- Analyze patterns in customer defaults and repayment behavior.
- Identify potential indicators of creditworthiness.

## 🧾 Dataset Overview

The dataset includes customer demographic and financial information, along with repayment behavior. Typical features may include:

- **Customer ID**
- **Age**
- **Gender**
- **Education**
- **Marital Status**
- **Limit Balance (Credit Limit)**
- **Payment History**
- **Bill Amounts**
- **Previous Payments**
- **Default Payment (Target variable)**

> Note: Exact feature names depend on the specific dataset structure used in the notebook.

## 🔍 EDA Highlights

- **Missing value analysis**
- **Univariate & bivariate analysis**
- **Correlation matrix and heatmap**
- **Distribution of default vs. non-default customers**
- **Boxplots and barplots for categorical vs numerical relationships**
- **Insights on how factors like education, age, and repayment history affect default rate**

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (optional for interactive visualizations)

## 🚀 Getting Started

### Requirements

```bash
pip install pandas numpy matplotlib seaborn plotly

📈 Key Findings
Younger customers and those with lower education levels show a higher tendency to default.

Strong correlations found between previous payment history and likelihood of default.

Limit balance and bill amount distributions vary widely across customer segments.

📝 Conclusion
The EDA provides a strong foundation for building a predictive model for credit default. It reveals key risk indicators and helps refine feature selection for future modeling.
