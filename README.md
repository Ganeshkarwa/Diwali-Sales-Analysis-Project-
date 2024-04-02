# Diwali-Sales-Analysis-Project-
# Diwali Sales Analysis Project

## Objectives
- Analyze Diwali sales based on different parameters such as products, gender, state, age, occupation, and zone area of the customers.
- Improve customer experience by analyzing sales data.
- Increase revenue.

## Project Overview
This project aims to analyze Diwali sales data to gain insights into customer behavior and preferences. 
It involves data cleaning, exploratory data analysis (EDA), and drawing conclusions based on the analysis.

## Steps Involved

### 1. Data Importation
- Libraries such as pandas, NumPy, matplotlib, and seaborn are imported in a Jupyter Notebook.
- Raw data is loaded using pandas' `read_csv()` function.

### 2. Data Cleaning
- Check the data types of each column using `df.info()`.
- Remove any useless columns using `df.drop()`.
- Check for null values using `pd.isnull(df).sum()` and drop them using `pd.dropna()`.
- Statistical summary of the data is obtained using `df.describe()`.

### 3. Exploratory Data Analysis (EDA)
#### Gender
- Analyze count vs. gender and amount vs. gender using seaborn.
- Draw conclusions about gender-based purchasing behavior.

#### Age
- Plot count vs. age group and amount vs. age group.
- Analyze purchasing patterns based on age groups.

#### State
- Analyze orders vs. state and amount vs. state.
- Identify states with the highest number of orders and total sales.

#### Marital Status
- Analyze count vs. marital status and amount vs. marital status.
- Investigate purchasing behavior based on marital status.

#### Occupation
- Analyze count vs. occupation and amount vs. occupation.
- Identify the most common occupations among customers.

#### Product Category
- Plot count vs. product category and amount vs. product category.
- Determine the most popular product categories.

### Conclusion
- Married women aged 26–35 years from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and
- Aviation sectors are more likely to buy products from Food, Clothing, and Electronics categories.

## GitHub Repository Information
- This repository contains the Jupyter Notebook file (`Diwali_Sales_Analysis.ipynb`) where the analysis is performed.
- The dataset used for analysis is stored as a CSV file (`diwali_sales_data.csv`).
- All necessary libraries and dependencies are listed in the README file (`README.md`).

