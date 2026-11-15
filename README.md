# My-project
End-to-end Python workflow for scraping, cleaning, and analyzing retail sales and customer behavior data.

## PROJECTS 1

### Customer Churn Analysis \| Python, SQL, Pandas, Seaborn, MySQL

- Analyzed 7,043 telecom customer records to identify retention and churn patterns.
- Performed data cleaning, exploratory data analysis, and statistical summarization using Python and Pandas.
- Developed SQL queries to evaluate customer behavior, contract types, and churn risk.
- Created visualizations showing churn distribution, contract\-based churn trends, and monthly charge patterns.
- Generated business recommendations to improve customer retention and reduce customer attrition.
- Published project documentation, code, SQL queries, and visualizations on GitHub.



# Customer Churn Analysis using Python and SQL

## Project Overview

Customer retention is a key business challenge in the telecommunications industry. This project analyzes customer churn patterns using the IBM Telco Customer Churn dataset to identify factors associated with customer attrition and customer retention.

The analysis includes:

- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Customer churn visualization
- Customer contract analysis
- Monthly charge analysis
- SQL\-based business queries

---

## Dataset

**IBM Telco Customer Churn Dataset**

- Records: 7,043 customers
- Features: 21 customer attributes
- Target Variable: Churn (Yes/No)

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL
- Jupyter Notebook
- GitHub

---

## Data Cleaning

### Tasks Performed

- Loaded the customer churn dataset into Pandas.
- Inspected column types and dataset structure.
- Converted TotalCharges from text to numeric format.
- Handled missing values using median imputation.
- Verified dataset quality before analysis.

---

## Exploratory Data Analysis

### 1\. Customer Churn Distribution

Results:

| Churn Status | Customers |
| --- | --- |
| No | 5,174 |
| Yes | 1,869 |

### Insight

Approximately **26.5% of customers churned**, while **73.5% remained with the company**.

This indicates that roughly one out of every four customers left the service.

---

### 2\. Churn by Contract Type

The analysis revealed that customers on **Month\-to\-Month contracts** are significantly more likely to churn compared to customers on One\-Year or Two\-Year contracts.

### Business Insight

Long\-term contracts improve customer retention and reduce churn risk.

---

### 3\. Monthly Charges Analysis

A boxplot comparison between churned and non\-churned customers shows that customers with higher monthly charges tend to leave more frequently.

### Business Insight

High service costs may contribute to customer attrition.

---

## SQL Analysis

Example SQL Query:

SELECT Churn,

       COUNT(\*) AS Customers

FROM wa\_fn\_usec

GROUP BY Churn;

Result:

| Churn | Customers |
| --- | --- |
| No | 5174 |
| Yes | 1869 |

---

## Key Findings

1. Total Customers: 7,043
2. Churned Customers: 1,869
3. Churn Rate: 26.5%
4. Month\-to\-Month contracts have the highest churn risk.
5. Customers with higher monthly charges are more likely to churn.
6. Customer retention improves with longer contract durations.

---

## Business Recommendations

- Encourage customers to move from Month\-to\-Month contracts to Annual Contracts.
- Provide retention incentives for high\-risk customers.
- Monitor customers with high monthly charges.
- Develop customer loyalty programs to improve retention.

---

## Project Outcome

This project demonstrates practical applications of:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Customer Analytics
- SQL Query Development
- Business Insight Generation

The project helps identify key drivers of customer churn and provides data\-driven recommendations for improving customer retention.

