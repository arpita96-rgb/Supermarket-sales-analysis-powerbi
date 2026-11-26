# 📖 Data Dictionary – Supermarket Sales Analysis

## Project Overview
This data dictionary describes the key fields used in the Supermarket Sales Analysis project. It provides an understanding of the dataset structure, column definitions, and their business relevance.

## 1. Customer & Transaction Details

| Column Name | Description | Data Type |
|---|---|---|
| Invoice_ID | Unique transaction identification number | Text |
| Customer_ID | Unique customer identification number | Text |
| Gender | Customer gender | Text |
| Membership_Type | Customer membership category | Text |
| Payment | Payment method used for transaction | Text |

## 2. Product Details

| Column Name | Description | Data Type |
|---|---|---|
| Product | Name of the purchased product | Text |
| Category | Product category | Text |
| Quantity | Number of units sold | Whole Number |
| Customer_Rating | Customer rating for the product | Whole Number |

## 3. Sales & Financial Details

| Column Name | Description | Data Type |
|---|---|---|
| Total | Total transaction revenue | Decimal |
| Profit | Profit generated from the transaction | Decimal |
| Discount | Discount applied to the transaction | Decimal |
| Sales_Target | Target sales value | Decimal |

## 4. Geographical & Time Details

| Column Name | Description | Data Type |
|---|---|---|
| City | City where the transaction occurred | Text |
| Branch | Store branch identification | Text |
| Date | Transaction date | Date |
| Month | Month of transaction | Text |
| Day | Day of transaction | Whole Number |

## 5. Key Business Metrics

| KPI | Description |
|---|---|
| Total Revenue | Sum of all transaction revenue |
| Total Profit | Total profit generated |
| Profit Margin | Profit as a percentage of revenue |
| Sales Growth | Percentage change in sales over time |
| Total Orders | Number of unique transactions |
| AOV | Average revenue per order |
| Total Customers | Number of unique customers |
| Customer Loyalty Rate | Percentage of customers classified as loyal |

## 6. Business Usage

The dataset supports:
- Sales and revenue performance analysis.
- Product-wise and category-wise performance tracking.
- Customer purchasing behaviour analysis.
- Branch-wise and city-wise sales comparison.
- Profitability and discount analysis.
- Monthly and daily sales trend monitoring.
