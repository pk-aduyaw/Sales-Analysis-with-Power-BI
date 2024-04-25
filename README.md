<h1 align='center'>Sales Analysis with Power BI 📊💼</h1>


# Table of Contents 📜
[-Introduction]()

[-Data Sources]()

[-Methodology]()

[-Analysis]()

[-Results]()

[-Hypothesis]()

[-Hypothesis Test Result]()

[-Usage]()

[-Contributing]()

[-License]()

# Introduction 🚀
Sales analysis is crucial for understanding the performance of a business, identifying trends, and making informed decisions to optimize sales strategies. This project aims to analyze sales data to uncover patterns, correlations, and actionable insights.

# Data Sources 📂
The sales data collected for this analysis contains information such as sales transactions, product details, customer geographical details.

The data for the first half of the year (January to June) was collected in excel and saved as csv files before management decided to use databases to store their data. The first six (6) months of the data was located on OneDrive while the last six (6) months was  in a remote database.

 # Methodology
CRISP-DM Framework 🔄
This project follows the Cross-Industry Standard Process for Data Mining (CRISP-DM) framework, which consists of the following six phases:

Business Understanding 💼🔍 
Data Understanding 📊💡 
Data Preparation 🛠️🧹 
Modeling 🤖📈 
Evaluation 📝🔍 
Deployment 🚀📊

It is worthy to mention that with the exception of the modelling phase all other phases were used in this project. This is because the project's focus did not require modelling.


# Analysis 🔍
The analysis consists of several key steps:

Data Cleaning and Preprocessing: Cleaning and preparing the raw sales data for analysis, including handling missing values, data formatting, and data transformation.

Exploratory Data Analysis (EDA): Exploring the sales data to understand its distribution, trends, and relationships between variables. This includes visualizations such as histograms, scatter plots, and correlation matrices.

Sales Performance Metrics: Calculating key sales performance metrics such as total sales revenue, average order value, total quantity ordered and total unique product.

Segment Analysis: Analyzing sales performance by different segments such as product categories, customer segments.



# Results 📈
The analysis reveals insights such as:
- Peak Months: We observe peaks in sales during certain months, December, October, and April. These months likely correspond to increased demand due to factors like holidays, promotions, or seasonal trends.
- Trough Months: During the months of June, August, and September. These months may represent periods of lower consumer spending or quieter seasons for the business.
- Opportunities for Improvement: By analyzing seasonality in sales, the business can identify opportunities to capitalize on peak months and mitigate challenges during slower periods. This could involve adjusting marketing strategies, offering targeted promotions, or optimizing inventory management.
- Overall, the month-over-month growth rates suggest that sales are increasing at a steady pace over the course of the year. This suggests that the business is making progress towards achieving its goals and objectives.
- These findings indicate that the "Electronics" category generates higher revenue and has a significantly higher quantity ordered compared to the "Other" category. 
- This suggests that electronics products are the main drivers of sales revenue and volume in the dataset.



- There are no missing values for order IDs, as the count matches the total number of rows in the dataset
- The minimum quantity ordered is 1, and the maximum is 9, with the majority of transactions having a quantity ordered of 1 as indicated by the median and quartiles.
- The mean price of each item ordered is approximately $184.52, with a standard deviation of $332.84, indicating significant variability in item prices.
- The total amount of money made in 2019 was $16,513,908.56
- The minimum quantity ordered is 1, and the maximum is 9, with the majority of transactions having a quantity ordered of 1 as indicated by the median and quartiles.


# Hypothesis
- Null Hypothesis (H0): The total revenue generated in 2019 is equal to or less than a predetermined benchmark or expectation.
- Alternative Hypothesis (H1): The total revenue generated in 2019 is greater than the predetermined benchmark or expectation.

# Hypothesis Test Result
1. The observed total revenue in 2019 matches the benchmark exactly, suggesting that the business achieved its expected revenue target for the year.

2. The extremely low p-value (close to zero) indicates a highly significant difference between the observed revenue and the benchmark. This suggests that the observed revenue is not simply due to random variation but is indeed significantly different from the benchmark.

3. Therefore, we can reject the null hypothesis and conclude that the total revenue generated in 2019 is greater than or different from the benchmark.

4. This finding suggests that the business has achieved its revenue target for the year and is on track to meet or exceed its goals.

5. The results of the hypothesis test provide evidence that the business is making progress towards achieving its goals and objectives.



# Usage 💻
To replicate the analysis or explore the data further, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies from the requirements.txt file with the prompt below:

`python pip install -r requirements.txt`

3. Run the analysis scripts in the specified order.
4. Explore the generated visualizations and insights.
5. Modify the code as needed for your specific requirements.

# Contributing 🤝
Contributions to this project are welcome! 
If you have suggestions for improvements or new features, please open an issue or submit a pull request.

# License 📄
This project is licensed under the [MIT]() License.

# Author: 
Team Nobium
