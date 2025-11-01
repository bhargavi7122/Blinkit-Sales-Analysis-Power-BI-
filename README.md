<h1 align="center">🛒 Blinkit Sales Analysis Dashboard | Power BI</h1>
<h3 align="center">Data Visualization | DAX Measures | KPI Analysis | Power Query</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Language-DAX%20%7C%20M%20Query-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Sales%20Performance%20Analysis-green?style=for-the-badge"/>
</p>

---

### 🧾 *About the Project*
The **Blinkit Sales Analysis Dashboard** is an interactive Power BI project designed to analyze Blinkit’s grocery sales performance.  
It focuses on understanding **total sales, product demand, outlet performance, and customer ratings** across various regions and categories.  
This dashboard converts raw sales data into **insightful KPIs and visual stories** for smarter business decisions.

---

### 🚀 *Key Objectives*
- 📊 Track **total and average sales** across outlets and item types.  
- 🏪 Identify **top-performing outlet types** and **high-revenue locations.**  
- 🍎 Analyze **sales distribution by item type and fat content.**  
- ⭐ Evaluate **average ratings** and their effect on sales performance.  
- 🎯 Build an **interactive Power BI dashboard** with filters and KPIs.

---

### ⚙️ *Project Workflow*
1. **Data Loading & Cleaning**
   - Imported Blinkit dataset into Power BI.
   - Cleaned data using **Power Query Editor**.
   - Removed nulls, standardized category names, and formatted numerical fields.

2. **Data Modeling**
   - Built relationships between **items, outlets, and sales** tables.
   - Defined measures using **DAX** for custom KPIs.

3. **DAX Measures**
   - `Total Sales = SUM(Blinkit[Item_Outlet_Sales])`  
   - `Average Sales = AVERAGE(Blinkit[Item_Outlet_Sales])`  
   - `Total Items = COUNT(Blinkit[Item_Identifier])`  
   - `Average Rating = AVERAGE(Blinkit[Item_Weight])`  
   - `Target % = DIVIDE([Total Sales], 2400000) * 100`

4. **Visualization**
   - Created KPI cards, bar charts, donut charts, and maps.
   - Used filters for **Outlet Type**, **Fat Content**, and **Item Type**.
   - Added drill-through analysis for outlet-wise insights.

---

### 🧠 *Key Insights*
- 🏪 **Supermarket Type 1** has the highest total sales.  
- 🏙️ **Tier 3 cities** contribute the most to total revenue.  
- 🍪 **Regular fat content** items outperform *Low Fat* in sales.  
- 🍎 **Fruits & Vegetables** and **Snack Foods** dominate the top-selling categories.  
- ⭐ Products with higher ratings have better average sales.  

---

### 💡 *Recommendations*
- 📦 Increase stock for **top-performing product types** in Tier 3 outlets.  
- 🏬 Focus marketing on **Supermarket Type 1**, where sales growth is highest.  
- ⚖ Optimize **pricing strategy** for low-performing fat content items.  
- 📈 Use trend analysis to forecast **seasonal sales patterns.**

---

### 🧰 *Tech Stack*
| Tool / Feature | Purpose |
|----------------|----------|
| 🧩 Power BI | Dashboard creation & visualization |
| 🧮 DAX | Custom measures & calculated KPIs |
| 🧹 Power Query | Data cleaning & transformation |
| 📘 Excel / CSV | Source dataset |

---

### 📂 *Repository Structure*

📁 *blinkit-sales-analysis-dashboard*  
│  
├── 📊 *Blinkit_Sales_Dashboard.pbix* → Main Power BI file.  
├── 📄 *Blinkit_Dataset.csv* → Original dataset used.  
├── 🧮 *DAX_Measures.txt* → Contains all custom DAX formulas.  
├── 🎥 *Dashboard_Demo.mp4* → Demo video of Power BI dashboard.  
└── 📄 *README.md* → Project documentation for recruiters and contributors.  

---

<h3 align="center">✨ Transforming Grocery Sales Data into Actionable Business Insights ✨</h3>

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/shopping-cart.png" width="80"/>
</p>
