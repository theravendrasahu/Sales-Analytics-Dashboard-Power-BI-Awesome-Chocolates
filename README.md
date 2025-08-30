Sales Analytics Dashboard – Power BI (Awesome Chocolates)[1]

Overview
An end-to-end Power BI dashboard for a fictional chocolate company showcasing the complete BI workflow: dimensional modeling with a star schema, DAX measures for core KPIs, month-on-month time intelligence, and an interactive UX with KPI cards, tooltips, bookmarks, field parameters, and slicer panels. The dataset used is ac-sample-data.xlsx.[2][1]

Features
- Data model: One fact table (Shipments) connected to Product, Salesperson, Geography, and Calendar dimensions for a star schema.
- KPIs: Total Sales, Total Boxes, Total Shipments, Total Costs, Total Profit, Profit %.
- Costing: Total Costs derived from cost-per-box in Product and Boxes in Shipments, aggregated to Profit and Profit %.
- Time intelligence: Marked Calendar table; Month-on-Month change patterns using PREVIOUSMONTH and a “Latest Month” approach for card reference labels.
- Insights: Low-Box Shipments analysis (<50 boxes) with LBS Count and LBS % to monitor shipment mix.
- UX polish: New Card visuals with reference labels and icons, conditional formatting, Profit % gauge, bookmarks (Product vs People), histograms via grouping, zoom slider, page-level slicer panel.

Repository structure
- /report: Power BI .pbix file with 1920×1080 canvas, theme, header KPI cards, trend analysis, and detailed Product and Salesperson views.
- /data: ac-sample-data.xlsx (or link/placeholder) used by the report.
- /assets: optional icons used in KPI cards.

Setup
1) Clone the repository and download ac-sample-data.xlsx into the /data folder.
2) Open the .pbix in Power BI Desktop; update file paths if prompted and Refresh.
3) Explore pages, slicers, tooltips, and bookmarks; interact with KPI cards and trends.

DAX highlights
- Measures table organizing KPIs and time intel metrics.
- MoM patterns using PREVIOUSMONTH and variables for current vs prior month.
- “Latest Month” measures to populate reference labels on KPI cards even at total level.

Skills demonstrated
- Dimensional modeling and relationships for a star schema.
- DAX for KPIs, costs, profit, LBS metrics, and MoM time intelligence.
- Report design: card reference labels, conditional formatting, gauge targets, field parameters, bookmarks, tooltips, and histogram grouping.

Notes
- This project uses a fictional dataset for learning and portfolio demonstration. Replace or extend with real data as needed.
