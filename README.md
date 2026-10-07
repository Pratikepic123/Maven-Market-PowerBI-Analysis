# Maven Market Sales & Performance Analysis – Power BI

## 📊 Project Overview

This project is an interactive **Power BI dashboard** created using the Maven Market dataset.

The dashboard focuses on analyzing business performance through **transactions, profit, profit margin, product brands, returns, revenue trends, customers, stores, and regions**.

The project demonstrates the use of **Power Query, data modeling, DAX, KPI analysis, interactive visualizations, and business insights** to convert raw business data into an interactive business intelligence dashboard.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall transaction performance.
- Monitor profit and profit margin.
- Analyze product brand performance.
- Track product returns and return rates.
- Analyze performance across countries and regions.
- Monitor weekly revenue trends.
- Compare revenue against targets.
- Identify important business performance insights.
- Present findings through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Transformation
- Data Visualization
- Business Intelligence
- KPI Analysis

---

## 📂 Dataset

The Maven Market dataset contains business information related to customers, products, transactions, stores, regions, and product returns.

The Power BI data model contains the following major tables:

- Customers
- Transaction_Data
- Products
- Stores
- Regions
- Calendar
- Return_Data

---

## 🧩 Data Model

The project uses a relational data model to connect the different business entities.

### Main Tables

**Customers**
- customer_id
- customer_acct_num
- customer_address
- customer_city
- customer_country
- birth_year
- birth_date
- Current_Age
- account_open_date

**Transaction_Data**
- customer_id
- product_id
- quantity
- stock_date
- store_id
- transaction_date
- calculated/measured transaction metrics

**Products**
- product_id
- product_brand
- product_name
- product_sku
- product_retail_price
- product_cost
- low_fat
- recyclable
- discount_price
- price_tier

**Stores**
- store_id
- store_city
- store_country
- store_code
- region_id
- full_address
- first_opened_date
- last_remodel_date
- grocery_sqft

**Regions**
- region_id
- sales_region
- sales_district

**Calendar**
- Date
- Day Name
- Month Name
- Quarter
- Start of Month
- Start of Week
- Weekend
- Year
- End of Month

**Return_Data**
- product_id
- quantity
- return_date
- store_id
- return-related calculated metrics

---

## 🔄 Data Preparation

The data was prepared and transformed in Power BI before creating the dashboard.

The preparation process included:

- Importing the required datasets.
- Checking data types.
- Transforming data using Power Query.
- Creating relationships between tables.
- Creating a dedicated Calendar table.
- Preparing data for time-based analysis.
- Creating calculated measures and metrics.
- Organizing the data model for interactive reporting.

---

## 🧮 DAX & Calculated Metrics

DAX was used to create business metrics and calculations for the dashboard.

The model contains metrics related to:

- Total Transactions
- Total Profit
- Profit Margin
- Return Rate
- Revenue
- Current Month Transactions
- Current Month Profit
- Current Month Returns
- Weekly Revenue
- Revenue Target
- Quantity Returned

These calculations are used throughout the dashboard to dynamically analyze business performance.

---

# 📈 Dashboard

## Topline Performance

The main dashboard provides a high-level view of Maven Market's performance.

### Key KPI Cards

The dashboard displays:

- **Current Month Transactions**
- **Current Month Profit**
- **Current Month Returns**

The dashboard also provides an overall product-brand performance table containing:

- Product Brand
- Total Transactions
- Total Profit
- Profit Margin
- Return Rate

---

## 🏷️ Product Brand Analysis

The product-brand table allows comparison of different brands based on:

- Number of transactions
- Total profit
- Profit margin
- Return rate

This helps identify brands with stronger transaction performance and profitability.

The dashboard includes brands such as:

- Hermanos
- Ebony
- Tell Tale
- Tri-State
- High Top
- Nation
- Best Choice
- Horatio
- Fort West
- East
- Sunset
- Carrington
- Red Wing
- Big Time
- Cormorant
- Imagine
- Super
- Denny
- High Quality
- Golden
- BBB Best
- PigTail
- Plato
- Landslide
- CDR
- Better
- Carlson
- Pleasant
- Just Right
- Bravo

---

## 🌎 Geographic Analysis

A geographic map is used to visualize store/business activity across locations.

The dashboard provides geographic analysis across countries including:

- USA
- Mexico
- Canada

This allows users to explore the geographical distribution of business activity.

---

## 📊 Country Performance

A treemap is used to compare performance across countries.

The dashboard includes:

- USA
- Mexico
- Canada

This provides a quick visual comparison of business contribution by country.

---

## 📅 Weekly Revenue Trending

A weekly revenue chart is used to analyze revenue performance over time.

The visualization helps identify:

- Weekly revenue fluctuations
- Periods of higher revenue
- Periods of lower revenue
- Overall revenue trends

The dashboard covers the 1998 business period represented in the dataset.

---

## 🎯 Revenue vs Target

A gauge visual is used to compare revenue against the defined target.

The dashboard displays:

- Current Revenue: approximately **$119.48K**
- Target: **$120K**

This provides a quick view of progress toward the revenue target.

---

# 📝 Performance Notes

A separate **Performance Notes** page summarizes important business findings from the dashboard.

### Insight 1 – Portland Sales

Portland reached **1,000 sales in December**, helping close out the year strongly.

### Insight 2 – High Top Product Returns

High Top product returns in Mexico increased from **4 to 8**, resulting in a **1.2% return rate**.

### Insight 3 – Plato Profit Margin

Plato products achieved the strongest overall profit margin at **63.55%** in 1998.

These notes demonstrate how dashboard analysis can be converted into concise business insights.

---

# 📌 Key Dashboard Metrics

The dashboard shows the following overall performance figures:

- **Total Transactions:** 113,668
- **Total Profit:** $449,627
- **Overall Profit Margin:** 59.94%
- **Overall Return Rate:** 1.00%

The current-month KPI section shows:

- **Current Month Transactions:** 18,325
- **Current Month Profit:** $71.68K
- **Current Month Returns:** 476

---

# 📊 Dashboard Visualizations

The project uses several Power BI visualizations, including:

- KPI Cards
- Tables
- Matrix-style analysis
- Geographic Maps
- Treemap
- Weekly Revenue Column Chart
- Gauge Chart
- Interactive Filters
- Country Selection
- Product Brand Analysis

These visualizations allow users to explore business performance from different perspectives.

---

# 🎛️ Dashboard Interactivity

The dashboard provides interactive analysis through:

- Country selection
- Product brand analysis
- Geographic visualization
- Interactive Power BI visuals
- Dynamic KPI calculations
- Cross-filtering between visuals

Users can interact with the dashboard to analyze different parts of the business.

---

# 🔍 Key Business Insights

Based on the dashboard analysis:

1. The business recorded **113,668 total transactions**.
2. Total profit was approximately **$449.63K**.
3. The overall profit margin was approximately **59.94%**.
4. The overall return rate was approximately **1.00%**.
5. Plato products achieved a **63.55% profit margin** in 1998.
6. High Top product returns in Mexico increased from **4 to 8**.
7. Portland reached **1,000 sales in December**.
8. Revenue reached approximately **$119.48K** against a **$120K target** in the displayed revenue-vs-target analysis.
