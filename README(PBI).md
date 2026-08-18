# Superstore Business Intelligence - Power BI

This project analyses a retail Superstore dataset using **Excel and Power BI** to understand sales, profitability, product performance, customer segments and regional trends.

The work was completed as part of a university Business Intelligence & Data Warehousing project. The main focus was to clean the raw data, explore the business performance and build dashboards that could be used by different managers.

## Project workflow

1. Clean and standardise the dataset in Excel
2. Explore product, sales, profit and regional patterns
3. Build Power BI reports and visualisations
4. Create dashboards for Regional and Sales Managers
5. Translate the findings into business recommendations

## Data preparation

The data-cleaning stage included:

- checking hidden and empty rows/columns
- removing fully duplicated records
- separating city and postal-code information
- standardising currency fields
- reviewing missing and poorly documented fields before analysis

## Power BI analysis

The analysis looked at areas such as:

- sales and quantity ordered
- product categories and sub-categories
- monthly sales and profit trends
- regional and state profitability
- customer segments
- shipping modes
- least-profitable products
- sales vs quantity relationships

The first-half dataset recorded approximately **$1.92M in sales** and around **25K units ordered**. Office Supplies represented the largest share of quantity ordered, while Technology products were important revenue and profitability drivers in several parts of the analysis.

## Regional Manager Dashboard

![Regional Manager Dashboard](images/regional-manager-dashboard.png)

The Regional Manager dashboard focuses on geographic performance. It combines a map with region/customer-segment information, product-category detail and state-level average unit prices to allow deeper investigation of regional patterns.

## Sales Manager Dashboard

![Sales Manager Dashboard](images/sales-manager-dashboard.png)

The Sales Manager dashboard focuses on product and financial performance, including monthly category sales, shipping-mode profitability, average sales/profit KPIs and the least-profitable products.

## Example insights

- Product demand and profitability varied considerably by region.
- Office Supplies accounted for a large share of units ordered, while Technology products often produced higher-value sales.
- Aggregate sales and quantity ordered had only a weak positive correlation, showing that price, product mix and discounts also matter.
- Some states and product categories performed well overall but showed very different results when drilled down by category or customer segment.
- Shipping mode and product type affected profitability, which created opportunities for logistics and pricing improvements.

## Business recommendations

The report translated the analysis into recommendations around:

- more targeted marketing in lower-performing regions
- customer retention in profitable regions
- reviewing shipping and logistics strategies
- managing low-profit products and inventory more carefully
- using product/category performance to support pricing and purchasing decisions

## Tools

- Microsoft Power BI
- Microsoft Excel
- Data cleaning and standardisation
- Dashboard development
- Descriptive analysis
- Correlation analysis
- Business intelligence reporting

## Repository files

- `report/business-intelligence-report.pdf` - full project report
- `images/regional-manager-dashboard.png` - Regional Manager dashboard
- `images/sales-manager-dashboard.png` - Sales Manager dashboard
- Power BI `.pbix` source file - available in the original GitHub repository

## Power BI source

The original `.pbix` file is available here:

`https://raw.githubusercontent.com/Siddhant0kohli/Power-BI-development-analysis/refs/heads/main/Siddhant%27s%20Report%20Power%20BI%20dashboard.pbix`

## Note

This is an academic portfolio project based on the Superstore dataset. The recommendations are based on the supplied dataset and should be interpreted in that context.
