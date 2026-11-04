# Retail Sales Performance, Customer Behaviour & Profitability Analysis

**Tools:** Python \| Pandas \| NumPy \| Matplotlib \| Seaborn \| Power
BI \| DAX \| Google Colab

## Project Overview

This project analyses retail sales data to understand business
performance, customer purchasing behaviour, product performance, and
profitability. Python is used for data inspection, cleaning,
preprocessing, and exploratory data analysis (EDA). Power BI is used to
build interactive dashboards that present key metrics and business
insights.

The project is presented through two Power BI dashboards:

1.  **Sales Performance Analysis** -- explores sales, net sales, profit,
    costs, regional performance, category performance, and monthly sales
    trends.
2.  **Customer & Product Analysis** -- explores customer profitability,
    satisfaction, discounts, product returns, and purchasing quantities.

## Project Objectives

-   Analyse sales performance across regions, product categories, and
    subcategories.
-   Evaluate revenue, costs, discounts, and profitability.
-   Identify customer purchasing patterns and customer segments.
-   Examine customer satisfaction and product return patterns.
-   Compare the performance of products and regions.
-   Present actionable findings through interactive Power BI dashboards.

## Dataset Description

The dataset is a structured retail sales CSV file.

  Dataset detail   Description
  ---------------- ------------------------
  Records          15,006
  Features         15
  Format           CSV
  Domain           Retail Sales Analytics

### Dataset Features

  Column                    Description
  ------------------------- --------------------------------------------
  `Order_ID`                Unique identifier for each sales order
  `Order_Date`              Date of the sales order
  `Customer_ID`             Unique customer identifier
  `Region`                  Region associated with the transaction
  `Category`                Main product category
  `Subcategory`             Product subcategory
  `Quantity`                Number of units purchased
  `Unit_Price_INR`          Unit selling price in INR
  `Sales_INR`               Sales amount before discount
  `Discount_Amount_INR`     Discount applied to the transaction
  `Net_Sales_INR`           Sales amount after discount
  `Cost_INR`                Cost associated with the products sold
  `Profit_INR`              Profit from the transaction
  `Returned`                Indicates whether the product was returned
  `Customer_Satisfaction`   Customer satisfaction rating

> **Data source:** Add the original dataset publisher or download link
> here before publishing the repository. The source and date coverage
> should be verified from the original dataset.

## Tools & Technologies

-   **Python:** Data inspection, cleaning, preprocessing,
    transformation, and EDA.
-   **Pandas:** Data manipulation and analysis.
-   **NumPy:** Numerical operations.
-   **Matplotlib & Seaborn:** Exploratory data visualisation.
-   **Google Colab:** Python development environment.
-   **Power BI:** Data modelling, report development, interactive
    visualisations, and dashboard creation.
-   **DAX:** Measures and KPI calculations.

## Data Preprocessing

The Python workflow includes:

-   Inspecting dataset dimensions, column names, data types, and
    non-null counts.
-   Identifying missing values in `Region`, `Category`, `Quantity`, and
    `Customer_Satisfaction`.
-   Checking for duplicate records.
-   Converting `Order_Date` into a datetime data type.
-   Reviewing numerical and categorical columns for inconsistent values.
-   Preparing the cleaned data for exploratory analysis and Power BI
    reporting.

The actual treatment of missing values, duplicates, and outliers should
be documented according to the steps applied in the final notebook.

## Exploratory Data Analysis

The analysis focuses on:

-   Regional sales and profit comparisons.
-   Category-wise and subcategory-wise sales performance.
-   Monthly sales trends.
-   Profit contribution by subcategory.
-   Discount patterns across regions and categories.
-   Customer profitability and satisfaction.
-   Returned versus non-returned product quantities.
-   Quantity and product performance comparisons.

## Power BI Dashboards

### Dashboard 1: Sales Performance Analysis

Key visuals and metrics include:

-   Sales and net sales KPIs.
-   Average profit and cost analysis.
-   Sales by region.
-   Sales by category and subcategory.
-   Profit by subcategory.
-   Monthly sales trend.
-   Regional and category slicers.
-   Quantity and unit-price comparison.

### Dashboard 2: Customer & Product Analysis

Key visuals and metrics include:

-   Customer-wise profit.
-   Average customer satisfaction.
-   Discount analysis by category and region.
-   Quantity by category and return status.
-   Customer satisfaction by category and region.
-   Average quantity by region and return status.
-   Customer and product performance comparisons.

## Key Findings

The dashboards indicate the following patterns based on the displayed
visuals:

-   The **South** region recorded the highest sales, at approximately
    **₹10.56 million**.
-   The **East** region recorded the lowest sales among the displayed
    regions, at approximately **₹6.19 million**.
-   **Technology** was the highest-sales category in the displayed
    category comparison, at approximately **₹12 million**.
-   **Binders** recorded the highest displayed subcategory profit, at
    approximately **₹0.99 million**.
-   The displayed overall average customer satisfaction KPI was
    approximately **3.57**.
-   Monthly sales were relatively steady across the months shown for
    2025, with some month-to-month variation.

> These are observations from the dashboard screenshots. Validate the
> figures against the final cleaned dataset and Power BI measures before
> using them in formal reporting.

## Business Recommendations

Recommendations should be based on verified results from the analysis.
Potential areas for business action include:

-   Review sales strategies in regions with comparatively lower sales.
-   Evaluate pricing, costs, and discount strategies for categories with
    lower profitability.
-   Investigate product quality and customer feedback for products with
    higher return quantities.
-   Consider customer retention initiatives for customers with strong
    profit contributions.
-   Monitor customer satisfaction across regions and product categories.

## Repository Structure

A suggested GitHub repository structure:

``` text
Retail-Sales-Analysis/
│
├── data/
│   └── retail_sales_dataset.csv
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
├── powerbi/
│   └── retail_sales_dashboard.pbix
│
├── screenshots/
│   ├── sales_performance_dashboard.png
│   └── customer_product_dashboard.png
│
└── README.md
```

Update the filenames and folders to match the files actually included in
your repository. Do not upload confidential or restricted data.

## How to Run the Project

1.  Clone or download this repository.
2.  Open the Jupyter notebook in Google Colab or a compatible Python
    environment.
3.  Upload the retail sales CSV file or update the notebook's data path.
4.  Install any missing Python libraries:

``` bash
pip install pandas numpy matplotlib seaborn
```

5.  Run the notebook cells in sequence to perform data preprocessing and
    analysis.
6.  Open the Power BI `.pbix` file in Power BI Desktop to explore the
    dashboards. If prompted, update the data source path.

## Conclusion

This project demonstrates an end-to-end retail analytics workflow using
Python and Power BI. Python supports data cleaning, preprocessing, and
exploratory analysis, while Power BI presents the results through two
interactive dashboards. Together, these tools help transform retail
transaction data into insights about sales performance, customer
behaviour, product trends, and profitability.

## Author

**Priyanka K**

**Project:** Retail Sales Performance, Customer Behaviour &
Profitability Analysis Using Python and Power BI
