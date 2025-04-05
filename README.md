# WIDE-WORLD-IMPORTERS-DATA-ANALYSIS
This initiative focuses on examining the Worldwide Importers dataset to reveal practical insights regarding international trade operations. The dataset contains information about clients, orders, transactions, products, and inventory. The goal of the analysis is to enhance decision-making in aspects like supply chain efficiency, sales performance, and customer behavior.

## Project Objectives

- **Understanding customer demographics**  
  Analyze who the major customers are, and where they are located.

- **Analyze sales and purchase trends**  
  Identify high-performing products, seasonal demand patterns, and top revenue sources.

- **Monitor inventory**  
  Track inventory levels, and order fulfillment rates.

- **Detect anomalies or inconsistencies**  
  Spot unusual transactions, duplicate entries, or missing information.

  ## Data Cleaning Process

- **Missing Values Handling**  
  Identified and filled missing values in fields such as `DeliveryDate`, `CustomerCategory`, and `City` using mean, mode, or forward-fill methods depending on the context.

- **Data Type Conversions**  
  Converted date-related columns like `OrderDate` to datetime format.  
  Ensured numerical fields such as `UnitPrice`, and `Quantity` were correctly typed as numeric values.

- **Duplicate Removal**  
  Checked for and removed duplicate transactions or repeated records based on a combination of `OrderID`, and `ProductID`.

- **Standardization**  
  Standardized categorical data such as country names and payment methods.  
  Ensured consistent units across product dimensions and currency values to avoid calculation errors.

## Outcomes and Key Insights

- **Top-Selling Products Identified**  
  Certain product categories consistently drive high revenue across quarters and regions.

- **Customer Behavior Patterns**  
  Segmented customers based on purchase frequency and value to support targeted marketing strategies.
  
- **Sales Seasonality Trends**  
  Recognized monthly and quarterly sales peaks to better align marketing strategies and staffing needs.

- ** Profit Analysis**  
  Created dashboards highlighting net profit margins per region, customer category, and product line to aid in business strategy.

  
![Screenshot 2025-04-05 004320](https://github.com/user-attachments/assets/68c41dd5-bc33-4667-8925-1afbf485e847)


