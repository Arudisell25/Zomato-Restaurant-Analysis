# Zomato-Restaurant-Analysis
The project task was to analyze customer data and order history to identify purchasing trends using Power BI and Word.
# Table of Contents

1. [Project Overview](#project-overview) 
2. [Data Sources](#data-sources)
3. [Tools and Technologies Used](#tools-and-technologies-used)
4. [Data Preparation and Cleaning](#data-preparation-and-cleaning)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Conclusion and Recommendations](#conclusion-and-recommendations)
11. [Future Work and Enhancements](#future-work-and-enhancements)
    

---
![image](https://github.com/user-attachments/assets/b401911a-b606-491d-baac-9ef1d8b42319)

![image](https://github.com/user-attachments/assets/a43e2945-ab59-471a-94b8-26aee2b0b1fe)

## Zomato Business Analysis

### Data Sources

Based on the provided document, the data sources appear to be:

-   **Zomato Sales Data:** Information on sales transactions, including sales amounts, quantities, dates (quarters, months, days of the week), and potentially restaurant IDs and user IDs.
-   **Currency Conversion Data:** Information on conversion rates between INR (Indian Rupee) and USD (US Dollar).
-   **Customer Data (Implied):** Data necessary for RFM (Recency, Frequency, Monetary Value) segmentation, suggesting a database of customer purchase history.

### Tools and Technologies Used

The analysis likely involved the following tools and technologies:

-   **Data Analysis Software:**  Potentially Python with libraries like Pandas for data manipulation and analysis.
-   **Data Visualization Tools:** Tools like Tableau or Matplotlib/Seaborn (Python) for creating visualizations such as:
    -   Line graphs for sales trends over time.
    -   Scatter plots for quantity vs. sales amount by restaurant.
    -   Donut charts for proportions.
    -   Heatmaps (mentioned for tracking trends).
-   **RFM Analysis Tools:** Software or libraries for performing RFM segmentation.

### Data Preparation and Cleaning

Data preparation and cleaning steps likely included:

-   **Data Cleaning:** Handling missing values, correcting inconsistencies in restaurant IDs or user IDs.
-   **Data Transformation:** Aggregating sales data by day, week, month, quarter, restaurant, or user.  Converting currencies if necessary.  Calculating RFM values (recency, frequency, monetary value).
-   **Data Integration:** Combining data from different sources (e.g., sales data with customer data) using appropriate keys.

### Exploratory Data Analysis (EDA)

Key insights derived from the EDA include:

-   **Sales Trends Over Time:**
    -   2019 had the highest average sales.
    -   Sales peaked in January-March and declined through September.
    -   Fridays generate the most revenue.
    -   Saturdays show consistent growth.
    -   Tuesdays are declining in sales.
-   **Sales Quantity by Day of the Week:**
    -   Saturday is the best day for sales quantity (28.96%).
    -   Sunday is the worst day for sales quantity (7.40%).
-   **Conversion Rates:**
    -   INR (Indian Rupee) has a significantly higher conversion rate than USD (US Dollar).
-   **Restaurant Performance:**
    -   Positive correlation between quantity of items sold and total sales amount.
    -   Identification of outlier restaurants (high sales but lower quantities, or vice versa).
-   **User Performance:**
    - Identification of top-performing sales people and reward them accordingly.
-   **Average sales amount**
    - Average sales for Thursday is 1,510,944.00, User ID is 70591.

### Conclusion and Recommendations

-   **Leverage Fridays:** Focus marketing campaigns and promotions on Fridays. Optimize staffing and inventory.
-   **Invest in Saturday Growth:** Enhance customer engagement through weekend-specific campaigns or loyalty programs.
-   **Revitalize Tuesdays:** Investigate the reasons behind declining sales on Tuesdays.
-   **Optimize for INR:** Capitalize on the higher conversion rate of INR, potentially expanding marketing efforts in the Indian market.
-   **Address Declining Sales:** Investigate reasons for declining sales over the months from January to September.
-   **Restaurant Performance Analysis:** Analyze factors contributing to the success or failure of individual restaurants.
-   **Improve Sunday Sales:** Implement strategies to improve sales on Sundays.
-    **Identify trends in sales performance, such as which days of the week are most profitable, which currencies have the best conversion rates, and which user ids are associated with higher sales amounts.**
-   **RFM Segmentation:** Utilize RFM segmentation to target different customer groups with tailored marketing strategies.

### Future Work and Enhancements

-   **Root Cause Analysis:** Conduct a deeper investigation into the reasons behind declining sales on Tuesdays and overall sales decline from January to September.
-   **Sunday Sales Improvement:** Research and implement strategies to boost sales on Sundays.
-   **USD Conversion Optimization:** Investigate reasons for lower USD conversion rates and implement strategies to improve them.
-   **Restaurant-Specific Analysis:** Conduct detailed analysis of individual restaurants to identify best practices and areas for improvement.
-   **Predictive Modeling:** Use predictive models to forecast future sales trends and optimize inventory management.
-   **A/B Testing:** Implement A/B testing for different marketing campaigns and promotions to identify the most effective strategies.
-   **Further User ID Performance Analysis:** By tracking sales and User IDs you can identify top-performing salespeople and reward them accordingly.
-   **Optimize campaigns and promotions** Focusing on Fridays to capitalize on higher spending patterns.
