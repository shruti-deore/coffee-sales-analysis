# Data Analytics Project

## Project Objective

The objective of this project is to perform data cleaning, analysis, and visualization on a coffee sales dataset using Python, Jupyter Notebook, and Power BI.

## Tools & Technologies Used

* Python
* Pandas
* Jupyter Notebook
* Power BI
* Git
* GitHub

## Dataset Information

The dataset contains coffee sales transaction data, including:

* Date
* Date and Time
* Coffee Name
* Payment Type
* Transaction Amount

The dataset was analyzed to identify sales trends, payment preferences, and coffee popularity.

## Steps Performed

### 1. Data Loading

* Imported dataset using Pandas
* Checked dataset structure and data types

### 2. Data Cleaning

* Checked for missing values
* Removed duplicate records
* Verified data quality

### 3. Data Analysis

* Calculated summary statistics
* Identified maximum and minimum transaction values
* Calculated average transaction amount
* Counted transactions by coffee type
* Analyzed payment methods

### 4. Data Visualization

Created visualizations in Power BI, including:

* Total Sales Card
* Coffee-wise Sales Bar Chart
* Payment Type Pie Chart
* Date-wise Sales Line Chart
* Coffee Distribution Donut Chart
* Payment Type Slicer

## Python Libraries Used

```python
import pandas as pd
```

## Files Included

* coffee_sales_analysis.ipynb
* coffee_sales_cleaned.csv
* coffee_dashboard.pbix
* README.md

## Sample Commands Used

```python
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dropna(inplace=True)
df.drop_duplicates(inplace=True)
df["money"].sum()
df["coffee_name"].value_counts()
```

## Dashboard Insights

* Identified the total sales generated from coffee transactions.
* Compared sales across different coffee types.
* Analyzed payment methods used by customers.
* Observed sales trends over time.
* Visualized coffee distribution patterns.

## Conclusion

Successfully performed data cleaning, analysis, and dashboard creation using Python, Pandas, Jupyter Notebook, and Power BI. The project demonstrates a complete beginner-level data analytics workflow, including data preparation, analysis, visualization, and project documentation using GitHub.
