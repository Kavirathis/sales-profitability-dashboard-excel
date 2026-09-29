# Sales \& Profitability Analysis Dashboard (Excel)

An interactive Excel dashboard that analyses **2,000 transactions (2022-2023)** to show where revenue comes from, where money is spent, and which regions, products, departments and payment methods drive profit.

!\[Dashboard Preview](images/dashboard\_preview.png)

## Business Problem

Management needs a single view of sales and profitability to answer:

* How much revenue, expense and profit are we making, and at what margin?
* Which regions, product lines and departments perform best (or worst)?
* Which payment methods and customer segments contribute most?
* How do revenue and profit trend month by month?

## Key Numbers

|Metric|Value|
|-|-|
|Total Revenue|53.97M|
|Total Expenses|33.47M|
|Total Profit|20.49M|
|Profit Margin|38.0%|
|Loss-making transactions|26.8%|

## Key Insights

* **Africa** is the most profitable region (8.75M), well ahead of North America (3.92M).
* **Healthcare** is the top product line by revenue (21.86M), about 40% of total revenue.
* **IT** is the most profitable department (8.15M).
* **Cash** payments generate the highest profit (9.01M), followed by Credit Card (5.03M).
* Over a quarter of transactions make a loss - a clear area to investigate (high-expense, low-revenue deals).

## Dashboard Contents

* **Charts:** Profit by Payment Method, Revenue by Product Line, Transactions by Region, Revenue/Expenses/Profit by Department, Average Expense by Department, Revenue by Customer Segment, Revenue by Year and Month
* **Slicers (interactive filters):** Year, Month, Department, Payment Method, Customer Segment

## Workbook Structure

|Sheet|Purpose|
|-|-|
|`DATA`|Raw transaction data (2,000 rows)|
|`REFERENCE PIVOT`|PivotTables that feed every chart|
|`DASHBOARD`|Final interactive dashboard with charts and slicers|

## Tools \& Skills Used

Microsoft Excel - PivotTables, PivotCharts, Slicers, Data Cleaning, Dashboard Design, KPI Reporting

## Repository Structure

```
sales-profitability-dashboard-excel/
├── dashboard/
│   └── Sales\\\_Profitability\\\_Analysis\\\_Dashboard.xlsx
├── data/
│   └── sales\\\_profitability\\\_data.csv
├── docs/
│   └── data\\\_dictionary.md
├── images/
│   └── dashboard\\\_Dashboard\_Image.png
├── .gitignore
├── LICENSE
└── README.md
```

## How to Use

1. Download `dashboard/Sales\\\_Profitability\\\_Analysis\\\_Dashboard.xlsx`.
2. Open in Microsoft Excel (2013 or later - slicers need it).
3. Go to the **DASHBOARD** sheet and use the slicers to filter.

## Author

**Kaviyarasu S** - B.Tech Information Technology, aspiring Data Analyst

* GitHub: KaviyarasuS
* LinkedIn: [https://www.linkedin.com/in/kaviyarasu-s0201](https://linkedin.com/in/your-link)

