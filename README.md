
# SuperMart Sales Analysis – Excel Dashboard 2025

## Project Overview
This project presents a **comprehensive Sales Analysis Dashboard** built in **Microsoft Excel 2010** using the *SuperMart Sales Dataset (2025)*.  
The main objective is to analyze sales performance, profit trends, and top-performing products, and to visualize business insights using Excel dashboards.

---

## Problem Statement
SuperMart wants to understand its **overall sales and profit performance** by analyzing:
- Which **regions, categories, and products** generate the most sales and profit.
- Which **orders result in loss** or low profit margins.
- How **monthly and yearly trends** change over time.
- Insights to help **management make better business decisions**.

---

## Tools & Techniques Used
| Category | Tools / Features |
|-----------|------------------|
| **Software** | Microsoft Excel 2010 |
| **Data Source** | SuperMart Sales Dataset (2025) |
| **Data Preparation** | Table formatting, Filters, Sorting, Named Ranges |
| **Analysis Techniques** | Pivot Tables, Pivot Charts, Conditional Formatting |
| **Visualization** | Column, Bar, Line, Pie Charts |
| **Dashboard Elements** | Slicers for Region, Category, and Month |

---

## Formulas & Functions Used
| Function Type | Example Formulas |
|----------------|------------------|
| **Mathematical & Statistical** | `=SUM()`, `=AVERAGE()`, `=COUNT()`, `=MIN()`, `=MAX()` |
| **Conditional** | `=IF()`, `=COUNTIF()`, `=SUMIF()`, `=AVERAGEIF()` |
| **Lookup Functions** | `=VLOOKUP()`, `=INDEX()`, `=MATCH()` |
| **Text Functions** | `=LEFT()`, `=RIGHT()`, `=LEN()`, `=CONCATENATE()` |
| **Date Functions** | `=YEAR()`, `=MONTH()`, `=TEXT()` |
| **Other Useful** | `=ROUND()`, `=ABS()`, `=INT()` |

---

## 📊 Key Performance Indicators (KPIs)
| KPI Name | Formula | Description |
|-----------|----------|-------------|
| **Total Sales** | `=SUM(tblSales[Total Sales])` | Overall sales revenue |
| **Total Profit** | `=SUM(tblSales[Profit])` | Total profit generated |
| **Total Orders** | `=COUNTA(tblSales[Order ID])` | Count of all orders |
| **Average Order Value** | `=AVERAGE(tblSales[Total Sales])` | Average revenue per order |
| **Average Profit Margin** | `=AVERAGE(tblSales[Profit]/tblSales[Total Sales])` | Average profit % per sale |
| **Orders with Loss** | `=COUNTIF(tblSales[Profit],"<0")` | Number of loss-making orders |

---

## 📈 Dashboard Insights
- **Total Sales:** ₹85,758,863.62 (approx)  
- **Average Profit Margin:** ~10.4%  
- **Top 5 Products** contribute the majority of total profit.  
- **West & South regions** lead in total sales.  
- **Q2 and Q4** show peak sales periods.  
- Around **30 orders** had losses — helpful to identify pricing or logistics issues.  
- Dynamic **slicers** allow instant filtering by Region, Category, and Month.

---

## Business Impact
This Excel dashboard helps SuperMart:
- Identify **top-selling products and high-performing regions.**  
- Detect **loss-making orders** and optimize pricing.  
- Analyze **monthly sales trends** for forecasting.  
- Enable **data-driven decision making** through clear visual insights.  

---

## Skills Demonstrated
- Data Cleaning & Preparation  
- Dashboard Designing in Excel  
- Pivot Table & Chart Mastery  
- Use of Slicers & Filters  
- Business KPI Analysis  
- Data Visualization & Storytelling  

---

## Final Outcome
  A **fully interactive Excel Dashboard** that provides management with:
- Quick access to KPIs (Sales, Profit, Orders)  
- Region-wise, Product-wise & Monthly performance  
- Insightful visuals and trends  
- Automated calculations via formulas  

---

## File Included
  `SuperMart_Sales_2025.xlsx` – Complete project file with dataset, calculations, and dashboard.

---

## Author
**Anand Kumar**    
**Gmail** - Anandkgzb3@gmail.com
**LinkedIn** - https://www.linkedin.com/in/anand-kumar-201106297/

---

  

