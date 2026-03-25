# Telco Customer Churn Analysis
### Understanding Why Customers Leave - And What To Do About It

--- 

## Overview
According to Harvard Business Review, acquiring a new customer is anywhere from five to 25 times more expensive than retaining an existing one. Yet, 1 in 4 customers in this dataset are leaving. This project investigates why - uncovering five behavioral and account-level patterns that reliably predict churn across 7,032 telecom customers.

---

## Business Question
What customer behaviors and account characteristics predict churn, and which segments are most at risk of leaving?

---

## Data Source
- **Dataset:** IBM Telco Customer Churn Dataset
- **Source:** Kaggle
- **Size:** 7,032 customer records
- **Features:** 21 variable including account details, sucription services, and churn label.

--- 

## Tools and Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- GitHub

---

## Key Findings
1. **26.58% overall churn rate** - 1 in 4 customers are leaving.
2. **Contract type is the stronges predictor** - Month-to-month customers churn at 24.71% vs just 2.85 % for two-year customers.
3. **Electronic check customers are highest risk** - Churning at 45.29%, nearly 3x higher than automatic payment customers.
4. **Online security is the biggest ervice gap** - Customers without it  churn at 41.78% vs 14.64% with it - a 27 percentage point difference.
5. **Senior citizens are undeserved** - Churning at 41.68% nearly double the rate of non-senior customers.
6. **First 12 months are the danger zone** — New customers 
   churn at 42.13%, dropping to just 9.51% after 4+ years
7. **Gender has no meaningful effect** — Less than 1% 
   difference between male and female churn rates
8. **Streaming slightly reduces churn** — Streaming 
   customers churn 3-4% less than non-streaming customers

---

## Recommendations

1. **Incentivise longer contracts during onboarding** — 
   Discounts or rewards for annual commitments
2. **Migrate electronic check customers to automatic 
   payments** — Fastest potential retention win
3. **Promote protective services during onboarding** — 
   Online security, tech support, and backup adoption 
   dramatically reduces churn
4. **Build a senior citizen retention programme** — 
   Simplified tiers, proactive support, dedicated helpline
5. **Prioritise the first 12 months** — Structured 90-day 
   onboarding journey to drive early engagement and loyalty

---

## Project Structure
```
telco-churn-analysis/
├── data/
│   ├── raw/          ← Original dataset
│   └── cleaned/      ← Cleaned dataset
├── code/             ← Google Colab notebook (.ipynb)
├── visuals/          ← All 5 charts (PNG)
├── docs/             ← Full case study (PDF)
└── README.md
```

---

## Key Visualizations

### Overall Churn Rate
![Chart 1](visuals/chart1_overall_churn.png)

### Churn Rate by Contract Type
![Chart 2](visuals/chart2_contract_churn.png)

### Churn Rate by Customer Tenure
![Chart 3](visuals/chart3_tenure_churn.png)

### Churn Rate by Payment Method
![Chart 4](visuals/chart4_payment_churn.png)

### Impact of Online Security on Churn
![Chart 5](visuals/chart5_security_churn.png)

---

## Author
**Gospel I. Arinze**
[**LinkedIn**](https://www.linkedin.com/in/gospel-arinze-55590424a/) | [**Email**](gospelarinze2022@gmail.com)
