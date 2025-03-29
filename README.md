# 📊 Tableau Visual Analytics – Problem Set #5 

This project features three interactive Tableau dashboards built as part of MAX 507 Visual Analytics. It explores advanced concepts including **Sets**, **Parameters**, **Calculated Fields**, and **Dashboard Actions** using three real-world datasets.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Problem_Set_5.twbx` | Tableau workbook containing all three dashboards |
| `dashboard_screenshots/` | Optional PNG images of each dashboard (for preview) |

---

## 🟨 Problem 1 – Global Superstore: Proportion of Sales by Subcategory

**Dataset:** Global Superstore  
**Objective:** Visualize product subcategory sales by proportion, using dynamic sorting and set logic

🔧 **Techniques Used:**
- Set for **Selected Countries**
- Parameter for sorting method:
  - Overall Sales
  - Selected Country Sales
  - % of Selected Country Sales vs Global
- Calculated fields for each sort option
- Dynamic title, chart labels, and axis formatting
- Dashboard layout with clear instructions and toggle controls

🎯 **Business Value:**  
Allows users to compare how subcategories perform globally vs. within selected markets, helping to identify regional sales drivers.

---

## 🟦 Problem 2 – Coffee Chain: KPI Scatterplot with Dashboard Action

**Dataset:** Coffee_Chain_Updated  
**Objective:** Create a dual-view dashboard with a map and scatterplot powered by user-selected metrics

🔧 **Techniques Used:**
- Set: **Selected States**
- Parameters:
  - `Select KPI` (Sales, Profit, Margin)
  - `Select Cost` (COGS, Marketing, Total Expenses)
  - `Select Dimension` (State, Market, Product Type, Product)
- Scatterplot with reference lines for averages
- Bar chart showing selected KPI vs. target
- Dashboard Action: Click on states to populate scatterplot
- Dynamic axis titles and chart header via calculated fields

🎯 **Business Value:**  
Provides a flexible visual interface to compare performance metrics across states, enabling market-level diagnostic analysis.

---

## 🟩 Problem 3 – Donations: Top N States by Gift Amount

**Dataset:** Advancement_donations_and_giving_Combined.xlsx  
**Objective:** Display the top contributing states by donation amount for a selected college

🔧 **Techniques Used:**
- Parameter: `Top N States` (values from 5 to 20, in steps of 5)
- Filter: `College` (applied to all worksheets using this data source)
- Calculated field for state ranking
- Filled map with:
  - State abbreviation labels
  - Donation amounts
  - **Tooltips removed** for visual clarity
- Table showing state-by-year breakdown
- **Highlight Action**: Hovering over a state highlights corresponding table row
- Dynamic title that reflects both selected college and N value

🎯 **Business Value:**  
Helps advancement teams focus on the most supportive regions for specific colleges and prioritize fundraising campaigns.

---

## 🧠 Key Skills Demonstrated

- Tableau Parameters & Sets Integration
- Dashboard Actions for interactivity
- Sorting logic via calculated fields
- Dynamic titles and reference lines
- Map + Table linking and highlight behavior
- Clean formatting, no tooltip redundancy, dashboard-level filters

---

## 🔗 References

- MAX 507 Visual Analytics (DePaul University)
- Tableau Community Documentation
- Storytelling with Data principles

---

## 📫 Connect with Me

- 📍 [LinkedIn – Praneth Nandeesh](https://www.linkedin.com/in/praneth-nandeesh-789038285/)
- 📊 [Kaggle Projects](https://www.kaggle.com/pranethhh)
- ✉️ Email: pranethnandeesh@gmail.com

---

## 📌 License

Shared for academic, educational, and portfolio purposes as part of Visual Analytics coursework at Illinois Tech .
