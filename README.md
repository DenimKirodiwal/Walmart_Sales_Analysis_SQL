# 🛒 Walmart Sales Analysis using SQL

<img width="459" height="110" alt="image" src="https://github.com/user-attachments/assets/c5889342-5232-4ddb-af72-6838612a1b7a" />

Welcome to the **Walmart Sales Analysis** project! This project leverages SQL to explore, clean, and analyze Walmart's retail data for actionable business insights. From understanding customer behavior to identifying top-selling products and peak sales times — this analysis covers it all.

---

## 📁 Project Structure

- ├── sales.csv # Raw dataset
- ├── sales_analysis.sql # SQL queries for data cleaning & analysis
- └── README.md # Project documentation

---

## 📊 Project Objectives

- Clean and preprocess sales data for analysis  
- Identify trends in product performance and customer behavior  
- Discover actionable insights for business decisions  

---

## 🧹 Data Cleaning Steps

- ✅ Removed duplicates using `ROW_NUMBER()`  
- ✅ Renamed incorrect column names (`quantiy` → `quantity`, `prce` → `price`)  
- ✅ Handled NULL values with conditional deletion and updates  
- ✅ Standardized categorical values (e.g., gender, payment mode)  

---

## 🔍 Exploratory Data Analysis (EDA)

| 💡 Analysis Question | 📈 Description |
|----------------------|----------------|
| **Top-Selling Products** | Find top 5 products by quantity sold |
| **Most Cancelled Products** | Identify products frequently cancelled |
| **Peak Purchase Time** | Determine popular shopping hours (Morning, Afternoon, etc.) |
| **Top Spending Customers** | Recognize high-value customers |
| **Revenue by Category** | Analyze which product categories earn the most |
| **Cancellation & Return Rate** | Evaluate dissatisfaction trends by category |
| **Preferred Payment Method** | Understand popular payment modes |
| **Age Group Behavior** | Explore how different age groups spend |
| **Monthly Sales Trends** | Track performance over time |
| **Gender vs Category Purchase** | Analyze gender-based preferences |

---

## 🧠 Key Insights

- 🔥 **Top-selling products** can be restocked and promoted more frequently  
- ❌ **Frequently cancelled items** may need review for quality or description accuracy  
- ⏰ **Most purchases happen in the evening**, ideal for targeted ads  
- 💸 **Loyal customers** identified for exclusive rewards and engagement  
- 💳 **Credit Card** is the most preferred payment method  

---

## 📦 Tools & Technologies

- **SQL Server**  
- **T-SQL (Transact-SQL)**  
- **CSV Dataset**  

---

## 📂 Dataset Overview
- **Source: sales.csv**
- **Fields Include:
transaction_id, customer_id, customer_name, customer_age, gender,
product_id, product_name, product_category, quantity, price,
payment_mode, purchase_date, time_of_purchase, status**

---

## 🚀 How to Run
- **Clone the repo**

- **Import sales.csv using the BULK INSERT command in your SQL Server**

- **Execute sales_analysis.sql for complete cleaning + EDA**

---

## 📌 Future Improvements
- **📊 Add data visualization using Power BI or Tableau**

- **⚙️ Automate data import and cleanup with Python**

- **🌍 Expand analysis to regional or store-level data**

---

## 💬 Contact
**Feel free to connect if you have any suggestions or feedback!**

- **👤 Author: Denim Karodiwal**

- **📧 Email: rajnikarodiwal@gmail.com**

- **🌐 GitHub: DenimKirodiwal**
