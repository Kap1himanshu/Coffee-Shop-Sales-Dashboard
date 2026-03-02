# ☕ Coffee Shop Sales Performance & Business Insights Dashboard

## 1. Coffee Shop Sales Performance & Customer Insights Analysis  

An interactive data analytics project built using SQL and Power BI to analyze coffee shop transactional sales data — focusing on revenue trends, product performance, time-based demand patterns, and business optimization insights.

---

## 2. Short Description / Purpose

The Coffee Shop Sales Dashboard is a multi-page analytical Power BI report designed to evaluate daily sales transactions and uncover business-critical insights.

This project helps identify high-performing products, peak sales hours, seasonal patterns, and revenue distribution to support data-driven decision-making for store managers, marketing teams, and operations planners.

---

## 3. Tech Stack

The project was built using the following tools and technologies:

• 🗄 SQL – Used for revenue aggregation, product ranking, hourly & daily analysis  
• 📊 Power BI Desktop – Data visualization and dashboard creation  
• 🔄 Power Query – Data cleaning and transformation  
• 🧠 DAX (Data Analysis Expressions) – KPI calculations and dynamic measures  
• 🔗 Data Modeling – Table relationships for cross-filtering and aggregation  
• 📁 File Format – `.pbix` for dashboard development and `.xlsx` as raw dataset  

---

## 4. Data Source

Source: Coffee Shop Sales Dataset (Excel file)

The dataset contains transactional sales records including:

- Transaction ID  
- Transaction Date  
- Transaction Time  
- Product Name  
- Product Category  
- Unit Price  
- Quantity Sold  
- Store Location (if applicable)  

The dataset enables detailed time-based, product-level, and revenue analysis.

---

## 5. Features / Highlights

### • Business Problem

Coffee shops generate thousands of daily transactions, but raw data does not easily answer:

- Which products generate the most revenue?  
- What time of day drives maximum sales?  
- Which categories are underperforming?  
- How does weekday vs weekend performance differ?  
- What are the busiest sales hours?  

Management requires structured insights to optimize staffing, inventory, and promotional campaigns.

---

### • Goal of the Dashboard

To build an interactive analytical tool that:

- Tracks daily and monthly revenue trends  
- Identifies best and worst-performing products  
- Analyzes hourly and weekday demand patterns  
- Evaluates category contribution  
- Supports operational and marketing strategy decisions  

---

### • Walkthrough of Key Visuals

## 📊 Page 1 — Sales Overview & Trends

### Key KPIs
- Total Revenue  
- Total Transactions  
- Total Quantity Sold  
- Average Transaction Value  

### Sales by Month (Line Chart)
Displays monthly revenue trends and identifies peak and slow-performing months.

### Sales by Day of Week (Bar Chart)
Highlights busiest weekdays and weekend performance differences.

### Hourly Sales Trend (Line/Bar Chart)
Identifies peak business hours to support staffing and operational planning.

### Sales by Category (Donut/Bar Chart)
Shows revenue distribution across categories such as Coffee, Tea, Bakery, etc.

---

## 🏆 Page 2 — Product Performance Analysis

### Top 5 Products by Revenue
Identifies highest revenue-generating items.

### Top 5 Products by Quantity
Highlights most frequently purchased products.

### Bottom 5 Products
Identifies underperforming SKUs that may require repositioning or promotion.

### Comparative Product Analysis
Side-by-side comparison of high vs low performers to support strategic decisions.

---

## • SQL Analysis Performed

- Revenue calculation using SUM(quantity * unit_price)  
- Total transactions and quantity aggregation  
- GROUP BY analysis for product and category performance  
- Top 5 and Bottom 5 ranking using ORDER BY  
- Hourly and weekday analysis using time extraction functions  
- Validation of Power BI measures using SQL queries  

---

## • Business Impact & Insights

• Staffing Optimization: Align employee shifts with peak sales hours  
• Product Strategy: Promote high-performing items strategically  
• Inventory Planning: Stock fast-moving items efficiently  
• Promotional Strategy: Boost low-performing products during slow hours  
• Revenue Maximization: Identify best-selling time slots for marketing focus  

---

## 🔁 Project Workflow

Raw Excel Data → SQL Aggregation & Cleaning → Data Validation → Power BI Dashboard Development → Business Recommendations
