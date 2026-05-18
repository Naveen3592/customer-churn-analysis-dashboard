# Customer Churn Analysis Dashboard

## Project Overview

This project focuses on analyzing customer churn behavior in a telecommunications company using Power BI. The dashboard provides insights into customer demographics, churn trends, contract analysis, payment methods, and internet service usage to help businesses reduce customer attrition and improve retention strategies.

The project was developed as part of a Power BI Internship Program and demonstrates practical dashboard development, business intelligence, and data visualization skills.

---

## Business Problem Statement

Customer churn is a major challenge for telecom companies because losing customers directly impacts revenue and business growth. Identifying churn patterns helps organizations improve customer satisfaction, optimize services, and reduce customer loss.

This project analyzes customer behavior and highlights factors contributing to customer churn.

---

## Project Objectives

- Analyze customer churn patterns
- Identify high-risk customer segments
- Visualize customer demographics
- Understand churn by contract type
- Analyze churn by payment method
- Explore internet service impact on churn
- Build interactive Power BI dashboards
- Generate business recommendations

---

## Tools and Technologies Used

| Tool | Purpose |
|------|----------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning |
| DAX | KPI Calculations |
| CSV Dataset | Data Source |
| Data Visualization | Business Insights |

---

## Dataset Information

The dataset contains telecom customer information including:

- Customer ID
- Gender
- Partner Status
- Dependents
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Senior Citizen Status
- Customer Tenure
- Churn Status

---

## Data Cleaning and Transformation

The dataset was cleaned and transformed using Power Query.

### Data preprocessing steps:
- Handled missing values
- Standardized categorical values
- Verified data consistency
- Created calculated measures
- Optimized data types

---

## Dashboard KPIs

The dashboard includes the following KPI metrics:

| KPI | Value |
|-----|------|
| Total Customers | 7043 |
| Churned Customers | 1869 |
| Churn Rate | 26.54% |

---

## Dashboard Features

### 1. Customer Demographics Analysis
Visualizations:
- Gender Distribution
- Partner Status
- Dependent Status

### 2. Customer Tenure Distribution
- Histogram-style visualization
- Customer retention duration analysis

### 3. Churn by Contract Type
Analysis of:
- Month-to-Month Contracts
- One-Year Contracts
- Two-Year Contracts

### 4. Churn by Internet Service
Comparison of churn across:
- Fiber Optic
- DSL
- No Internet Service

### 5. Churn by Payment Method
Analysis based on:
- Electronic Check
- Mailed Check
- Bank Transfer
- Credit Card

---

## Key Insights

### Major Findings

- Month-to-month contract customers show the highest churn rate
- Customers using Fiber Optic internet have higher churn percentages
- Electronic check users are more likely to churn
- Long-term contracts significantly reduce churn
- Customer tenure strongly impacts retention

---

## Business Recommendations

- Promote long-term contract plans
- Improve Fiber Optic customer experience
- Offer retention discounts for high-risk customers
- Encourage automated payment methods
- Create loyalty programs for new customers

---

## Dashboard Preview

### Main Dashboard

![Dashboard](assets/dashboard.png)

---

## Project Structure

```text
customer-churn-analysis-dashboard/
│
├── assets/
├── data/
├── powerbi/
├── reports/
├── README.md
└── requirements.txt
```

---

## Files Included

| File | Description |
|------|-------------|
| customer_churn_analysis.pbix | Power BI Dashboard |
| Telco_Customer_Churn_Cleaned_Dataset.csv | Cleaned Dataset |
| dashboard.png | Dashboard Screenshot |
| SKS_PowerBI_Task.pdf | Internship Task Document |

---

## Power BI Skills Demonstrated

- Data Modeling
- Data Cleaning
- Power Query Transformation
- DAX Measures
- KPI Cards
- Interactive Visualizations
- Dashboard Design
- Business Intelligence Reporting

---

## DAX Measures Used

Examples of measures created:

```DAX
Total Customers = COUNT(customerID)

Churned Customers =
CALCULATE(
    COUNT(customerID),
    Churn = "Yes"
)

Churn Rate =
DIVIDE([Churned Customers], [Total Customers]) * 100
```

---

## Internship Task Details

The project was developed based on Power BI internship tasks including:

- Data Importing
- Data Cleaning
- Dashboard Development
- Churn Analysis
- Customer Demographics Visualization
- Customer Tenure Analysis

Based on internship documentation:
:contentReference[oaicite:1]{index=1}
:contentReference[oaicite:2]{index=2}

---

## Learning Outcomes

This project improved practical skills in:

- Power BI Dashboard Development
- Business Intelligence
- Data Visualization
- Customer Analytics
- KPI Reporting
- Data Transformation
- DAX Calculations

---

## Future Improvements

- Machine Learning Churn Prediction
- Real-Time Dashboard Integration
- Predictive Analytics
- Customer Segmentation Models
- AI-Based Retention Recommendations

---

## Author

### Dorraju Naveen Raju

Data Analyst | Power BI | SQL | Python | Excel

LinkedIn: Add Your LinkedIn Link  
GitHub: Add Your GitHub Link

---

## License

This project is developed for educational and portfolio purposes.
