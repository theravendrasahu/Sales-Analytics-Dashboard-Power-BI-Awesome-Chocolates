# 📊 Sales Analytics Dashboard Power BI- Awesome Chocolates 

## 🚀 Project Overview

This project is a Power BI Dashboard built to analyze and visualize sales performance of Awesome Chocolates across different countries, products, and sales teams.
It provides insights into Sales, Profit, Cost, Shipments, and Performance Trends with interactive visuals and advanced Power BI features such as calculation groups, measure selectors, and DAX-based KPIs.

---

## 📂 Project Data

The dataset includes multiple dimensions and fact tables:, Shipments (Fact Table), Date, Boxes (bins), Geography, Product, Products (Dimension Table), Product, Category, (Bars, Bites, Other), Cost per Box, People (Dimension Table), Salesperson, Team, Picture, Locations (Dimension Table), Geo, Region, Calendar (Dimension Table), Date

---

## 🗂 Data Model

Star Schema design with Shipments as the fact table
Relationships:
Shipments[Date] → Calendar[Date]
Shipments[Product] → Products[Product]
Shipments[Geography] → Locations[Geo]
Shipments[Salesperson] → People[Salesperson]
This enables powerful filtering and slicing by Time, Region, Product, and Salesperson.

---

## 📐 Key Measures & Calculations

A set of custom DAX measures and calculation groups were created to analyze performance:
Measures, Total Sales, Total Profit, Total Cost, Total Shipments, Total Boxes, Profit %, LBS % (Low Boxes Shipments %), MoM Sales Change %, MoM Shipment Change %, Latest Month Sales, Latest Month Profit, Latest Month Total Shipment, Profit Target & Indicator, Calculation Groups

My cals- Total measure for Latest Month, Latest measure MoM Change

Measure Selector (Dynamic Switching)- Created using field parameters to toggle between: Sales, Boxes, Cost, Shipments, Profit %

---

## 📊 Dashboard Features & Visuals

KPIs
Total Sales, Total Boxes, Total Shipments, Total Cost, Total Profit
Month-on-Month (MoM) Change % indicators
Profit % Gauge with target indicator

## Visuals
Line Chart: Cost by Start of Month (trend analysis)
Column Chart: Shipments Analysis
Table / Matrix: Salesperson-wise performance with Sales, Profit, Profit %, and LBS %
Dynamic Measure Selector: Switch between Sales, Boxes, Cost, Shipments, and Profit %
Slicers/Filters: By Product Category, Country, Region

---

## 🎯 Key Insights
Sales & profit performance tracking across 7 regions: Australia, Canada, India, New Zealand, UK, USA, and Others
Top-performing salespeople with highest profit % identified
Low Box Shipments (LBS %) monitored to optimize logistics
Month-on-Month performance trends clearly visible
Profit target monitoring with a KPI indicator

---

## 🛠 Tools & Technologies
Power BI Desktop
DAX (Data Analysis Expressions)
Calculation Groups (for MoM & dynamic measures)
Field Parameters (for dynamic measure switching)

---

## 📌 How to Use
1. Open the .pbix file in Power BI Desktop
2. Refresh data connections if required
3. Use slicers to filter by Category, Region, or Country
4. Switch measures dynamically using the Measure Selector

---

## 📷 Dashboard Preview
Main Report Page (Sales Report)
KPIs (Sales, Profit, Cost, Shipments)
MoM change indicators
Salesperson performance table
Trend analysis (Cost, Shipments)
Gauge chart (Profit %)

[(Add your screenshots here in GitHub repo for better presentation — e.g., /images/dashboard.png)](https://github.com/theravendrasahu/Sales-Analytics-Dashboard-Power-BI-Awesome-Chocolates/blob/d09f524c6cb8c58ec826b73caac59d065e9e3f19/Dashboard%20Image.png)

---

## ⭐ Key Learnings
Implemented star schema data modeling in Power BI
Used DAX measures & calculation groups for advanced KPIs
Built a dynamic measure selector for flexible reporting
Designed a visually engaging dashboard with business insights

---

## 📌 Future Improvements
Add forecasting models for sales & shipments
Enhance with drill-through pages for deeper analysis
Integrate with real-time data source for live monitoring

---

👨‍💻 Author
Ravendra Sahu
💼 Data & Business Analyst (~3 Yrs) | Advanced Excel/VBA, Power BI, SQL, Python | Dashboarding, Automation, KPI Tracking & Reporting.
🌐 LinkedIn Profile [(Add link)](https://www.linkedin.com/in/theravendrasahu/)
📧 Email- sahuravendra0@gmail.com
