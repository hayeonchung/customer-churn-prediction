# customer-churn-prediction
Predicting customer churn using R (telecom dataset)
# Customer Churn Analysis (R)

This project uses real-world customer data to build a churn prediction model using R. The goal is to identify which customers are most likely to stop using the service and why.

---

## Project Overview

- **Objective**: Predict customer churn using logistic regression and random forest models
- **Dataset**: Telco Customer Churn dataset
- **Tools**: R, tidyverse, caret, DALEX, ggplot2
- **Key Techniques**: Feature engineering, classification modeling, model explainability

---

## Files Included

| File | Description |
|------|-------------|
| `Customer-Churn-Analysis-Project.Rmd` | Source code in R Markdown |
| `Customer-Churn-Analysis-Project.html` | Interactive HTML report |
| `Customer-Churn-Analysis-Project.pdf` | Printable PDF report |
| `README.md` | This project overview |

---

## Key Findings

- **Contract Type**: Month-to-month customers have the highest churn rates.
- **Tenure & Charges**: Short tenure and high monthly charges are strong indicators of churn.
- **Support Services**: Customers lacking tech support and security add-ons churn more often.

---

## Business Recommendations

- Offer loyalty discounts to month-to-month subscribers.
- Create bundles with tech support to retain high-risk customers.
- Target early-tenure customers with onboarding incentives.

---

## Next Steps

- Try alternative models like XGBoost
- Perform hyperparameter tuning
- Deploy the model as a dashboard with Shiny

---

