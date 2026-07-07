# Customer Behavior Data Analytics Project

## Overview

This project demonstrates an end-to-end Data Analytics workflow using Python, SQL, and Power BI. The objective is to analyze customer purchasing behavior, clean and transform the data, answer business questions using SQL, and build an interactive dashboard for business insights.

---

## Dataset

The dataset contains customer purchase information, including:

- Customer Demographics
- Product Details
- Purchase Amount
- Category
- Discounts
- Review Ratings
- Shipping Type
- Subscription Status
- Previous Purchases
- Payment Method
- Season
- Location

---

## Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  

- **SQL**
  - MySQL Workbench

- **Visualization**
  - Power BI

- **Environment**
  - Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Imported the dataset into Jupyter Notebook.
- Loaded data using Pandas.

### 2. Exploratory Data Analysis (EDA)

- Examined dataset structure
- Checked missing values
- Analyzed data types
- Generated summary statistics
- Explored distributions and relationships

### 3. Data Cleaning

- Removed duplicate records
- Handled missing values
- Corrected inconsistent data
- Converted data types where necessary

### 4. SQL Analysis

Imported the cleaned dataset into MySQL and solved business problems using SQL.

Some of the analyses include:

- Revenue by Gender
- Top Rated Products
- Customer Spending Analysis
- Subscription vs Non-Subscription Comparison
- Discount Analysis
- Customer Segmentation
- Product Performance
- Revenue Contribution by Age Group

### 5. Dashboard Development

Created an interactive Power BI dashboard featuring:

- KPIs
- Revenue Analysis
- Customer Segmentation
- Product Performance
- Purchase Trends
- Interactive Filters and Slicers

---

## Dashboard

The dashboard provides insights into:

- Total Revenue
- Total Customers
- Average Purchase Amount
- Revenue by Gender
- Top Performing Products
- Subscription Analysis
- Customer Segmentation
- Revenue by Age Group

---

## Results

This project helped identify:

- Customer purchasing patterns
- Revenue trends
- High-performing products
- Customer segments
- Impact of discounts
- Subscription behavior
- Business opportunities through data-driven insights

---

## Project Structure

```
Customer-Behavior-Analytics/
│
├── data/
│   └── ecommerce_customer_behavior.csv
│
├── notebooks/
│   └── ecommerce_costomer_behavior analysis.ipynb
│
├── sql/
│   └── customers_behavior.sql
│
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
│
│
└── README.md
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/customer-behavior-analytics.git
```

2. Install the required Python libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

3. Open the Jupyter Notebook and run the data cleaning and EDA steps.

4. Import the cleaned dataset into MySQL.

5. Execute the SQL queries provided in the `sql` folder.

6. Open the Power BI dashboard (`.pbix`) to explore the interactive visualizations.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Query Writing
- Database Management
- Data Visualization
- Dashboard Development
- Business Insight Generation
- Data Storytelling

---

## Author

**Prathamesh**
