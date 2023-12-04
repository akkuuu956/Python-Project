# Python-project-Analyze Diwali sales data to improve customer experience and sales
This Python code performs an exploratory data analysis on Diwali sales data. Here is a detailed explanation of the key sections:

Import Libraries and Load Data:
- Imports pandas, matplotlib, seaborn to enable data analysis and visualization
- Uses pandas read_csv() to load the Diwali sales data from a CSV file into a DataFrame 

Data Cleaning:
- drops the unused 'Status' and 'unnamed1' columns  
- Checks for null values using pd.isnull().sum()
- Drops rows with null values to clean the data
- Casts the 'Amount' column from object to int datatype for aggregation calculations later

Exploratory Data Analysis:

Analyze by Gender: 
- Plots count of buyers by Gender using seaborn countplot()
- Sums Amount by Gender and plots a bar chart showing Females ordered more

Analyze by Age Group:
- Plots count of buyers by Age Group and Gender using seaborn catplot()
- Sums Amount by Age Group and plots bar chart showing 26-35 age group dominates

Analyze by State:
- Sums Orders and Amount by State and plots bar charts showing UP, Maharashtra and Karnataka lead 

Analyze by Marital Status: 
- Plots count of buyers by Marital Status
- Sums Amount by Marital Status and Gender, married women lead

Analyze by Occupation and Category:
- Plots count and sum of Amount by Occupation and Product Category showing top segments

Top Products:
- Plots top 10 products by Order count 

Key Insights:
- Provides summary of key insights from EDA on buyer demographics and products

The analysis slices the data across various dimensions and visualizes the main metrics using pandas/seaborn to uncover insights.

