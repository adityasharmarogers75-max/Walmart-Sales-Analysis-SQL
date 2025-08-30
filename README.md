# 🛒 Walmart Sales Analysis using SQL

## 📌 Overview
This project analyzes Walmart sales data using **SQL Server** to uncover valuable business insights.  
It demonstrates SQL concepts such as data cleaning, feature engineering, aggregations, grouping, joins, and advanced analytics queries.

---

## 📂 Dataset
The dataset includes transaction-level details such as:
- Invoice ID  
- Branch & City  
- Customer Type & Gender  
- Product Line  
- Unit Price, Quantity, Tax, Total  
- Date & Time of purchase  
- Payment Method  
- Customer Ratings  

---

## ⚙️ Project Workflow
1. **Database Setup** – Created `WALMART` database and `WalmartSales` table.  
2. **Data Loading** – Imported CSV using `BULK INSERT`.  
3. **Feature Engineering** – Added:  
   - `TimeOfDay` (Morning, Afternoon, Evening)  
   - `DayName` (e.g., Mon, Tue, Wed)  
   - `MonthName` (e.g., Jan, Feb, Mar)  
4. **Exploratory Analysis** – Wrote queries to answer business questions.  

---

## 🔑 Business Questions Answered
- How many unique cities and product lines are there?  
- What is the most common payment method?  
- Which product line sells the most?  
- Which month had the highest revenue?  
- Which branch sells more than the average quantity?  
- What time of the day has peak sales?  
- Which day of the week gets the best ratings?  
- Which customer type generates the most revenue?  

---

## 📊 Example Insights
- ✅ Branch **C** had the highest total revenue.  
- ✅ **Electronic Accessories** was the top-selling product line.  
- ✅ **Evening hours** generated the most sales.  
- ✅ **E-Wallet** was the most common payment method.  

---

## 🎯 Key Learnings
- Data cleaning & feature engineering with SQL.  
- Using `CASE`, `GROUP BY`, `HAVING`, `DATENAME`, `FORMAT` functions.  
- Applying aggregations and business logic in SQL.  
- Generating actionable insights from retail sales data.  

---

## 🚀 Future Enhancements
- Build interactive dashboards in Power BI / Tableau.  
- Automate SQL queries for reporting.  
- Extend analysis with Python (Pandas, Matplotlib, Seaborn).  

---

## 📜 License
This project is licensed under the MIT License.  
