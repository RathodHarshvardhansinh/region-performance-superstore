# Region Performance Analysis | Superstore

> Task 18 | Data Analytics Track | Veda Technology Internship
> **Author:** Rathod Harshvardhansinh J

## Overview
This project compares sales and profit across regions in the Superstore dataset. It practices grouping, comparison and ranking, and ends with a region summary and a bar chart.

## Objective
Practice grouping and comparison by finding which regions perform best and worst, and why sales alone is not enough to judge them.

## Tools Used
- Microsoft Excel (Pivot Tables, charts)
- Power BI (dashboard and bar chart)

## Dataset
- **Superstore** sales dataset (Region, Sales, Profit, Category, etc.)

## Approach
1. Loaded the Superstore dataset and checked for missing values and duplicates.
2. Grouped the data by **Region** and aggregated **Total Sales** and **Total Profit**.
3. Calculated **Profit Margin (%) = Profit / Sales x 100** for each region.
4. Ranked regions by sales, profit and profit margin.
5. Built a bar chart comparing sales and profit across regions.
6. Wrote down insights and recommendations.

## Deliverables
| Deliverable | File |
|---|---|
| Region summary | `region_summary.xlsx` |
| Power BI report | `region_performance.pbix` |

## Region Summary
> Replace with your own numbers from your pivot table.

| Rank | Region | Total Sales | Total Profit | Profit Margin (%) |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |

## Key Insights
- **Top region by sales:** _(name, value)_
- **Top region by profit:** _(name, value)_
- **Lowest profit margin:** _(name, value)_
- A region with high sales can still have low profit, so both metrics must be compared.

## Why compare profit with sales?
Sales shows how much revenue a region generates, but not whether that revenue is profitable. Discounts and costs can make a high-sales region less valuable than a smaller, more profitable one.

## How I rank regions
I rank by **profit and profit margin first**, with sales as a secondary measure. This shows which regions create real value, not just volume.

## Outcome
The analysis showed how regional performance differs and which regions need attention (for example, reducing discounts where margin is low).

## Repository Structure
```
region-performance-superstore/
|-- README.md
|-- data/
|   `-- Superstore.csv
|-- region_summary.xlsx
|-- region_performance.pbix
```

## Author
**Rathod Harshvardhansinh J** | Data Analytics Intern, Veda Technology
