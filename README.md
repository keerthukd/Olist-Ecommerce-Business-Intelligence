\# Olist E-Commerce Business Intelligence \& Strategic Sales Analytics



\## Project Overview



An end-to-end Business Intelligence project developed using \*\*Power BI\*\* to analyze Brazilian e-commerce business performance using the Olist dataset (2016–2018).



The project focuses on sales performance, product categories, customer behaviour, regional distribution, payment methods, and delivery operations through an interactive five-page dashboard.



\## Business Objectives



\- Analyze overall sales and order performance.

\- Identify top-performing product categories.

\- Understand customer purchasing behaviour and satisfaction.

\- Evaluate sales and customer distribution across Brazilian states.

\- Monitor delivery efficiency and order cancellations.

\- Analyze payment methods and installment behaviour.



\## Tools \& Technologies



\- Microsoft Power BI Desktop

\- Power Query

\- DAX (Data Analysis Expressions)

\- Data Modeling

\- CSV Dataset



\## Dataset



\*\*Dataset:\*\* Brazilian E-Commerce Public Dataset by Olist



The dataset contains multiple interconnected CSV files covering orders, customers, sellers, products, payments, reviews, and geolocation information.



\*\*Analysis Period:\*\* 2016–2018  

\*\*Geographic Coverage:\*\* Brazil  

\*\*Currency:\*\* Brazilian Real (BRL)



\## Dashboard Pages



\### 1. Executive Overview

\- Total Sales

\- Total Orders

\- Total Customers

\- Average Order Value

\- Delivery Success Rate

\- On-Time Delivery Rate

\- Average Review Score

\- Cancellation Rate

\- Monthly Sales Trend

\- Top Product Categories

\- Order Status Distribution



\### 2. Product Performance Analytics

\- Top 10 Categories by Sales

\- Average Product Price by Category

\- Product Quantity Sold by Category

\- Product Category Sales Contribution



\### 3. Customer Insights \& Behaviour

\- Repeat Customers

\- Repeat Customer Rate

\- Average Customer Rating

\- Low-Rated Reviews

\- Customer Review Distribution

\- Top 10 Cities by Customer Count



\### 4. Regional Sales \& Customer Analysis

\- Total Sales by State

\- Customer Distribution by State

\- Seller Distribution by State

\- Geographic Distribution of Customers

\- Seller State-wise Sales Performance

\- Total Active Sellers



\### 5. Business Performance \& Operational Insights

\- Average Delivery Days

\- On-Time Delivery Rate

\- Cancellation Rate

\- Average Order Approval Time

\- Payment Method Distribution

\- Average Delivery Delay by State

\- Average Installments by Payment Type

\- Cancelled Order Value by State



\## Data Modeling



The project uses a relational data model with fact and dimension tables.



\*\*Fact Tables\*\*

\- Fact\_Orders

\- Fact\_Order\_Items

\- Fact\_Payments

\- Fact\_Reviews



\*\*Dimension Tables\*\*

\- Dim\_Customers

\- Dim\_Products

\- Dim\_Sellers

\- Dim\_Category

\- Dim\_Geolocation

\- Dim\_Zipcode\_Location

\- Dim\_Seller\_Zipcode\_Location



Relationships were configured to support cross-table analysis and interactive filtering.



\## Key DAX Measures



The project includes calculated measures for:



\- Total Sales (BRL)

\- Total Orders

\- Average Order Value

\- Total Customers

\- Total Sellers

\- Delivery Success Rate

\- On-Time Delivery Rate

\- Cancellation Rate

\- Repeat Customer Rate

\- Average Review Score

\- Average Delivery Days

\- Average Delivery Delay

\- Total Freight

\- Average Installments

\- Credit Card Payment Share

\- Positive Review Rate



\## Interactive Features



\- Five-page report navigation

\- Date range slicers

\- Customer state filters

\- Product category filters

\- Order status filters

\- Review score filters

\- Payment method filters

\- Interactive charts and KPI cards



\## Important Metric Definitions \& Limitations



\- Total Sales represents product item prices and excludes freight charges.

\- Sales including freight is calculated separately.

\- The dataset does not contain product cost information; therefore, profit and profit margin are not calculated.

\- Cancelled Sales represents the item value associated with cancelled orders and should not be interpreted as confirmed financial loss.

\- Geographic coordinates based on zipcode prefixes are approximate.



\## Project Structure



```text

Olist\_Ecommerce\_Analytics/

│

├── 01\_Raw\_Data/

├── 02\_Cleaned\_Data/

├── 03\_PowerBI\_Report/

│   └── Olist\_Ecommerce\_Business\_Intelligence.pbix

│

├── 04\_Documentation/

│   └── README.md

│

└── 05\_Screenshots/

```



\## Project Outcome



Developed an interactive five-page Power BI dashboard that transforms raw e-commerce data into structured business intelligence, enabling analysis of sales, products, customers, regional performance, and operational efficiency.



\---



\*\*Project Domain:\*\* E-Commerce Analytics | Business Intelligence | Data Analytics  

\*\*Technology:\*\* Microsoft Power BI | DAX | Power Query





\## Dashboard Preview



\### 1. Executive Overview

\[!\[Executive Overview](../05\_Screenshots/01\_Executive\_Overview.png)](../05\_Screenshots/01\_Executive\_Overview.png)



\### 2. Product Performance

\[!\[Product Performance](../05\_Screenshots/02\_Product\_Performance.png)](../05\_Screenshots/02\_Product\_Performance.png)



\### 3. Customer Insights

\[!\[Customer Insights](../05\_Screenshots/03\_Customer\_Insights.png)](../05\_Screenshots/03\_Customer\_Insights.png)



\### 4. Regional Analysis

\[!\[Regional Analysis](../05\_Screenshots/04\_Regional\_Analysis.png)](../05\_Screenshots/04\_Regional\_Analysis.png)



\### 5. Business Insights

\[!\[Business Insights](../05\_Screenshots/05\_Business\_Insights.png)](../05\_Screenshots/05\_Business\_Insights.png)

