# Coffee Shop Sales Analysis

<img width="1425" height="630" alt="css_db" src="https://github.com/user-attachments/assets/4ba5031e-ea5a-4501-b981-027df6c66f99" />


## 📌 Project Overview

This project analyzes coffee shop transaction data using Microsoft Excel to understand revenue performance, transaction patterns, product performance, and customer ordering activity.

The project follows an end-to-end data analytics workflow:

**Raw Data → Data Cleaning → Data Analysis → Dashboard → Business Insights**

The final dashboard provides an interactive view of coffee shop sales performance across different products, categories, store locations, days, hours, and months.

---

## 🎯 Business Objective

The main objective of this project is to analyze coffee shop transaction data and answer important business questions such as:

- What is the overall revenue generated?
- How many transactions were recorded?
- How does revenue change from month to month?
- Which product categories have the highest transaction volume?
- Which products generate the highest revenue?
- Which products have the highest number of transactions?
- How does transaction activity vary by day of the week?
- Which hours have the highest transaction activity?
- How does sales activity differ across store locations?
- What patterns can be identified from the transaction data?

---

## 📊 Dataset

The project uses the **Coffee Shop Sales** dataset from the Maven Analytics Data Playground.

The dataset contains transaction-level coffee shop sales information that can be used to analyze revenue, transaction volume, products, categories, store locations, dates, and times.

The dataset was prepared and analyzed using Microsoft Excel before being presented through an interactive dashboard.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel Slicers
- Data Cleaning
- Data Transformation
- Data Analysis
- Data Visualization
- Dashboard Development

---

## 🔄 Project Workflow

The project followed an end-to-end data analytics workflow:

**Raw Data → Data Cleaning → Data Analysis → Dashboard → Business Insights**

### 1. Data Preparation

The raw coffee shop transaction data was imported into Excel and reviewed to understand the available fields and structure of the dataset.

The data contains information related to:

- Transaction IDs
- Products
- Product categories
- Revenue
- Store locations
- Transaction dates
- Transaction times
- Quantity/transaction activity

---

### 2. Data Cleaning & Transformation

The raw dataset was prepared for analysis by reviewing and transforming the data into a suitable format.

The preparation process included:

- Reviewing the raw dataset
- Checking data types
- Preparing date-related fields
- Preparing time-related fields
- Organizing transaction information
- Removing or handling unnecessary data where required
- Preparing the final dataset for analysis



---

### 3. Data Analysis

The cleaned dataset was analyzed using Excel PivotTables and other analytical features.

The analysis focused on:

- Monthly revenue
- Product category transaction volume
- Product-level transaction performance
- Product revenue
- Day-of-week transaction patterns
- Hour-of-day transaction patterns
- Store location analysis


---

## 📈 Key Performance Indicators

The final dashboard provides several important performance measures.

### Total Transactions

**144,919**

The dataset contains 144,919 recorded transactions.

### Total Revenue

**$629,499**

The dashboard records total revenue of $629,499.

### Store Locations

The dashboard allows analysis across three store locations:

- Astoria
- Hell's Kitchen
- Lower Manhattan

---

## 🔍 Key Analysis Areas

### 1. Monthly Revenue Analysis

The dashboard tracks total revenue by month to identify changes in revenue performance over time.

The monthly revenue trend shows increasing revenue toward the later months of the analyzed period, with June recording approximately **$166,486** in revenue.

---

### 2. Product Category Analysis

Transaction volume was analyzed across different product categories.

The dashboard shows categories including:

- Coffee
- Tea
- Bakery
- Drinking Chocolate
- Flavours
- Loose Tea
- Coffee Beans
- Packaged Chocolate
- Branded

Coffee has the highest transaction volume among the displayed categories, with **58,416 transactions**.

Tea follows with **45,449 transactions**.

---

### 3. Day-of-Week Analysis

Transactions were analyzed across each day of the week to understand customer activity patterns.

The dashboard allows comparison between:

- Sunday
- Monday
- Tuesday
- Wednesday
- Thursday
- Friday
- Saturday

Friday records the highest transaction volume among the displayed days, with **21,701 transactions**, while Saturday records the lowest with **20,510 transactions**.

---

### 4. Hour-of-Day Analysis

The dashboard analyzes transaction activity by hour to identify periods of higher and lower customer activity.

The highest transaction activity shown in the dashboard occurs around **10 AM**, with **18,545 transactions**.

Transaction activity is considerably lower during the later evening hours.

---

### 5. Product-Level Analysis

The product analysis table compares products using:

- Number of transactions
- Revenue generated

For example, the dashboard shows:

| Product | Transactions | Revenue |
|---|---:|---:|
| Barista Espresso | 16,403 | $91,406 |
| Brewed Chai Tea | 17,183 | $77,082 |
| Gourmet Brewed Coffee | 16,912 | $70,035 |
| Hot Chocolate | 11,468 | $72,416 |
| Brewed Black Tea | 11,350 | $47,932 |

This allows product performance to be compared from both transaction volume and revenue perspectives.

---

### 6. Store Location Analysis

The dashboard includes an interactive store-location slicer containing:

- Astoria
- Hell's Kitchen
- Lower Manhattan

Users can select a location to interactively filter the dashboard and analyze the selected store's performance.

---

## 💡 Key Business Insights

Based on the dashboard analysis:

- The dataset contains **144,919 transactions**.
- Total revenue across the analyzed data is **$629,499**.
- Revenue increases substantially toward the later months of the analyzed period.
- **Coffee** has the highest transaction volume among the displayed product categories.
- **Tea** is the second-highest transaction category by volume.
- Friday records the highest transaction activity among the displayed days.
- Saturday records the lowest transaction activity among the displayed days.
- Transaction activity is highest around the morning period, particularly around **10 AM**.
- Product performance differs when comparing transaction volume with revenue, showing why both metrics are useful for analysis.
- Store-level performance can be explored interactively using the store-location slicer.
