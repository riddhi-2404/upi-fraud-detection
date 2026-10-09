# UPI Fraud Detection using Machine Learning

Minor project (B.Tech 4th year): detecting fraudulent UPI-style
transactions using Python, XGBoost, SHAP, SQLite and Streamlit.

## Dataset
PaySim synthetic financial dataset (Kaggle). Not included in this
repo due to size. Download it and save as `data/paysim.csv`.

## Key findings so far (EDA)
- Fraud is only ~0.13% of transactions (8,213 of 6,362,620)
- Fraud occurs only in TRANSFER and CASH_OUT transactions
- 97.8% of fraud transactions empty the sender's entire balance
- The old rule-based flag caught only 16 of 8,213 frauds

## Status
Work in progress.