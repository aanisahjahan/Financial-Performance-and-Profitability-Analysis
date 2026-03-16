# Retail Financial Performance & Profitability Analysis
## Project Overview

This project analyses a multi-year retail sales dataset to evaluate revenue performance, profitability drivers, and the financial impact of discount strategies across product categories, customer segments, and regions.

Using exploratory data analysis and an interactive Power BI dashboard, the project investigates how different factors influence profitability and highlights key business insights related to product performance, customer behaviour, and pricing strategies.

The goal of the analysis is to demonstrate how data analytics can support better financial and operational decision-making in a retail environment.

## Dataset

The dataset contains transactional retail sales data across multiple years, capturing information about orders, products, customers, pricing, and profitability.

| Column             | Description                                                                 |
| ------------------ | --------------------------------------------------------------------------- |
| `order_id`         | Unique identifier for each transaction                                      |
| `order_date`       | Date when the order was placed                                              |
| `year`             | Year extracted from the order date for time-based analysis                  |
| `month`            | Month extracted from the order date                                         |
| `year_month`       | Combined year–month field used for trend analysis                           |
| `region`           | Geographic region where the order was placed                                |
| `customer_segment` | Type of customer placing the order (Consumer, Corporate, Small Business)    |
| `product_category` | Product category (Electronics, Furniture, Home Appliances, Office Supplies) |
| `product`          | Specific product purchased                                                  |
| `quantity`         | Number of units sold in the order                                           |
| `revenue`          | Total sales revenue generated from the order                                |
| `cost`             | Operational cost associated with the order                                  |
| `profit`           | Profit generated from the order (Revenue – Cost)                            |
| `discount_rate`    | Discount percentage applied to the order                                    |
| `profit_margin`    | Profit as a percentage of revenue                                           |

## Business Questions

**The analysis was designed to answer the following key questions:**

- Which product categories and products generate the most revenue and profit?

- Which categories operate with the highest and lowest profit margins?

- How do discount levels impact profitability?

- Which customer segments contribute the most revenue and profit?

- Which regions generate the strongest financial performance?

- Are there any revenue trends or seasonal patterns over time?

## Power BI Dashboards
### 1. Performance Overview

<img width="2545" height="1433" alt="1" src="https://github.com/user-attachments/assets/6040083c-f8e8-4302-b902-a0c630dd49ab" />

**Key Insights:**

- The business generated £9.96M in revenue and £1.46M in profit, resulting in an overall profit margin of 14.7% across 12K orders.

- Revenue remains relatively stable over time with no strong seasonal pattern, suggesting consistent demand throughout the year.

- The West region contributes the highest share of revenue, though sales are relatively balanced across regions.

- Electronics dominate revenue generation, accounting for more than half of total sales.

### 2. Profitability Analysis

<img width="2547" height="1433" alt="2" src="https://github.com/user-attachments/assets/5f26a128-e834-492b-9517-96789f921678" />

**Key Insights:**

- Electronics generate the largest share of total profit, primarily due to higher sales volume.

- Office Supplies achieve the highest margins (~33%), but contribute relatively little profit because of lower sales volume.

- The analysis reveals a high-volume, low-margin strategy for electronics, while office supplies operate as high-margin, low-volume products.

- Products such as Laptop, Smartphone, Cabinet, and Vacuum Cleaner are among the strongest contributors to overall profitability.

### 3. Discount Impact

<img width="2547" height="1433" alt="3" src="https://github.com/user-attachments/assets/915258d5-0ef0-4e2e-a044-6b085bebebe1" />

**Key Insights:**

- Profitability declines as discount levels increase, with 0–10% discounts generating the majority of total profit.

- Discounts above 15% significantly reduce profit margins.

- 286 orders resulted in losses, producing approximately £11.48K in total financial loss.

- The analysis suggests that aggressive discounting does not generate enough additional sales to offset margin losses.

### 4. Customer & Regional Performance

<img width="2544" height="1433" alt="4" src="https://github.com/user-attachments/assets/28d25a5b-bbd1-4001-8e8c-af4a1b944021" />

**Key Insights:**

- Corporate customers generate the highest average order value (~£854), indicating larger transactions compared to other segments.

- Revenue and profit are relatively evenly distributed across customer segments, suggesting diversified demand.

- The West region generates the highest total profit, though regional performance is generally balanced.

- Profit margins remain consistent across regions (~14–15%), indicating stable pricing and cost structures.

## Tools & Technologies

**Microsoft Excel:**

- Data cleaning and transformation

- Exploratory data analysis (EDA)

- Pivot table analysis for revenue, margin, and product performance

**Power BI:**

- Data modelling

- DAX measures for KPI calculations

- Interactive dashboard development

## Analytical Techniques

- **Revenue trend analysis**

- **Profitability and margin analysis**

- **Product performance analysis**

- **Discount impact analysis**

- **Customer segmentation analysis**

- **Regional performance analysis**
