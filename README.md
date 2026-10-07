An interactive Tableau dashboard that analyses Nike sales performance across regions, retailers, products and sales methods, with KPIs for revenue, units sold, orders and average selling price.

---

## 📌 Project Overview

This project turns a raw sales dataset into a dashboard that helps answer key business questions:

- How much revenue is being generated, and how many units are being sold?
- How do sales change month by month?
- Which regions, retailers and products perform best?
- Which sales method (for example in-store or online) brings in the most sales?

## 🖼️ Dashboard Preview


![Dashboard Preview](images/dashboard.png)


## 📂 Dataset

**File:** `Nike Dataset.csv`

| Column | Description |
|---|---|
| Retailer | Retailer that sold the product |
| Region | Sales region |
| State | State where the sale took place |
| Product | Product sold |
| Sales Method | How the sale was made |
| Invoice Date | Date of the invoice |
| Price per Unit | Selling price of one unit |
| Units Sold | Number of units sold |
| Total Sales | Total sales amount |

## 📊 Dashboard Contents

| Worksheet | What it shows |
|---|---|
| **KPI** | Headline numbers: total revenue, total units sold, total orders, average selling price and average sales per product |
| **Monthly Sales by Trend** | Line chart of sales over time |
| **Sales by Region** | Regional sales comparison (charts and map) |
| **Sales by Sales Method** | Share of sales by sales method |
| **Top Retailers** | Best-performing retailers |
| **Top Selling Products** | Best-selling products |
| **Filters** | Interactive filters to slice the dashboard |

## 🧮 Calculated Fields (KPIs)

| KPI | Formula |
|---|---|
| Total Revenue | `SUM([Total Sales])` |
| Total Units Sold | `SUM([Units Sold])` |
| Total Orders | `COUNT([Product])` |
| Average Selling Price | `SUM([Total Sales]) / SUM([Units Sold])` |
| Average Sales per Product | `AVG([Total Sales])` |

## 🔍 Key Insights

> Replace these with your own findings from the dashboard.

- **Top region:** *(region name)* generated the highest sales.
- **Top retailer:** *(retailer name)* led in total revenue.
- **Best-selling product:** *(product name)* had the most sales.
- **Sales method:** *(method)* contributed the largest share of revenue.
- **Trend:** *(for example, sales peaked in month/season)*.

## 🛠️ Tools Used

- **Tableau** for dashboard design, calculated fields, charts, maps and filters
- **CSV** as the data source

## ▶️ How to Open the Project

1. Download or clone this repository.
2. Open `My_project.twb` in **Tableau Desktop** or **Tableau Public**.
3. If Tableau asks for the data source, point it to `Nike Dataset.csv` in this folder.

## 📁 Repository Structure

```
nike-sales-dashboard-tableau/
├── My_project.twb                # Tableau workbook
├── Nike Dataset.csv              # Dataset
├── README.md
└── Tableau_Dashboard.PNG         # Dashboard screenshots
```

## 👩‍💻 Author

**Jasmin P P**
Aspiring Data Analyst | Thrissur, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jasmin_P_P-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/jasmin-p-p-640184341)
