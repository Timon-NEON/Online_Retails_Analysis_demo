# 📊 Online Retail Data Analysis

## 📌 Overview

This project explores transactional data from a UK-based online retail company. The goal is to analyze purchasing behavior, identify patterns, and extract meaningful business insights.

The dataset covers the period from **December 2010 to December 2011** and includes information about products, customers, transactions, and countries.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Explore customer purchasing behavior
* Identify key sales patterns
* Analyze cancellations and anomalies
* Generate actionable business insights

---

## 📂 Dataset

* Source: UCI Machine Learning Repository
* Contains ~500,000 transactions
* Features include:

  * `InvoiceNo`
  * `StockCode`
  * `Description`
  * `Quantity`
  * `InvoiceDate`
  * `UnitPrice`
  * `CustomerID`
  * `Country`

---

## 🧹 Data Cleaning

Key steps:

* Handled missing values (notably in `CustomerID`)
* Identified negative quantities as **returns**
* Filtered invalid or suspicious transactions
* Created a clean dataset for analysis

---

## ⚙️ Feature Engineering

* Created **Revenue** column:

  ```
  Revenue = Quantity × UnitPrice
  ```
* Analyzed and created marker regarding transaction success **Valid** column  

---

## 📈 Key Insights

### 🕒 Time Patterns

* Peak purchasing hours: **12:00 – 15:00**
* Suggests optimal timing for promotions and campaigns

### 🌍 Country Distribution

* **91% of transactions come from the UK**
* Indicates strong market concentration
* Opportunity for international expansion

### ❌ Cancellation Analysis

* Some countries (e.g., USA) show high cancellation rates
* May indicate logistical or customer experience issues

### 👤 Customer Behavior

* Identified a group of customers with unusually high cancellation rates
* Potential fraud or abnormal purchasing patterns

### 📦 Top products

* Identified products with the highest combined revenue
* May be useful for choosing product partners

---

## 📊 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn

---

## 📁 Project Structure

```
├── .gitignore
├── LICENSE
├── Online Retail.xlsx
├── Online_Retails_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:

   ```
   git clone https://github.com/Timon-NEON/Online_Retails_Analysis_demo.git
   ```
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```
   jupyter notebook
   ```

---

## 💡 Future Improvements

* Add time-series analysis (monthly revenue trends)
* Build customer segmentation (RFM analysis)
* Apply machine learning for prediction (e.g., churn or returns)

---

## 🙌 Author

Created as a first step of a data science learning journey and portfolio project by [Kyrylenko Tymofii](https://www.linkedin.com/m/in/tymofii-kyrylenko-127803291/)

---

## 🧾 License

[MIT](https://choosealicense.com/licenses/mit/)
