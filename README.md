# Banking Fraud Analytics Project

## 📌 Overview
This project focuses on analyzing a real-world style banking transactions dataset to identify fraud patterns and risk indicators. The goal was to perform end-to-end Exploratory Data Analysis (EDA), derive fraud-related KPIs, and uncover insights that help understand fraud behavior in digital payments.

## 📊 Key Objectives
- Identify patterns in fraudulent vs non-fraudulent transactions
- Analyze transaction types, amount behavior, and card-present trends
- Build fraud KPIs to support risk teams
- Create visual insights using Python (Matplotlib + Seaborn)

## 🛠️ Tools and Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Google Colab / Jupyter Notebook**

## 📂 Dataset Details
The dataset contains fields such as:
- TransactionType  
- CardPresent  
- Country  
- Amount  
- TransactionDate  
- FraudFlag  

Includes both *fraud* and *non-fraud* transactions.

## 🔍 Analysis Performed
### ✓ Data Cleaning
- Checked nulls, duplicates, formatting issues  
- Converted dates, cleaned categorical labels  

### ✓ Exploratory Data Analysis (EDA)
- Fraud vs Non-Fraud distribution  
- High-risk transaction types  
- Card-present vs card-not-present risk  
- Cross-border transaction patterns  
- High-value fraud contribution  

### ✓ Key Metrics Created
- **Fraud Rate (%)**
- **Total Fraud Amount**
- **Average Amount of Fraud Transactions**
- **Fraud Count by Transaction Type**
- **Fraud Count by Country**
- **High-Risk Category Identification**

## 📈 Insights Summary
- Card-Not-Present (CNP) transactions show significantly higher fraud rate  
- High-value transactions contribute a large share of total fraud amount  
- Certain countries show disproportionate fraud activity  
- Night-time transactions show a spike in fraud attempts  

## 📁 Project Structure
banking-fraud-analysis/
│── data/
│── notebook/
│── images/
│── README.md
## ▶️ How to Run
1. Clone the repository  
2. Open the Jupyter/Colab notebook  
3. Run all cells to reproduce EDA and visualizations  

## 📌 Status
Completed — includes full EDA and business insights for fraud risk teams.

## 🧑‍💻 Author
Pratham Singh  
GitHub: https://github.com/singhpratham19  
