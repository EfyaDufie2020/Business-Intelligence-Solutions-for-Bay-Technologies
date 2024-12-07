![Bay Technologies Dashboard](./Data/Capture%207.PNG)

## Description
Bay Technologies has collected transactional data for the year 2019 but has not been able to leverage it for insights. They seek to extract meaningful information from the data to identify key opportunities to boost sales and improve operational efficiency. They are specifically interested in understanding revenue trends, seasonality trends, product sales performance, and customer preferences across different time periods and locations. Their goal is to make data-driven decisions to optimize their business operations, sales and makerting strategies and overall business performance.

### Project Goal
The objective is to design and deliver an end-to-end business intelligence solution that analyzes the client’s 2019 transactional data by leveraging on the CRISP-DM methodology. The goal is to generate insights on sales trends, seasonality trends, product performance, analyze geographical delivery patterns and provide actionable recommendations to help the client increase sales and improve efficiency. The solution will also categorize products based on their price levels and uncover additional insights beyond the client’s specific questions.


### Data Source
1. One Drive
2. Database Server
   

The `Final_Sales_2019` dataset is a cleaned and processed version of the original sales data collected from various data sources. The dataset contains information about individual sales transactions, including the product name, quantity ordered, price per unit, order date, purchase address, and total sales generated.

## Data Cleaning and Preprocessing
The original sales data was cleaned and preprocessed to handle inconsistencies, errors, and missing values. The following steps were taken:

1. Duplicates were removed to ensure data integrity.
2. Null values were handled by dropping rows with missing values or specific columns.
3. Unwanted strings and characters were removed from the dataset.
4. Data types were checked and converted where necessary.
5. New columns were created to calculate the total sales generated from each sale.
6. Additional columns were extracted from the purchase address to get the city information.
7. A new column was created to categorize products based on their price level (high-level or basic-level).
8. Only sales data from the year 2019 was extracted for further analysis.

## Summary Statistics
The summary statistics for numerical columns in the `Final_Sales_2019` dataset are as follows:

- `Quantity_Ordered`: The average quantity ordered per sale is 1.97, with a minimum of 1 and a maximum of 100.
- `Price_Each`: The average price per unit is $22.36, with a minimum of $0.25 and a maximum of $2,000.
- `Total_Sales`: The average total sales generated per sale is $43.51, with a minimum of $0.25 and a maximum of $20,000.

## Hypothesis Testing
To test the hypothesis that there is a significant difference in revenue between high-level and basic-level products, an Analysis of Variance (ANOVA) test was performed. The results indicated that there is a statistically significant difference in revenue between the two product levels.

## Exploratory Data Analysis
The `Final_Sales_2019` dataset can be used for various exploratory data analysis tasks, such as:

1. Analyzing the distribution of sales by product level.
2. Identifying trends in sales over time (e.g., monthly, quarterly, or yearly).
3. Examining the relationship between sales and other factors (e.g., price, quantity, location).
4. Performing market segmentation based on customer demographics or purchase behavior.
5. Analyzing the impact of promotions or discounts on sales.


## Data Visualization
Visualize the data using various plots and charts to better understand the patterns and trends in the sales data. Some suggestions for visualization include:

1. Bar charts to compare sales by product level.
2. Line graphs to show sales trends over time.
3. Pie charts to represent the distribution of sales by product level.
4. Scatter plots to examine the relationship between sales and other factors.
5. Heat maps to visualize the correlation between different factors.

[Power BI](https://app.powerbi.com/groups/me/reports/f5b73e7c-4286-4e4a-804e-e1dd0465af24/91fba607080cd602d082?experience=power-bi)

## Additional Resources
For further information and resources related to the `Final_Sales_2019` dataset, consider the following:

1. [Python Pandas documentation](https://pandas.pydata.org/docs/)
2. [Data Visualization with Python](https://www.oreilly.com/library/view/data-visualization-with/9781491920545/)
3. [Exploratory Data Analysis with Python](https://www.oreilly.com/library/view/exploratory-data-analysis/9781491985450/)
4. [Market Basket Analysis in Python](https://www.kdnuggets.com/2019/09/market-basket-analysis-python.html)
5. [Sentiment Analysis with Python](https://www.kdnuggets.com/2018/08/sentiment-analysis-python.html)

## License
This project is licensed underthe MIT License- see the LICENSE FILE for details

I hope this README helps you understand the `Final_Sales_2019` dataset better! 
Let me know if you have any further questions.
Email:mercydboateng@gmail.com
