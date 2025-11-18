<h1>Video-Games-Sales-Data-Analysis</h1>

<h2>Description</h2>

This project performs an end-to-end data analysis pipeline on a video games dataset. It focuses on extensive data cleaning, preprocessing, outlier handling, and exploratory data analysis (EDA) to derive insights regarding National and Global sales trends.

Key Features
1. Data Cleaning & Preprocessing
Duplicate Management: Identifies and removes duplicate records to ensure data integrity.
Missing Value Handling:
Imputes missing values for categorical columns (Region, Publisher) with 'Not available'.
Implements a mean imputation strategy for missing numerical sales data.
Data Formatting: Cleans currency characters (e.g., removing '$') from sales columns and converts string objects to numeric data types for analysis.
Categorical Standardization: Standardizes inconsistent entries in the Country column (e.g., mapping 'USA' and 'united states' to 'United States').

2. Statistical Manipulation
Renaming: Renames columns for better readability (e.g., changing NA_Sales to National Sales).
Outlier Detection & Handling: Identifies outliers in sales data and applies a capping method using the 95th percentile to reduce the skewing effect of extreme values.

3. Data Visualization (EDA) The project utilizes Matplotlib and Seaborn to visualize key metrics:

Bar Charts: Comparison of National Sales across different Regions and Countries.
Box Plots: Statistical distribution of National Sales by Country to visualize spread and remaining outliers.
Pie Charts: Side-by-side composition analysis of National vs. Global Sales by Country.
Line Charts: Time-series analysis tracking National and Global Sales trends for years greater than 2010.

<h2>Insights walk-through:</h2>


National Sales by Region & Country: <br/>
<img src="https://i.imgur.com/yWK7Uuu.png" height="80%" width="80%" alt="National Sales by Region & Country"/>
<br />
<br />

National Sales by Country: <br/>
<img src="https://i.imgur.com/uCL2r5m.png" height="80%" width="80%" alt="National Sales by Country_1"/>
<br />
<br />

National Sales by Country: <br/>
<img src="https://i.imgur.com/d7XnECl.png" height="80%" width="80%" alt="National Sales by Country_2"/>
<br />
<br />
