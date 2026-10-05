# Bank Customer Churn: Cleaning and Exploratory Analysis

A first data analytics project in Python (pandas, seaborn): clean a messy two-sheet Excel file of 10,000 bank customers and explore who churns.

**Notebook:** [`Bank_churn.ipynb`](Bank_churn.ipynb)

## Key findings

- About **20%** of customers churned.
- Churn is highest for customers aged **40-59** (56% for 50-59, against 8-11% under 40).
- **Germany** churns at about twice the rate of France and Spain (32% vs 16-17%): 25% of customers, 40% of churners.
- **1-product** customers and **inactive members** churn more than 2-product and active ones.
- Credit score, tenure and salary show no difference between churners and non-churners.

These are patterns in one snapshot, not proven causes. The messy file's `HasCrCard` column turned out to be a copy of `IsActiveMember`, so it was not trusted.

## Files

| File | Description |
|---|---|
| `Bank_churn.ipynb` | The full analysis, with a summary in section 5 |
| `Bank_Churn_Messy.xlsx` | Source data (two tabs: `Customer_Info`, `Account_Info`) |
| `Bank_Churn.csv` | Clean reference version of the data |
| `Bank_Churn_Data_Dictionary.csv` | Field definitions |
