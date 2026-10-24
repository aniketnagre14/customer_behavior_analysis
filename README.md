# customer_behavior_analysis
Data Analytics Project showcasing customer behavior analysis using Python ,SQL and Power bi
# Customer Shopping Behavior Analysis

**An End-to-End Data Analytics Project Using Python, SQL, and Power BI**

## Project Overview

The **Customer Shopping Behavior Analysis** project focuses on analyzing customer purchasing patterns, shopping preferences, spending behavior, and product performance to generate actionable business insights.

This project demonstrates an end-to-end data analytics workflow, starting with data extraction and cleaning in Python, followed by database storage and business analysis using SQL, and finally the development of an interactive Power BI dashboard for data-driven decision-making.

The goal is to help businesses understand their customers, identify purchasing trends, evaluate product performance, and develop effective marketing strategies.

## Project Objectives

- Analyze customer shopping behavior and purchasing patterns.
- Identify high-value customer segments.
- Evaluate sales performance across product categories.
- Analyze spending patterns based on customer demographics.
- Understand the relationship between discounts, subscriptions, and purchasing decisions.
- Answer business questions using SQL queries.
- Build an interactive dashboard to communicate key performance indicators (KPIs) and business insights.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing, cleaning, and analysis |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical operations |
| Jupyter Notebook | Data exploration and analysis workflow |
| PostgreSQL / MySQL / MS SQL Server | Data storage and SQL-based analysis |
| SQL | Business queries, aggregations, and customer analysis |
| Power BI | Interactive dashboard and visualization |
| Git & GitHub | Version control and project documentation |

*Note: Use the database technology you actually implemented in your project.*

## Project Workflow

```text
Raw Customer Dataset
        |
        v
Python & Jupyter Notebook
(Data Import, Exploration, Cleaning)
        |
        v
SQL Database
(Data Storage & Business Queries)
        |
        v
Power BI
(Interactive Dashboard & KPIs)
        |
        v
Business Insights & Recommendations
```

## Dataset Description

The dataset contains customer shopping information, including customer demographics, product categories, purchase amounts, discounts, subscription status, and shopping preferences.

Key data fields may include:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Season
- Review Rating
- Subscription Status
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Shipping Type
- Payment Method

The dataset is used to explore customer behavior and identify meaningful patterns in purchasing decisions.

## Project Implementation

### 1. Data Import, Exploration, and Cleaning — Python

**Notebook:** `Customer_Shopping_Behavior_Analysis.ipynb`

Tasks performed:

- Imported the dataset using Pandas.
- Explored the dataset structure, columns, data types, and statistical summaries.
- Identified missing values and checked for duplicate records.
- Handled missing values using appropriate data-cleaning techniques.
- Standardized categorical values and transformed data where required.
- Prepared the cleaned dataset for database storage and further analysis.

### 2. Database Integration and SQL Analysis

**SQL File:** `customer_behavior_sql_queries.sql`

The cleaned dataset is loaded into a relational database using Python and SQLAlchemy or an appropriate database connector.

Tasks performed:

- Created a database and the required table structure.
- Connected Python to the SQL database.
- Loaded the cleaned customer dataset into the database.
- Executed SQL queries to answer business questions.
- Used filtering, grouping, aggregate functions, conditional logic, and sorting to analyze customer behavior.

**Example business questions:**

1. What is the total purchase amount across the dataset?
2. Which product categories generate the highest sales?
3. How does customer spending differ by gender?
4. Which age groups contribute the most to purchases?
5. Do subscribed customers spend differently from non-subscribers?
6. How do discounts influence customer purchasing behavior?
7. Which customers have made the most previous purchases?
8. What are the most common purchase frequencies?
9. Which locations have the highest purchase activity?
10. How do review ratings vary across product categories?

### 3. Interactive Dashboard — Power BI

**Dashboard File:** `customer_behavior_dashboard.pbix`

Power BI is used to transform the analyzed data into an interactive business intelligence dashboard.

Potential dashboard components include:

