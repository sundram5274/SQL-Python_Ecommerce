# SQL-Python_Ecommerce
# 🛒 Ecommerce Data Analysis with Python & SQL

This project analyzes an Ecommerce dataset using **SQL** (MySQL) and **Python (Pandas, Seaborn, Matplotlib)** to uncover insights about sales, customer behavior, retention, and more.

---

## 📂 Dataset

The dataset contains the following CSV files (zipped and extracted in the notebook):
- `orders.csv`
- `customers.csv`
- `order_items.csv`
- `payments.csv`
- `products.csv`
- `sellers.csv`
- `geolocation.csv`

---

## ⚙️ Technologies Used

- Python 3.x
- MySQL / MySQL Connector
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Key Analyses Performed

- 📦 Total and average sales
- 📈 Monthly and yearly trends
- 🧍‍♂️ Customer retention (within 6 months)
- 🧮 YoY Growth of revenue using `LAG()` window function
- 🏆 Top 3 customers by payment per year using `DENSE_RANK()`
- 🧾 Cumulative revenue and moving averages
- 🗺️ Sales distribution by customer city
- 📉 Percentage of installment-based payments

---

## 📝 SQL Highlights

- Use of `JOIN`, `GROUP BY`, `ORDER BY`
- `WINDOW FUNCTIONS`: `LAG()`, `DENSE_RANK()`, `AVG() OVER (...)`
- Subqueries and Common Table Expressions (CTEs)
- Handling of `NaN` values and data type conversion before SQL insert

---

## 🖥️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sundram5274/SQL-Python_Ecommerce.git
