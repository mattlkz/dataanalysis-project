# dataanalysis-project
Credit Default Prediction is the most on-point—it puts you squarely in the credit-risk domain, shows you can wrangle “real” financial data, build risk-scoring models, and surface actionable insights for loan officers or risk teams.

Project: WalletRisk – Credit Underwriting & Fraud Alert for E-Wallet Users
📋 Objective
Build a scoring pipeline that

Ingests raw e-wallet & e-commerce transactions

Flags high-risk users for credit “whitelist” screening and potential fraud

Recommends credit limits and triggers collections workflows

🔧 Tech Stack & Data

Data storage: MySQL (or Postgres) for raw + normalized tables

Big-data ETL: PySpark to process millions of transaction records

Feature store: SQL views + Spark DataFrames for engineered metrics

Modeling:

Classification (logistic regression, RandomForest, XGBoost) for default/fraud flags

Survival analysis (CoxPH) for time-to‐default underwriting

Reporting / Dashboard: Streamlit or Tableau
