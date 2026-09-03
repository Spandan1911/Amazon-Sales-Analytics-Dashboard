# Amazon-Sales-Analytics-Dashboard
End-to-end EDA &amp; Power BI dashboard analyzing 129K Amazon India fashion orders (Mar–Jun 2022). Cleaned data in Python (Pandas), explored revenue trends, cancellations, fulfilment &amp; regional sales, then built an interactive Power BI dashboard with ₹72M revenue insights across 10 states.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🎯 Objectives
- Clean and prepare raw e-commerce order data for analysis
- Understand revenue growth patterns and monthly sales trends
- Identify best-selling product categories and top-performing states
- Analyze order cancellations and returns to uncover operational issues
- Compare B2B vs B2C performance and Amazon vs Merchant fulfilment
- Build an interactive, decision-ready dashboard for business stakeholders
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Excel (data source)
- openpyxl
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# ⚙️ Techniques Used
- Data Cleaning — null handling, duplicate removal, column standardization
- Feature Engineering — Month, Day Name, standardized state names
- Groupby Aggregation — revenue, order count, and average order value by multiple dimensions
- Time Series Analysis — monthly and day-of-week revenue trends
- Comparative Analysis — B2B vs B2C, Amazon vs Merchant fulfilment
- Category & Segment Analysis — quantity, revenue, and size distribution by product category
- Root Cause Analysis — cancellation and return trends by category and SKU
- Interactive Data Visualization — Power BI KPI cards, line charts, donut charts, bar charts
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# ✨ Features
- Monthly Revenue Trend — line chart tracking revenue from March to June 2022
- KPI Cards — Total Orders, Total Revenue, Cancellation Rate, Average Order Value
- Order Status Breakdown — Shipped, Delivered, Cancelled, Returned, Others
- Fulfilment Analysis — Amazon vs Merchant order share
- Category-wise Quantity Analysis — units sold by product category (Set, Kurta, Western Dress, etc.)
- State-wise Revenue Analysis — top 10 states by total revenue
- Apply Filter — interactive filtering across the entire dashboard
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  
🗂️ Project Structure

amazon-sales-dashboard/

- Amazon_EDA.ipynb → Full exploratory data analysis notebook (cleaning, EDA, visualizations)
- sales_dataset.xlsx → Raw Amazon India sales dataset used for analysis
- Amazon_dashboard.pbix → Power BI dashboard file
- dashboard_overview.png → Dashboard preview screenshot
- README.md → Project documentation
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# ⚙️ How It Works
- Step 1 — Raw sales data loaded from Excel into Python using Pandas
- Step 2 — Dataset structure explored (shape, dtypes, nulls, duplicates, summary stats)
- Step 3 — Missing values and duplicates handled; cancelled order amounts set to zero
- Step 4 — New features engineered — Month, Day Name, standardized ship-state
- Step 5 — Financial performance analyzed — monthly revenue, average order value, top categories, day-of-week trends
- Step 6 — Customer insights explored — top states, cancellation trends, B2B vs B2C comparison
- Step 7 — Logistics analyzed — Amazon vs Merchant fulfilment, shipping service levels
- Step 8 — Product & inventory patterns studied — category-wise quantity, size distribution
- Step 9 — Returns and cancellations examined — problematic categories and top problematic SKUs
- Step 10 — Cleaned data and summary tables exported and connected to Power BI for dashboard visualization
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🔍 Key Findings
Area	    |Finding
Financial	|April was the peak month for revenue and order volume
Financial	|Sets and Kurtas are the top-selling categories (~76% of orders combined)
Financial	|Sunday drives the highest weekly revenue
Customer	|Maharashtra is the #1 state by order volume, followed by Karnataka and Telangana
Customer	|April recorded the highest cancellation count
Customer	|B2C dominates order volume; B2B has a higher average order value
Logistics	|Amazon fulfilment handles the majority (~70%) of total orders

Overall	Total Orders: 129K · Total Revenue: ₹72M · Cancellation Rate: 14.2% · Avg Order Value: ₹556.76
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🔌 Data & Tools Notes
- No external API used — entire analysis runs locally in Python
- Dataset covers Amazon India fashion sales from March to June 2022
- Power BI dashboard connects directly to the cleaned dataset for interactive filtering
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# 🔎 Conclusion
This project demonstrates how Python and Power BI can be combined to turn raw e-commerce transaction data into actionable business insights. The Python-based EDA uncovers detailed patterns in revenue, cancellations, fulfilment, and regional performance, while the Power BI dashboard translates these findings into an interactive, stakeholder-friendly tool. Together, they highlight a complete data analytics workflow — from raw data to cleaned dataset to business-ready visualization — that supports faster, data-driven decision-making for e-commerce operations.
