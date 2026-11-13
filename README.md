# Quick Commerce Analytics Dashboard

An executive-level, interactive Excel dashboard that analyzes 1M+ rows of multi-platform quick commerce transactions across 8 major brands: Swiggy Instamart, Blinkit, Zepto, BigBasket, Flipkart Minutes, Amazon Now, Dunzo and JioMart.

## Dashboard Preview

![Quick Commerce Dashboard](Quick%20Commerce%20Dashboard.png)

## Business Problem

Quick commerce is a highly competitive space where platforms compete on sales, delivery speed and customer experience. Leadership needed one dashboard to:
- Benchmark brand performance by sales
- Track order volume, quantity and delivery speed
- Understand category and payment mode contribution
- Compare delivery time across cities

## Key KPIs

| KPI | Value |
|---|---|
| Total Orders | 1.0M |
| Total Gross Sales | ₹571.6M |
| Total Quantity | 9.7M |
| Average Delivery Speed | 16.5 Min |
| Average Rating | 3.0 / 5 |
| Average Distance | 7.8 Km |

## Brand Performance Benchmarking

| Rank | Brand | Gross Sales |
|---|---|---|
| #1 | Swiggy Instamart | ₹80.8M |
| #2 | Blinkit | ₹76.6M |
| #3 | Zepto | ₹74.4M |
| #4 | BigBasket | ₹71.7M |
| #5 | Flipkart Minutes | ₹70.8M |
| #6 | Amazon Now | ₹69.5M |
| #7 | Dunzo | ₹67.6M |
| #8 | JioMart | ₹60.3M |

## Visuals

- **Category-wise Sales Trends**
- **Payment Mode Share** (donut chart)
- **Delivery Time by City** (heatmap)
- **Brand Sales Ranking** (#1 to #8)

## Filters

City | Category | Payment Mode

Slicers filter the whole dashboard instantly (for example: City = Hyderabad, Category = Snacks, Payment Mode = Credit Card).

## Data Model

- 1M+ rows of transaction-level quick commerce data
- Pivot Tables as the calculation backend
- `GETPIVOTDATA` formulas linking the pivot tables to the dashboard KPIs
- Optimized data modeling for fast performance on a large dataset

## Key Learnings and Approach

- Handled a 1M+ row dataset in Excel with an optimized data model
- Used `GETPIVOTDATA` to keep KPI cards dynamic and linked to the pivot tables
- Built slicer-driven interactivity so all visuals respond to the selected City, Category and Payment Mode
- Benchmarked all 8 brands on a single sales ranking

## Tools Used

Microsoft Excel, Pivot Tables, GETPIVOTDATA, Slicers, Data Modeling

## Repository Structure

```
├── README.md
└── Quick Commerce Dashboard.png
```

## Access Full Dataset and File

Due to GitHub file size limits, the complete processed Excel file is hosted on Google Drive:

🔗 [Download Full Quick Commerce Dataset and Dashboard (.xlsx / .xlsb)](https://drive.google.com/file/d/1vQq2LUujQQWePcoSZOd3hLexHlEg558v/view?usp=sharing)

## How to Use

1. Download the workbook from the Google Drive link above
2. Open it in Microsoft Excel
3. Use the City, Category and Payment Mode slicers to explore the data

## Author

**Vikas Pawar**
🔗 [LinkedIn](https://www.linkedin.com/in/vikas-pawar-in) | [GitHub](https://github.com/Viky3891)

Feedback and suggestions are welcome!
