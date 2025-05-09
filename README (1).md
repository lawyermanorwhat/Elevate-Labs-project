
# Retail Sales Dashboard

## 📊 Project Overview

This project presents an **interactive Power BI dashboard** built to analyze online retail sales data. It focuses on identifying purchasing trends, visualizing sales performance across time and geography, and uncovering insights from product descriptions and customer behavior.

## 🎯 Objective

- Analyze historical online retail transaction data.
- Identify high-performing products and customer segments.
- Understand time-based and geographic trends.
- Enable stakeholders to make data-driven decisions through dynamic visuals.

## 🧰 Tools & Technologies

- **Power BI** – Dashboard creation and visualization.
- **Excel** – Data cleaning and preprocessing.
- **Python/Pandas** *(optional)* – For advanced preprocessing.

## 📁 Dataset Description

The dataset includes retail transactions with fields such as:

- InvoiceNo, StockCode, Description
- Quantity, InvoiceDate, UnitPrice
- CustomerID, Country

### Preprocessing Steps:
- Removed null values (especially missing `CustomerID` and `Description`)
- Converted data types (e.g., `InvoiceDate` to datetime)
- Created `TotalPrice = Quantity * UnitPrice`

## 📈 Key Insights from Dashboard

- **Top Months:** November and December show peak sales due to holiday shopping.
- **Top Products:** A few descriptions (e.g., gift items) dominate in revenue.
- **Geographic Trends:** The UK contributes the highest revenue, followed by European countries.
- **Customer Segmentation:** Using RFM metrics (Recency, Frequency, Monetary), customers are grouped into high-value, loyal, or dormant segments.
- **Returns:** Highlighted by negative quantities; often linked to specific products or customers.

## 📌 Features of the Dashboard

- Filters by Country, Month, and Product Description.
- Line chart showing **Quantity sold by Month**.
- Bar chart showing **UnitPrice by Description**.
- Geo map displaying **UnitPrice by Country**.
- Scatter plot correlating **Quantity vs. UnitPrice** by Description.

## ✅ Recommendations

- Retarget high-value customers via personalized campaigns.
- Optimize inventory based on top-performing SKUs.
- Investigate high return-rate products for quality issues.
- Explore expansion into emerging markets showing demand growth.

## 📂 Files Included

| File | Description |
|------|-------------|
| `dashboard.pbix` | Power BI dashboard source file |
| `dashboard.png` | Dashboard screenshot |
| `Online_Retail_Analysis_Report.pdf` | Detailed report of methodology and insights |
| `Untitled.html` / `Untitled.ipynb` | (If applicable) Preprocessing or analysis scripts |
| `README.md` | This file |

## 📌 How to Run

1. Open `dashboard.pbix` in Power BI Desktop.
2. Make sure the dataset is loaded or relinked if needed.
3. Interact with filters and visuals to explore insights.
