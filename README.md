# 🛒 Online Retail Sales Analysis

This project analyzes the [UCI Online Retail dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx) using **Python**, **Pandas**, and **Matplotlib** in Google Colab.  
It covers data cleaning, sales trend analysis, and visualization of top-performing countries.

---

## 📂 Dataset
The dataset contains all transactions from a UK-based online retail store between **1st Dec 2010 and 9th Dec 2011**.

**Key columns:**
- `InvoiceNo` – Invoice number (may have cancellations)
- `StockCode` – Product code
- `Description` – Product description
- `Quantity` – Quantity purchased
- `InvoiceDate` – Date of transaction
- `UnitPrice` – Price per unit (£)
- `CustomerID` – Unique customer identifier
- `Country` – Country of customer

---

## 🔍 Analysis Steps
1. **Data Loading** – Import `.xlsx` file directly from UCI.
2. **Data Cleaning** – Remove missing `CustomerID`, negative quantities, and zero/negative prices.
3. **Feature Engineering** – Create `TotalSales` column (`Quantity × UnitPrice`).
4. **Grouping & Aggregation** – Summarize sales by `Country` and by `Month`.
5. **Visualization** – Generate:
   - **Bar chart** of top 10 countries by sales.
   - **Line chart** of monthly sales trend.

---

## 📊 Sample Insights
- 🇬🇧 **United Kingdom** is the top revenue-generating country.
- Peak sales occurred in **November 2011**.
- Certain European countries show seasonal buying patterns.

---

## ▶ How to Run
**In Google Colab:**
```python
!wget https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx
```
1. Open the notebook in Colab.
2. Run all cells.
3. The dataset will be downloaded automatically.
---
## 🛠 Requirements

1. Python 3.x
2. pandas
3. matplotlib

==> Install locally:
```bash
pip install pandas matplotlib
```
📌 Author
Project by parthw04...
