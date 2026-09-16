# Food Delivery Orders - Exploratory Data Analysis

## Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a food delivery orders dataset containing approximately 5,000 order records.

The objective of the project is to understand customer ordering patterns, restaurant and cuisine preferences, delivery performance, customer satisfaction, and other important business trends.

The project follows a complete EDA workflow including **data understanding, data cleaning, feature engineering, visualization, analysis, insight generation, and business recommendations**.

---

## Business Problem

A food delivery company wants to better understand its historical order data to improve operational efficiency and customer experience.

The analysis focuses on answering questions related to:

- Customer ordering patterns
- Popular cuisines and restaurant types
- Order values and customer spending
- Peak ordering periods
- Delivery performance
- Delivery distance and delivery time
- Customer ratings
- Payment preferences
- Order cancellations and refunds

---

## Dataset

The dataset contains approximately **5,000 food delivery orders**.

Each row represents an individual food delivery order.

### Dataset Features

| Column | Description |
|---|---|
| Order_ID | Unique identifier for each order |
| Order_Date | Date on which the order was placed |
| Order_Time | Time at which the order was placed |
| Customer_ID | Unique identifier for the customer |
| City | City where the order was placed |
| Restaurant_Type | Type of restaurant |
| Cuisine | Type of cuisine ordered |
| Order_Value | Value of the food order |
| Delivery_Fee | Delivery charge applied to the order |
| Payment_Method | Payment method used by the customer |
| Delivery_Time_Min | Time taken to deliver the order in minutes |
| Distance_KM | Distance between restaurant and customer |
| Customer_Rating | Rating provided by the customer |
| Order_Status | Final status of the order |

---

## Tools and Libraries

The project was completed using:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## EDA Process

The following steps were performed during the analysis:

1. **Data Understanding**
   - Examined dataset structure
   - Identified numerical and categorical variables
   - Reviewed data types and basic statistics

2. **Data Quality Assessment**
   - Checked missing values
   - Identified duplicate records
   - Examined inconsistent categorical values
   - Investigated potential outliers

3. **Data Cleaning**
   - Removed duplicate records
   - Standardized inconsistent categorical values
   - Handled missing values based on business context
   - Converted date and time fields to appropriate formats

4. **Feature Engineering**
   - Created additional features from existing data to support analysis
   - Extracted information such as order hour, day, month, and order period

5. **Exploratory Analysis**
   - Performed univariate and bivariate analysis
   - Studied order patterns and customer preferences
   - Analyzed delivery performance
   - Investigated relationships between numerical variables

6. **Data Visualization**
   - Histograms
   - Bar charts
   - Box plots
   - Line charts
   - Scatter plots
   - Correlation heatmap

7. **Business Insights and Recommendations**

---

## Key Insights

- After removing duplicate records, **4,988 unique orders** remained for analysis.
- **Bangalore recorded the highest number of orders**, while Kochi recorded the lowest.
- **North Indian cuisine** was the most frequently ordered cuisine.
- **Fast Food restaurants** received the highest number of orders.
- Fine Dining received fewer orders but had a comparatively **higher average order value**.
- **UPI was the most commonly used payment method**.
- Order activity was particularly high during **lunch and dinner hours**.
- Weekend demand was strong, with **Sunday recording the highest order volume**.
- Approximately **92.4% of orders were successfully delivered**.
- Delivery distance and delivery time showed a **positive relationship**.
- Delivery distance and delivery fee also showed a strong positive relationship.
- Longer delivery times were generally associated with **lower customer ratings**.
- A small number of unusually high order values and delivery times were identified during outlier analysis.

---

## Business Recommendations

Based on the analysis:

- Increase delivery-partner availability during peak lunch and dinner periods.
- Strengthen operational capacity during weekends.
- Focus promotions and restaurant partnerships around high-demand cuisines.
- Consider Fine Dining as a high-value customer/order segment despite its lower order volume.
- Investigate comparatively higher delivery times in cities such as Mumbai and Bangalore.
- Improve delivery planning for longer-distance orders.
- Reduce delivery delays to improve customer satisfaction.
- Further investigate the reasons behind cancelled and refunded orders.
- Maintain a reliable and convenient UPI payment experience.

---

## Project Files

```text
Food-Delivery-EDA/
│
├── food_delivery_orders_eda.csv
├── Food_Delivery_EDA.ipynb
└── README.md
