# Decodelabs-Project-2-Exploratory-Data-Analysis (EDA)


**Tool Used:** Microsoft Excel  
**Dataset:** Sales Transaction Dataset  
**Total Records:** 1,200 rows  
**Internship:** DecodeLabs 

## Project Overview
This project involved performing Exploratory Data Analysis on a sales 
dataset to uncover hidden patterns, trends, and outliers. 
The goal was to transform raw sales data into meaningful business insights using 
Excel Pivot Tables, charts, and statistical methods.

---

## Dataset Columns
Customer ID, Order ID, Date, Product, Quantity, Unit Price, 
Shipping Address, Payment Method, Order Status, Tracking Number, 
Items In Cart, Coupon Code, Referral Source, Total Unit Price

---

## Summary Statistics

| Metric | Quantity | Unit Price | Items In Cart | Total Price |
|--------|----------|------------|---------------|-------------|
| Mean   | 2.95     | $356       |  5.49         | $1,054      |
| Median | 3        | $364       |  5            | $824        |
| Min    | 1        | $11        |  1            | $11         |
| Max    | 5        | $700       |  10           | $3,456      |
| Sum    | 1200     | $427,695   |  1200         | $1,264,762  |

![Summary Table](Summary%20Table.jpg)

---

## Key Findings

### 1. Revenue Per Product and Payment Method
- Total revenue across all products was **$1,264,762**
- **Chair** and **Printer** were the top revenue generators 
at approximately **$195,000 each**
- **Phone** recorded the lowest revenue at **$151,722** 
suggesting low demand or pricing issues
- **Online payment** was the most preferred method with 
**258 transactions**
- **Gift Card** was the least used payment method at **230 orders**

![Revenue by Product and Payment Method per Order](Revenue%20by%20Product%20and%20Payment%20method%20per%20Order.jpg)

---

### 2. Quantity Per Product and Order Status
- **Chair** was the highest selling product with **562 units sold**
- **Phone** recorded the lowest units sold at **411**, this is
consistent with its low revenue performance
- Only **231 orders** were successfully delivered out of 1,200, that is 
less than 20% delivery success rate
- **250 orders were cancelled** tis is the highest across all statuses
- **247 orders were returned** raising concerns about 
product quality or customer satisfaction
- **237 orders are pending** and **235 are shipped**

![Quantity per Product and Order Status](Quantity%20per%20Product%20and%20Order%20Status.jpg)

---

### 3. Customer Acquisition by Referral Source
- **Instagram** was the most effective customer acquisition 
channel bringing in **259 customers**
- **Direct Referral** was the weakest channel with only 
**222 customers** this is suggesting an opportunity to build 
a referral incentive program

![Customer Acquisation by referral source](Customer%20Acquisation%20by%20referral%20source.jpg)

---

### 4. Monthly Sales Trend
- **June** recorded the highest sales across all months
- **September** recorded the lowest sales
- This seasonal pattern suggests the business should plan 
inventory and marketing campaigns around peak and 
low periods accordingly

![Monthly Sales Trend](Monthly%20Sales%20Trend.jpg)

---

### 5. Outlier Detection
- Using the **IQR method**, **8 outliers** were identified 
in the Total Unit Price column out of 1,200 transactions
- This represents less than **1% of the dataset**
- Upon investigation, all 8 outliers were classified as 
**noise** — data points clustering near the upper bound 
rather than genuine anomalies
- This confirms overall **data integrity** across the dataset

![Outlier Metrics](Outlier%20Metrics.jpg)
![Outlier](Outlier.jpg)

---

## Recommendations

1. **Investigate Phone performance** — Phone is underperforming 
in both revenue and quantity. A pricing review or targeted 
marketing campaign is recommended.

2. **Address delivery failures** — With less than 20% of orders 
successfully delivered, the logistics and fulfillment process 
needs urgent review.

3. **Reduce cancellations and returns** — 250 cancellations and 
247 returns out of 1,200 orders is significantly high. 
Root cause analysis is needed.

4. **Leverage Instagram** — As the top referral source, 
increasing investment in Instagram marketing could drive 
further customer acquisition.

5. **Plan for seasonality** — June peaks and September dips 
suggest a need for seasonal inventory planning and 
promotional campaigns ahead of low periods.

---

## Skills Demonstrated
- Descriptive Statistics (Mean, Median, Min, Max, Sum)
- Pivot Tables and Data Aggregation
- Data Visualization (Bar Charts, Line Charts)
- Outlier Detection using IQR Method
- Trend Analysis
- Business Insight Generation

---

## Dataset
[Download Dataset](Dataset%20for%20Data%20Analytics.xlsx)
