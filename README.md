## 📊 Power BI Dashboard Code (Blinkit Sales Analysis)

### 🧮 DAX Measures

-- Total Sales
Total_Sales = SUM(Blinkit[Item_Outlet_Sales])

-- Average Sales
Average_Sales = AVERAGE(Blinkit[Item_Outlet_Sales])

-- Total Items
Total_Items = COUNT(Blinkit[Item_Identifier])

-- Average Rating
Average_Rating = AVERAGE(Blinkit[Item_Weight])

-- Maximum Sales
Max_Sales = MAX(Blinkit[Item_Outlet_Sales])

-- Minimum Sales
Min_Sales = MIN(Blinkit[Item_Outlet_Sales])

-- Sales Target Achievement %
Target_Achievement = DIVIDE([Total_Sales], 2400000) * 100

-- Sales by Fat Content
Sales_By_FatContent = CALCULATE(
    [Total_Sales],
    Blinkit[Item_Fat_Content] = "Regular"
)

-- Sales by Outlet Type
Sales_By_OutletType = CALCULATE(
    [Total_Sales],
    Blinkit[Outlet_Type] = "Supermarket Type1"
)

-- Total Sales by Location Tier
Sales_By_Location = SUMMARIZE(
    Blinkit,
    Blinkit[Outlet_Location_Type],
    "Total Sales", [Total_Sales]
)

-- Yearly Sales (if Date available)
Yearly_Sales = CALCULATE(
    [Total_Sales],
    YEAR(Blinkit[Date]) = 2023
)
