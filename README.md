Sales and Profit Analysis

Overview

This project analyzes sales and profit distribution across different markets using a dataset that includes information on orders, customers, regions, and product sales. The goal is to identify the most profitable regions, markets, and products, helping businesses make data-driven decisions.

Features

Sales and Profit Distribution Analysis

Identification of Most Profitable Cities and States

Most Popular Products (Highest Quantity Sold)

Visualization of Sales and Profit Across Different Markets

Insights from Stacked Bar Charts and Pie Charts

Dataset

The dataset includes the following key columns:

Order ID, Customer ID, Order Date, Ship Date

Market, Region, City, State

Product Name, Category, Sub-Category

Sales, Quantity, Profit, Discount, Shipping Cost

Analysis & Visualizations

1. Most Profitable Cities and States

Grouped data by City and State to calculate total profit.

Created a bar chart to visualize the top 10 most profitable locations.

2. Most Popular Products (Highest Quantity Sold)

Grouped data by Product Name to sum the total quantity sold.

Created a pie chart to show the top 5 most sold products.

3. Sales and Profit Distribution Across Different Markets

Grouped data by Market and calculated total Sales and Profit.

Created a stacked bar chart to compare sales and profit distribution across various markets.

Technologies Used

Python (pandas, matplotlib, seaborn)

Jupyter Notebook for analysis

Matplotlib & Seaborn for data visualization

How to Run the Project

Clone the repository:


Navigate to the project folder:

cd sales-profit-analysis

Install required dependencies:

pip install pandas matplotlib seaborn

Run the Jupyter Notebook:

jupyter notebook

Open the sales_analysis.ipynb file and execute the cells.

Results & Insights

APAC and EU markets are the most profitable.

The US and LATAM markets also contribute significantly.

Some regions like Canada and Africa have lower sales and profit.

Certain products have much higher sales volume, influencing inventory decisions.

Future Improvements

Adding machine learning models for predictive sales analysis.

Creating an interactive dashboard for real-time monitoring.

Expanding the analysis to customer segmentation.
