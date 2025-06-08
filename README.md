# Pens-and-Printers-New-Product-Sales-Strategy-Analysis
## 1. Project Overview

This project provides an in-depth analysis of sales data for a new line of office stationery products launched by Pens and Printers. It aims to evaluate the effectiveness of three different sales strategies—"Email," "Call," and "Email & Call"—and to provide data-driven recommendations to guide future sales initiatives.

## 2. Business Problem

The core of this analysis is to answer the following key questions from the sales team:
- How many customers were reached by each sales method?
- What is the overall revenue distribution, and how does it differ for each method?
- Are there other significant differences among the customer groups for each strategy?
- Based on the data, which sales method should we recommend for future use?

## 3. Data Source

The dataset used, `product_sales.csv`, contains sales records for the first six weeks following the product launch. The key fields include:
- `week`: The week the sale was made (since product launch)
- `sales_method`: The sales strategy used
- `customer_id`: Unique identifier for the customer
- `nb_sold`: Number of new products sold
- `revenue`: Revenue from the sale
- `years_as_customer`: Number of years the customer has been with the company
- `nb_site_visits`: Number of website visits in the last 6 months
- `state`: The state/location of the customer

## 4. Methodology & Pipeline

1.  **Data Cleaning and Validation**:
    - Standardized inconsistent entries in the `sales_method` column (e.g., "Email + Call", "em + call").
    - Addressed missing values and outliers in the `revenue` column.
    - Verified the data types and reasonable ranges of all columns to ensure data quality.

2.  **Exploratory Data Analysis (EDA)**:
    - Utilized `pandas`, `matplotlib`, and `seaborn` libraries for data manipulation and visualization.
    - Compared the performance of different sales strategies across multiple dimensions, including customer reach, revenue distribution, and revenue trends.
    - Profiled customer segments for each strategy based on characteristics like customer tenure and site engagement.

3.  **Conclusion and Recommendations**:
    - Assessed the Revenue per Customer (RPC) of each marketing method by synthesizing analysis findings with their respective time costs.
    - Formulated final conclusions and provided actionable strategic recommendations for the sales team.

## 5. Key Findings & Visualizations

#### Significant Disparity in Revenue Performance Across Strategies
The "Email & Call" combination yields the highest average revenue, whereas the "Email" strategy, despite its broad reach, results in the lowest average revenue.

![Revenue Distribution by Sales Method](https://github.com/ericxq27/Pens-and-Printers-New-Product-Sales-Strategy-Analysis/blob/main/Images/Revenue%20Distribution%20by%20Sales%20Method.png)

#### "Email & Call" Strategy Shows the Greatest Growth Potential
Over the 6-week period, the "Email & Call" strategy demonstrated the most robust and consistent growth in average weekly revenue, even though it only reaches a small percentage of customers.

![Average Weekly Revenue by Sales Method](https://github.com/ericxq27/Pens-and-Printers-New-Product-Sales-Strategy-Analysis/blob/main/Images/Average%20Weekly%20Revenue%20by%20Sales%20Method.png)
![Number of Customers by Sales Method](https://github.com/ericxq27/Pens-and-Printers-New-Product-Sales-Strategy-Analysis/blob/main/Images/Number%20of%20Customers%20by%20Sales%20Method.png)


## 6. Summary of Recommendations

1.  **Prioritize the "Email & Call" Strategy**: This method offers the best balance between revenue generation and time investment. Resources should be scaled to support this combined approach.
2.  **Optimize the "Email" Strategy**: Continue using email as a low-cost tool for broad outreach, but enhance it with customer segmentation and A/B testing to improve conversion rates and identify high-potential leads for follow-ups.
3.  **Use the "Call" Strategy Selectively**: Reserve this time-intensive method for high-value segments, such as long-term customers with high lifetime value or highly-qualified leads.
4.  **Implement a Differentiated Outreach Approach**: Develop customer personas based on tenure, engagement, and other metrics to match them with the most effective sales strategy.
5.  **Enhance Data Tracking & Evaluation**: Continuously monitor conversion rates at each stage of the sales funnel and accurately track time spent on each activity to dynamically optimize strategies.
