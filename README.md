# customer-sales-analysis
Retail sales analysis using Python, Excel and Power BI
# Sales Analysis

## Project Overview

This project analyzes retail sales data to understand business performance, identify sales trends, and evaluate product and regional profitability.

The project uses **Python, Pandas, NumPy, Microsoft Excel, and Power BI** to clean and analyze data, calculate key performance indicators (KPIs), and create visualizations that support data-driven business decisions.

## Project Objectives

- Analyze overall sales, profit, and order volume.
- Identify top-performing products and product categories.
- Compare sales and profitability across different regions.
- Understand monthly sales trends and business performance.
- Evaluate sales channels and customer purchasing patterns.
- Build an interactive Power BI dashboard for business reporting.

## Python Environment — Anaconda

This project uses **Anaconda** to manage the Python environment and install the libraries required for data analysis. It provides a convenient way to work with Python packages such as Pandas, NumPy, Matplotlib, and OpenPyXL.

Anaconda helps maintain a consistent development environment and simplifies dependency management when working with data science projects.

**Libraries used:**
- Pandas — data manipulation and analysis
- NumPy — numerical computations
- Matplotlib — data visualization
- OpenPyXL — Excel file handling

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning, manipulation, and aggregation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Microsoft Excel | Spreadsheet analysis and PivotTables |
| Power BI | Interactive dashboards and business reporting |
| Git & GitHub | Version control and project documentation |

## Project Structure

```text
retail-sales-analysis/
│
├── data/
│   ├── sales_dataset_raw.csv
│   └── sales_cleaned.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── excel/
│   └── sales_analysis.xlsx
│
├── powerbi/
│   ├── sales_data.pbix
│   └── sales_data_screenshot.png
│
└── README.md
```

## Project Workflow

### 1. Data Loading and Inspection
- Imported the retail sales dataset using Pandas.
- Examined column names, data types, and dataset structure.
- Checked for duplicate records and missing values.

### 2. Data Cleaning and Preparation
- Identified and handled duplicate records where appropriate.
- Checked data types and prepared the order date column.
- Validated numerical columns used for sales and profitability analysis.
- Prepared the cleaned dataset for further analysis.

### 3. KPI Analysis
The project evaluates the following key performance indicators:

- **Total Sales:** Total revenue generated from sales.
- **Total Profit:** Total profit recorded in the dataset.
- **Total Orders:** Number of unique orders.
- **Profit Margin:** Total profit divided by total sales, expressed as a percentage.

### 4. Excel Analysis
- Created PivotTables to summarize sales performance.
- Built charts to visualize monthly sales and product performance.
- Applied sorting and conditional formatting to identify important trends.

### 5. Power BI Dashboard
The interactive dashboard is designed to include:

- KPI cards for sales, profit, orders, and profit margin.
- A monthly sales trend line chart.
- A Top 10 Products by Sales bar chart.
- Sales and profit comparisons by region.
- Sales distribution by category.

## Key Findings

This section will summarize the main insights identified during the analysis.

Examples of questions explored:

- Which products generate the highest sales?
- Which categories contribute most to total profit?
- Which regions perform best in terms of sales?
- How do sales change over time?
- Which sales channels contribute most to business performance?

### Prerequisites
- Python 3
- Microsoft Excel (optional, for Excel analysis)
- Power BI Desktop (for the interactive dashboard)

## Skills Demonstrated

- Data cleaning and preprocessing
- Data aggregation and KPI calculation
- Data visualization
- Excel PivotTables and charts
- Power BI dashboard development
- Project documentation and version control

## Data Disclaimer

This project is intended for educational and portfolio purposes. The dataset used is AI generated solely for the purpose of educational use.

## Author

Sanika

Master's Student in Data Science
