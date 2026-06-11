# Customer Churn Analysis using Python

## Project Overview

This project focuses on analyzing customer churn behavior using Python and data analytics techniques. The objective is to identify factors influencing customer churn and discover patterns that can help businesses improve customer retention.

The dataset contains customer demographic information, subscription details, usage patterns, billing information, tenure, and churn status.

---

## Objectives

- Analyze customer churn based on age groups.
- Compare churn rates across locations.
- Study the impact of monthly usage on churn.
- Compare churned and retained customers.
- Identify high-risk customer segments.
- Calculate overall churn rate.
- Analyze churn by subscription type.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

## Dataset Description

The dataset contains 200 customer records with the following fields:

| Column Name | Description |
|-------------|-------------|
| Customer_ID | Unique customer identifier |
| Age | Customer age |
| Location | Urban, Rural, or Semi-Urban |
| Monthly_Usage_Hours | Monthly service usage hours |
| Subscription_Type | Basic, Standard, Premium |
| Monthly_Bill | Monthly subscription bill |
| Tenure_Months | Customer tenure in months |
| Churn | 0 = Retained, 1 = Churned |

---

## Project Workflow

### 1. Data Generation

- Created synthetic customer data using NumPy.
- Generated demographic and subscription information.
- Simulated churn behavior based on:
  - Low usage
  - High monthly bills
  - Short customer tenure

---

### 2. Churn Analysis by Age Group

Age groups analyzed:

- 18–25
- 26–35
- 36–45
- 46–60

Purpose:
- Identify age groups with the highest churn rate.

---

### 3. Churn Analysis by Location

Locations analyzed:

- Urban
- Rural
- Semi-Urban

Purpose:
- Compare customer retention across locations.

---

### 4. Churn Analysis by Subscription Type

Subscription plans:

- Basic
- Standard
- Premium

Purpose:
- Identify which plan experiences the highest churn.

---

### 5. Monthly Usage Impact

Usage categories:

- Low Usage (0–20 Hours)
- Medium Usage (21–50 Hours)
- High Usage (51–100 Hours)

Purpose:
- Determine how customer engagement affects churn.

---

### 6. Churned vs Retained Customer Comparison

Compared:

- Average Age
- Monthly Bill
- Monthly Usage
- Tenure

Purpose:
- Understand differences between retained and churned customers.

---

### 7. High-Risk Customer Identification

Customers classified as high-risk when:

- Monthly Usage < 20 Hours
- Monthly Bill > ₹1500
- Tenure < 6 Months

Purpose:
- Identify customers likely to churn.

---

### 8. Overall Churn Rate Calculation

Formula:

Churn Rate (%) = (Number of Churned Customers / Total Customers) × 100

Purpose:
- Measure overall customer attrition.

---

## Key Insights

- Customers with low usage show higher churn rates.
- Customers paying higher monthly bills are more likely to churn.
- Short-tenure customers are at greater risk of leaving.
- Subscription type influences churn behavior.
- Customer engagement is a critical retention factor.

---

## Business Benefits

- Improve customer retention strategies.
- Identify customers at risk of churn.
- Support targeted marketing campaigns.
- Reduce revenue loss from customer attrition.
- Enhance customer experience.

---

## Future Enhancements

- Machine Learning Churn Prediction Model.
- Customer Lifetime Value Analysis.
- Interactive Power BI Dashboard.
- Predictive Analytics using Random Forest and XGBoost.
- Automated Churn Risk Scoring.

---

## How to Run the Project

1. Install required libraries:

```bash
pip install pandas numpy
```

2. Run the Python script:

```bash
python python_task.py
```

3. Review the churn analysis results in the console output.

---

## Project Structure

```text
Customer-Churn-Analysis/
│
├── python_task.py
├── README.md
└── dataset.csv (optional)
```

---

## Author

**Nithin A**

Customer Churn Analysis Project using Python
