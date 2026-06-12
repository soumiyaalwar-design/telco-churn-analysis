# Telco Customer Churn Analysis

## Business Problem
A telecom company is losing ~26.6% of customers annually.
This project identifies who churns, why, and which factors drive churn —
so the business can take targeted action to retain customers.

## Key Findings
- Month-to-month contracts have a **43% churn rate** vs just 3% for 2-year contracts
- New customers in their **first 12 months** are the highest risk group (~49% churn)
- **Fiber optic** users churn at 2x the rate of DSL users
- Churned customers pay **~$10 more per month** on average
- **Electronic check** payment users have the highest churn rate of all payment methods
- The business loses **$139,131/month** in revenue due to churn

## Dashboard Preview
![Dashboard](Telco_Churn_Dashboard.pdf)

## Tools Used
- **Python** — pandas, seaborn, matplotlib, scikit-learn
- **Power BI** — interactive dashboard with DAX measures
- **Google Colab** — development environment

## Project Structure
| File | Description |
|------|-------------|
| `Telco_Churn_Analysis.ipynb` | Full analysis notebook |
| `churn_cleaned.csv` | Cleaned dataset |
| `Telco_Churn_Dashboard.pdf` | Power BI dashboard export |
| `*.png` | EDA charts |

## Model Performance
- Algorithm: Logistic Regression
- Accuracy: ~80%
- Key churn drivers: Contract type, tenure, internet service, monthly charges

## Dataset
IBM Telco Customer Churn Dataset — 7,032 customers, 20 features
Source: [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
