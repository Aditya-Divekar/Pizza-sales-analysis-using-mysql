# PIZZA-SALES-ANALYSIS-USING-MYSQL
Analyzed sales data to uncover revenue trends, peak order times, best-selling pizzas, and category/size performance. Used SQL (Joins, Aggregations, Window Functions) to generate actionable business insights that support better inventory, staffing, and marketing decisions

## 📌 Project Overview
This project analyzes a pizza sales dataset using **MySQL** to uncover key business insights such as:
- Revenue trends
- Best-selling pizzas
- Peak ordering times
- Category & size performance

The goal is to support **data-driven decision-making** for improving sales strategy, inventory planning, and operational efficiency.

---

## 🎯 Objectives
- Analyze pizza sales dataset using SQL
- Identify top revenue and top-selling items
- Understand customer ordering behavior by time
- Evaluate performance by pizza category and size

---

## 🗂️ Dataset & Tables Used
The dataset consists of 4 relational tables:

1. **orders** → `order_id`, `date`, `time`
2. **order_details** → `order_id`, `pizza_id`, `quantity`
3. **pizzas** → `pizza_id`, `pizza_type_id`, `size`, `price`
4. **pizza_types** → `pizza_type_id`, `name`, `category`, `ingredients`

---

## 🛠️ Tools & Skills Used
- **MySQL**
- SQL Concepts:
  - JOINS
  - GROUP BY, ORDER BY
  - Aggregate Functions (SUM, COUNT, AVG)
  - Window Functions (OVER)

---

## 📊 Key Insights
- ✅ **Total Orders:** 48,620  
- ✅ **Total Revenue:** $817,860.05  
- ✅ **Most Ordered Size:** Large (L) – 18,526 orders  
- ✅ **Highest Priced Pizza:** The Greek Pizza – $35.95  
- ✅ **Average Pizzas Sold Per Day:** 138  
- ✅ **Peak Order Timing:**  
  - 12–1 PM (Lunch)
  - 6–8 PM (Dinner)
- ✅ **Classic Category Contribution:** 26.9% of total revenue

---

## 📈 Business Impact
This analysis helps the business to:
- Identify **best-selling pizzas** for promotions & combos
- Support **inventory planning** based on category demand
- Improve **staff scheduling** during peak hours
- Optimize **menu strategy** using revenue-driven insights

---

## ✅ Project Conclusion
This project analyzed pizza sales data using **MySQL** to uncover sales trends and customer demand patterns, using SQL (Joins, Aggregations, Window Functions) to deliver actionable business insights for decision-making.

---

## 📌 Future Improvements
- Build interactive dashboard in **Power BI / Tableau**
- Add customer segmentation if customer data is available
- Perform forecasting for future demand planning

---

## 🤝 Connect with Me
If you liked this project, feel free to connect with me on LinkedIn and check out more projects!
