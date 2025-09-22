# 📊 E-Commerce Analysis – RFM & CLV Segmentation

## 📌 Project Overview

This project focuses on **exploratory data analysis (EDA)** and **dashboard creation** for a dataset containing over 500,000 e-commerce transactions.

The main goal was to transform raw data into actionable business insights by answering key questions related to customer behavior, profitability, and operational efficiency.

## 📂 Data Source

* **Online Retail** dataset from the UCI Machine Learning Repository
* Historical data from 2010 to 2011
* **Data fields:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## 🛠️ Data Preparation

This was a critical and time-consuming phase. The following steps were taken to ensure data quality:
* Separated raw data into two structured tables: **Sales** and **Returns**.
* Cleaned and standardized the data by removing duplicates, empty values, and irrelevant records (e.g., non-product transactions).
* Corrected and standardized country names (e.g., "EIRE" to "Ireland").
* Added new, calculated columns: **TotalPrice**, **Year**, **Month**, **Day**, **DayOfWeek**, and **Hour** for time-based analysis.

## 🔎 Key Analyses

The following analyses were performed to answer key business questions:
* **RFM (Recency, Frequency, Monetary Value) Analysis:** Segmented customers into groups like **Champions**, **Loyal Customers**, and **At Risk** to understand their behavior.
* **CLV (Customer Lifetime Value) Analysis:** Assessed the long-term value of each customer segment.
* **Correlation Analysis:** Explored the relationship between RFM variables, discovering a strong positive correlation between frequency and monetary value.
* **Geographical Analysis:** Visualized and compared sales and returns across different countries.
* **Temporal Analysis:** Identified key sales trends by month, day of the week, and hour of the day.
* **Operational Analysis:** Identified the most returned products and the financial loss they generate.

## 📊 Dashboard in Power BI

An interactive dashboard was built in **Power BI** to visualize key metrics and insights from the analysis. The dashboard allows users to:
* Filter data by **Month**, **Segment**, and **Country**.
* Compare key customer segments side-by-side.
* Analyze operational performance, including returns and product profitability.
* Identify key sales trends.

## 🚀 Tools & Technologies

* **Power BI** – data modeling, analysis, and dashboard creation
* **DAX** – for creating key performance metrics and columns
* **Excel** – for data cleaning and manipulation, initial data exploration and validation

## 📈 Key Outcomes & Business Recommendations

The project successfully transformed raw transaction data into actionable business strategies:
* **Customer-Centric Growth:** Identified **Champions** as the most valuable segment and recommended a focus on retention through personalized marketing campaigns.
* **Operational Efficiency:** Pinpointed the most returned products and identified **UK** as a key market for optimization due to a high volume of returns.
* **Strategic Insights:** Provided clear evidence of a strong correlation between purchase frequency and spending, supporting investment in loyalty programs.

<img width="1309" height="738" alt="5" src="https://github.com/user-attachments/assets/4f8ca70e-3880-464b-97fe-815eb4dcec8e" />
<img width="1310" height="738" alt="3" src="https://github.com/user-attachments/assets/f4d4ed57-d70a-4386-88b3-b985ae50735a" />
<img width="1312" height="739" alt="2" src="https://github.com/user-attachments/assets/98339ec5-e117-454c-a8f4-fe0402f47ccd" />
<img width="1316" height="736" alt="4" src="https://github.com/user-attachments/assets/4e0be7cb-11c0-4f4a-8ef7-f9a082ec540e" />
<img width="1307" height="728" alt="1" src="https://github.com/user-attachments/assets/685841e7-6a89-477e-933b-c250eb10c186" />
