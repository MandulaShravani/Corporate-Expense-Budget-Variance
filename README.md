# 📊 Corporate Expense & Budget Variance Analysis | Power BI

## 📌 Project Overview

Effective budget management is essential for organizations to control expenses, allocate financial resources, and maintain financial stability. Comparing planned budgets with actual expenditure helps businesses identify overspending and understand their financial performance.

This project focuses on analyzing corporate budget and expenditure patterns using **Microsoft Power BI**. The dashboard provides insights into departmental expenses, spending categories, regional expenditure, payment methods, and budget variances.

The objective is to help organizations monitor spending patterns, identify budget overruns, and make informed financial decisions through interactive visualizations.

## 🎯 Project Objectives

- Compare total budgeted amounts with actual expenditure.
- Analyze overall budget variance and budget utilization.
- Evaluate spending patterns across different departments.
- Identify expense categories contributing significantly to expenditure.
- Compare budget and actual spending across regions.
- Analyze expenditure distribution across different payment methods.
- Monitor monthly spending trends and identify areas requiring financial attention.

## 📂 Dataset Information

- **Dataset:** Budget vs Actual Data
- **Source:** Budget_vs_Actual_Data.xlsx
- **Total Records:** 10,010
- **Original Columns:** 8
- **Period Covered:** 2021–2023
- **Domain:** Finance & Business Analytics

The dataset contains financial records including dates, departments, expense categories, regions, budget amounts, actual expenditure, payment methods, and transaction identifiers.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **Microsoft Excel** – Dataset handling and preparation

## 🧹 Data Cleaning & Transformation

The following data preparation steps were performed:

- Checked for missing values and data inconsistencies.
- Handled missing categorical values using appropriate placeholder values such as `Unknown`.
- Reviewed transaction identifiers and handled missing identifiers.
- Verified and corrected column data types.
- Created additional date-related columns for time-based analysis.
- Created Month, Month Year, and MonthYear Sort columns for chronological analysis.
- Prepared the dataset for accurate reporting and visualization.

## 📊 Dashboard Sections

### 1. Budget vs. Actual Overview
- Analysis of total budget and actual expenditure.
- Overall budget variance and budget utilization percentage.
- Department-wise actual spending distribution.
- Comparison of monthly budget and actual spending trends.
- Identification of overall budget overruns.

### 2. Departmental Expense Analysis
- Comparison of budget and actual spending across departments.
- Department-wise budget variance analysis.
- Identification of departments with the highest budget overruns.
- Analysis of departmental budget utilization.
- Comparison of actual expenditure across departments.

### 3. Expense Category & Cost Analysis
- Comparison of budget and actual expenditure across expense categories.
- Identification of high-spending expense categories.
- Analysis of actual spending distribution by category.
- Category-wise budget variance analysis.
- Comparison of budget and actual amounts at the transaction level.

### 4. Regional & Payment Analysis
- Comparison of budget and actual expenditure across regions.
- Analysis of payment method distribution across different regions.
- Comparison of spending patterns by payment method.
- Analysis of actual expenditure across payment categories.
- Examination of regional financial activity.

## 🔍 Key Insights

- Total actual spending reached approximately **891.20M**, exceeding the recorded budget of **796.11M**.
- The organization recorded an overall budget overrun of approximately **95.09M**.
- Budget utilization reached approximately **112%**, indicating that actual expenditure exceeded the allocated budget.
- All six identified departments exceeded their recorded budgets.
- **Marketing** recorded the largest departmental budget overrun of approximately **19.98M**.
- **HR** recorded the highest actual departmental spending at approximately **155.55M**.
- **Finance** recorded the smallest budget overrun among the six identified departments.
- **Travel and Utilities** were among the highest-spending expense categories.
- Salaries and Marketing also contributed substantially to overall expenditure.
- Regional and payment method analysis provided additional insights into how expenditure was distributed across geographical areas and payment methods.

## 💡 Business Recommendations

- Investigate the overall budget deficit and identify the major reasons for overspending.
- Prioritize Marketing expenses for review due to its highest departmental budget overrun.
- Examine high-spending categories such as Travel and Utilities to identify potential cost-saving opportunities.
- Introduce regular budget monitoring across all departments.
- Improve financial data quality by addressing missing values and duplicate or incomplete transaction identifiers.
- Conduct monthly budget-versus-actual reviews to identify spending deviations at an early stage.

## 📁 Project Structure

```text
Corporate-Expense-Budget-Variance-Analysis/
│
├── Dataset/
│   └── Budget_vs_Actual_Data.xlsx
│
├── Dashboard/
│   └── Corporate-Expense-Budget-Variance.pbix
│
├── CorporateExpense-video.mp4
│
└── README.md
```

## 📈 Project Outcome

This project demonstrates the application of data cleaning, data transformation, DAX calculations, and interactive visualizations to analyze corporate financial data.

It highlights how Power BI can transform raw financial records into meaningful insights, helping organizations monitor expenditure, evaluate budget performance, identify financial deviations, and support data-driven decision-making.

---

⭐ If you find this project useful, feel free to explore the repository!
