# Instacart Business Analysis (Excel)

## Project Overview

This project explores Instacart grocery-order data using **Microsoft
Excel** to identify product and department-level purchasing patterns.
The workbook contains summary tables showing product counts by
department and the most frequently appearing products in the analysed
order-product records.

The analysis is intended to help understand which departments and
products account for the largest share of product activity.

## Objectives

-   Summarise product activity across departments.
-   Identify the most frequently appearing products.
-   Highlight categories and products that may be important for business
    and inventory decisions.
-   Practise data organisation and summarisation using Excel.

## Tools Used

-   **Microsoft Excel** -- data exploration and summary analysis
-   **Excel PivotTable-style summaries** -- aggregation of product
    counts by department and product

## Dataset

The project files are based on the Instacart Market Basket Analysis
dataset structure. The supplied CSV files are:

  -----------------------------------------------------------------------
  File                                Description
  ----------------------------------- -----------------------------------
  `orders.csv`                        Order-level information, including
                                      user, order sequence, day and hour

  `order_products__train.csv`         Products included in orders, cart
                                      position and reorder indicator

  `products.csv`                      Product names and their aisle and
                                      department identifiers

  `aisles.csv`                        Aisle ID and aisle name mapping

  `departments.csv`                   Department ID and department name
                                      mapping
  -----------------------------------------------------------------------

The Excel workbook provided is
`Instacart_Business_Analysis_Complete.xlsx`.

## Workbook Contents

The workbook includes the following summary sheets:

### 1. Department Analysis (`Sheet1`)

A summary of product counts by department.

Key figures in the workbook: - Produce: **409,087** - Dairy eggs:
**217,051** - Snacks: **118,862** - Beverages: **114,046** - Frozen:
**100,426** - Grand total shown: **1,384,617**

### 2. Top Products (`Top Products`)

A summary of the ten most frequently appearing products.

  Product                     Count
  ------------------------ --------
  Banana                     18,726
  Bag of Organic Bananas     15,480
  Organic Strawberries       10,894
  Organic Baby Spinach        9,784
  Large Lemon                 8,135
  Organic Avocado             7,409
  Organic Hass Avocado        7,293
  Strawberries                6,494
  Limes                       6,033
  Organic Raspberries         5,546

The displayed total for this top-products summary is **95,794**.

## Key Observations

-   Produce has the highest product count among the departments in the
    workbook.
-   Dairy eggs is the second-highest department.
-   Banana is the most frequently appearing product in the top-products
    summary.
-   Several of the leading products are fruits or vegetables.

These observations describe the counts displayed in the workbook; they
do not, by themselves, establish revenue, profit, customer preferences,
or causal explanations.

## Project Files

``` text
instacart-business-analysis/
├── Instacart_Business_Analysis_Complete.xlsx
├── orders.csv
├── order_products__train.csv
├── products.csv
├── aisles.csv
├── departments.csv
└── README.md
```

## How to Use

1.  Download the Excel workbook and the CSV files.
2.  Open `Instacart_Business_Analysis_Complete.xlsx` in Microsoft Excel.
3.  Review the `Sheet1` tab for department-level counts.
4.  Review the `Top Products` tab for the leading products.
5.  Use the supplied CSV files if you want to extend the analysis or
    build additional Excel summaries.

## Scope and Limitations

The supplied workbook contains two populated summary sheets (`Sheet1`
and `Top Products`). The `Products`, `Departments`, `Aisles`, and
`README` tabs are present but empty in the provided workbook. The README
therefore documents only the populated summaries and supplied source
files. Counts are product/order-record counts, not sales revenue or
profit.

## Conclusion

This Excel project provides a basic business view of Instacart product
activity by department and product. It highlights the leading
departments and products in the workbook and provides a starting point
for further analysis of ordering patterns, reorders, and customer
behaviour.
