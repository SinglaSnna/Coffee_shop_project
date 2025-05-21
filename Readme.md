**Coffee Shop Sales Analytics**

**Project Overview**

This project explores transactional data from a coffee shop to uncover sales trends, customer preferences, and performance patterns. Leveraging exploratory data analysis (EDA) and data visualization, the goal is to generate actionable insights that support smarter, data-driven business decisions.

**Objectives**

Identify peak sales hours

Determine top-selling products

Analyze customer payment preferences

Evaluate monthly and daily sales trends

**Dataset Overview**

The dataset includes real-time transaction records and contains the following key attributes:

Product Category and Item Line

Transaction Date and Time

Sales Amount

Payment Method

These variables provide critical insights into consumer behavior, product performance, and operational trends.

**Methodology**

1. Data Exploration

Loaded dataset using pandas

Reviewed data types, structure, and missing values

Conducted preliminary inspection of variables

2. Data Cleaning

Standardized date and time formats

Removed duplicates and handled nulls

Dropped irrelevant or redundant columns

3. Data Preprocessing
   
Aggregated sales data by hour, day and month

Grouped by Product Line and Payment Method

Created derived columns to facilitate analysis

4. Exploratory Data Analysis (EDA)
   
Used matplotlib and seaborn to visualize:

Hourly and monthly sales distribution

Product line performance and revenue share

Payment method usage trends

Sales heatmaps across different time frames

**Key Insights**

**Insight**                         	**Description**

Peak Hours	          Sales spike in the morning (8–11 AM) and late afternoon (4–6 PM)
Top Products	          Certain beverage and snack items consistently outperform others
Payment Preferences	  Card payments are the most preferred method by customers
Monthly Trends         	  Significant fluctuations suggest possible seasonal trends

These findings can guide decisions in inventory management, staff scheduling, and marketing strategies.

**Technologies Used**

Python:   Core programming language

Pandas:   Data loading, manipulation and grouping

NumPy:    Numerical operations and transformations

Matplotlib: Customizable static plotting

Seaborn: Statistical visualization and aesthetics

**Conclusion**

This project demonstrates the power of data analytics in the F&B domain. By performing systematic EDA on transactional data, we can:

Enhance operational efficiency

Improve customer experience

Support data-driven strategy formulation

The Coffee Shop Sales Analytics project shows how simple data analysis techniques can translate into actionable business value.