- **KPI Cards:** Total Purchase Amount, Total Customers, Average Purchase Amount, and Average Review Rating.
- **Category Analysis:** Purchase amount by product category.
- **Demographic Analysis:** Customer spending by age group and gender.
- **Subscription Analysis:** Comparison of subscribed and non-subscribed customers.
- **Discount Analysis:** Purchasing patterns based on discount usage.
- **Purchase Frequency:** Analysis of weekly, monthly, and other purchase intervals.
- **Customer Preferences:** Popular products, payment methods, and shipping types.
- **Interactive Filters:** Category, gender, age group, season, and subscription status, where supported by the model.

The dashboard helps users explore customer trends and compare business performance across different segments.

## Key Business Insights

The project is designed to uncover insights such as:

- Which customer segments contribute most to overall spending.
- Which categories attract the greatest purchase volume or revenue.
- Whether subscription status is associated with different spending patterns.
- How customer age and gender relate to shopping preferences.
- Which promotional and discount patterns are associated with purchases.
- How customer ratings differ across products or categories.
- Which purchasing behaviors could help businesses improve customer retention.

*Actual findings should be added after validating the results from your SQL queries and Power BI dashboard.*

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
│
├── customer_behavior_sql_queries.sql
│
├── customer_behavior_dashboard.pbix
│
├── customer_shopping_behavior.csv
│
└── README.md
```

*The structure above is a suggested layout. Include only files that are actually present in your repository.*

## How to Run the Project

### Prerequisites

Install or prepare the following:

- Python 3.x
- Jupyter Notebook
- Pandas and NumPy
- SQLAlchemy and the appropriate database driver
- PostgreSQL, MySQL, or MS SQL Server
- Microsoft Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Shopping-Behavior-Analysis.git
cd Customer-Shopping-Behavior-Analysis
```

Replace `YOUR_USERNAME` with your GitHub username and use your actual repository URL.

### Step 2: Install Python Dependencies

```bash
pip install pandas numpy jupyter sqlalchemy
```

Install the appropriate database driver for your chosen database. For PostgreSQL, for example:

```bash
pip install "psycopg[binary]"
```

### Step 3: Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells in order to import, explore, clean, and load the dataset.

### Step 4: Configure the SQL Database

1. Create the database in your SQL server.
2. Update the database connection settings in the notebook.
3. Execute the data-loading code.
4. Verify that the records have been inserted successfully.
5. Open `customer_behavior_sql_queries.sql` and execute the business analysis queries.

**Security note:** Keep database credentials in environment variables or a local configuration file excluded from Git. Never upload passwords, API keys, or other secrets to GitHub.

### Step 5: Open the Power BI Dashboard

1. Open `customer_behavior_dashboard.pbix` in Power BI Desktop.
2. Configure the database connection if prompted.
3. Refresh the data.
4. Verify the measures, charts, and filters.
5. Explore the dashboard to analyze customer behavior.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Python programming for data analytics
- SQL querying and database integration
- Data aggregation and business analysis
- KPI development and dashboard design
- Interactive data visualization
- Translating business questions into analytical solutions
- Data storytelling and insight generation

## Future Enhancements

- Automate data refresh and data-loading workflows.
- Add customer segmentation using machine learning.
- Develop customer lifetime value (CLV) analysis.
- Create a customer retention and churn-risk analysis.
- Introduce time-series analysis when transaction dates are available.
- Deploy dashboards and establish scheduled refreshes.

## Conclusion

The Customer Shopping Behavior Analysis project demonstrates how Python, SQL, and Power BI can work together to convert raw customer data into meaningful business insights.

By combining data preparation, database querying, and interactive visualization, the project provides a foundation for understanding customer preferences, evaluating purchasing patterns, and supporting evidence-based business decisions.

## Author

**ANIKET NAGTRE**

Aspiring Data Analyst

**Technical Skills:** Python | SQL | PostgreSQL / MySQL | Power BI | Pandas | NumPy | Excel



---

*This project was developed for learning, portfolio development, and demonstrating practical data analytics skills.*
