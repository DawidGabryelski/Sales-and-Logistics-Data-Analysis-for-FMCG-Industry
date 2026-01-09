# Overview
The project focuses on the operational analysis of an FMCG company between 2021 and 2023. The primary goal was to link sales and logistics data to evaluate the impact of product availability on financial performance and identify supply chain inefficiencies.

# Business Problem: Data Silos and Stockout Impact
In the analyzed enterprise, sales and warehouse data functioned as separate datasets. The main issue was the lack of visibility regarding the impact of lead time (6-7 days) on stockouts. Without integrated analytics, it was impossible to assess whether lost revenue resulted from demand fluctuations or delivery scheduling errors.

# Methodology
Power Query (ETL process) was used for data cleaning and transformation, and Microsoft Power BI Desktop was used for modeling. A Star Schema data model was implemented. Calculations were based on DAX measures incorporating non-additive inventory logic and stock rotation indices.
# Visualization & Data Model

## Data Model
<img width="1137" height="652" alt="Data Model" src="https://github.com/user-attachments/assets/6b49cf47-bcdd-4c29-9d89-73781d8a3d8c" />

## Yearly Analysis
<img width="1122" height="632" alt="Time Y page" src="https://github.com/user-attachments/assets/8aa26329-1af3-4602-9da2-f134b0832fb5" />

## Monthly Analysis
<img width="1122" height="640" alt="Time M Page" src="https://github.com/user-attachments/assets/a28cec13-6b2a-4a06-b761-11c5c57ab41e" />

## Product Data Analysis
<img width="1122" height="628" alt="Product Page" src="https://github.com/user-attachments/assets/cd94896e-0ddf-41e3-bce9-b7f4e16c2b23" />

## Stores Analysis
<img width="1118" height="632" alt="Stores Page" src="https://github.com/user-attachments/assets/e185493a-2589-44a8-8a3b-17170f374b2e" />

## Storage Analysis
<img width="1127" height="633" alt="Storage" src="https://github.com/user-attachments/assets/762074e2-4114-4ea0-b183-6c426570d537" />

# Final Results
1. The network maintains a weighted margin of 38-39% with stable revenue growth throughout the analyzed period.
2. 71% of stockouts occur on business days, confirming errors in delivery planning rather than sudden demand spikes.
3. The "Beverages" and "Snacks" categories generate the highest turnover while being the most vulnerable to inventory depletion.
4. The 6-7 day Lead Time is too long relative to the current rotation rate, leading to regular exhaustion of safety stocks.
5. The Average Selling Price (ASP) metric showed pricing consistency across all locations; revenue variances between cities are driven solely by sales volume.
   
# Recommendations
1. Increase safety stock levels for high-rotation categories (Beverages, Snacks) to eliminate mid-week stockouts.
2. Shorten Lead Times or adjust order frequency during business days.
3. Implement promotional activities for the Home Care category to boost sales volume while maintaining its current margin.

# Data

Orginal csv file is too large for attaching it to this repository. Here is a link to that data.
https://www.kaggle.com/datasets/robertocarlost/fmcg-multi-country-sales-dataset
