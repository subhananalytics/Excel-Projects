# Excel-Based Complete E-Commerce Management & Analytics System

## 📌 Project Overview
An end-to-end business operations tool developed in Excel to manage the full lifecycle of an e-commerce order—from entry to delivery and financial analysis. This project eliminates the need for expensive CRM/ERP software for small businesses.



## 🧩 System Architecture
The system is built on a modular architecture across 6 specialized sheets:

1. **Orders_DB:** The "Single Source of Truth" using Excel Tables for dynamic data ranges.
2. **Order_Search:** A high-speed lookup tool utilizing `XLOOKUP` and `Data Validation` to retrieve specific order profiles.
3. **Delivery_Tracking:** A logistics module with automated status updates (Pending/Delivered) and visual indicators.
4. **Inventory_Tracking:** Automated stock deduction using `SUMIFS` to link sales data to warehouse levels.
5. **Invoice_Generator:** A dynamic, print-ready template that auto-populates via `GETPIVOTDATA` and `XLOOKUP`.
6. **Executive Dashboard:** A visual command center featuring Slicers, Pivot Charts, and KPI cards.

## 📊 Key Metrics Tracked
- **Total Revenue & Orders:** High-level financial health.
- **Average Order Value (AOV):** Customer spending trends.
- **Delivery Fulfillment Rate:** Real-time logistics efficiency.
- **Stock Status:** Automatic "Low Stock" flagging using Conditional Formatting.



## 🛠️ Technical Skills Demonstrated
- **Advanced Formulas:** `XLOOKUP`, `SUMIFS`, `ISNUMBER`, `SEARCH`.
- **Data Engineering:** Designing relational structures within Excel.
- **Automation:** Reducing manual data entry through dynamic linkages.
- **UI/UX Design:** Creating a clean, non-spreadsheet look for end-users (hiding gridlines, custom buttons).

## 🚀 How to Use
1. Add new orders to the **Orders_DB**.
2. Refresh the **Sales Analysis** sheet to update Pivot Tables.
3. Use the **Search Bar** to find specific customer details.
4. Generate a PDF invoice by typing the Order ID into the **Invoice** sheet.
