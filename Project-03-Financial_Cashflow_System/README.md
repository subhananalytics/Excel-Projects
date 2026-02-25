# 💰 Financial & Cash Flow Management System

## 📌 Business Case
Most small businesses don't fail because they lack sales—they fail because they run out of cash. This system solves the "visibility gap" by transforming raw bank exports into a strategic decision-making tool.

## 🔴 The Problem It Solves
Owners often confuse **Profit** with **Cash-on-Hand**. This tool tracks:
- **Where is the money going?** (Categorized Expenses)
- **What is our monthly burn?** (Average Outflow)
- **How much "Life" does the business have left?** (Runway Calculation)

## 🛠️ Key Features
- **Transaction Engine:** A structured input sheet with Data Validation to prevent entry errors.
- **Dynamic Cash Flow Forecast:** A 12-month rolling view using `EOMONTH` and `SUMIFS` to predict future bank balances.
- **Executive Dashboard:** - **KPI Cards:** Total Income, Total Expenses, Net Profit, and Cash Position.
  - **Burn Rate Tracker:** Visualizes monthly spending trends.
  - **Expense Mix:** A breakdown of fixed vs. variable costs.
- **Status Toggles:** Filter between "Paid" and "Pending" to see your actual vs. projected cash position.

## 🧪 Technical Deep-Dive
- **Date Logic:** Automated headers that update based on the current month, ensuring the report never goes "out of date."
- **Formula Strategy:**
  - `SUMIFS` for multi-criteria aggregation (Month + Category + Transaction Type).
  - `IFERROR` handling to keep the dashboard clean even with missing data.
- **UI/UX Design:** Removed gridlines, used custom color palettes, and implemented Slicers for a "Software-as-a-Service" (SaaS) feel within Excel.

## 📂 Contents
- `Financial_System_v1.xlsx`: The core application.
- `Screenshots/`: Visual previews of the Dashboard and Transaction Log.

---
## 🚀 Quick Start
1. Open the file and go to the **Setup** tab to define your categories.
2. Enter your transactions in the **Transactions** tab.
3. Refresh the **Dashboard** to see your financial health instantly.
