# Bike Sales Analysis Project

This repository contains a comprehensive analysis of bike sales data, exploring the relationship between customer demographics and purchasing behavior. The analysis aims to uncover key insights that can inform marketing strategies and business decisions.

## Dataset Overview

The dataset used in this analysis includes the following columns:

- **ID:** A unique identifier for each customer.
- **Marital Status:** Indicates whether the customer is married or single.
- **Gender:** Gender of the customer.
- **Income:** The annual income of the customer.
- **Children:** The number of children the customer has.
- **Education:** The highest level of education attained by the customer.
- **Occupation:** The customer's occupation.
- **Home Owner:** Indicates whether the customer owns a home.
- **Cars:** The number of cars owned by the customer.
- **Commute Distance:** The distance the customer travels to work.
- **Region:** The region where the customer resides.
- **Age:** The age of the customer.
- **Age Brackets:** Categorized age groups.
- **Purchased Bike:** Indicates whether the customer purchased a bike (Yes/No).

## Data Cleaning and Processing

### 1. Data Cleaning
The data was initially cleaned to ensure accuracy and consistency. This involved:

- **Handling Missing Values:** Any missing data was identified and appropriately handled. For instance, missing income or age data was either imputed with median values or excluded if it was insignificant.
- **Data Type Correction:** Ensuring that all columns had the correct data types, such as numeric types for income and age, and categorical types for marital status and gender.
- **Standardizing Categorical Values:** Values in columns like `Gender`, `Marital Status`, and `Purchased Bike` were standardized to ensure consistency (e.g., `Male`/`Female`, `Yes`/`No`).

### 2. Data Processing
Once the data was cleaned, it was processed for analysis:

- **Creation of Age Brackets:** The `Age` column was grouped into `Age Brackets` to categorize customers into different age groups, making it easier to analyze trends across different age ranges.
- **Income Grouping:** Customers' income levels were grouped into ranges to facilitate comparison across different income brackets.
- **Commute Distance Categorization:** The `Commute Distance` column was categorized into different ranges to understand its impact on bike purchasing behavior.

## Analysis and Insights

### 1. Pivot Tables
Pivot tables were created to summarize key metrics and provide insights:

- **Average Income per Purchase:** A pivot table was created to calculate the average income of customers who purchased bikes. This table helps to identify income levels that are more likely to result in a bike purchase.
- **Commute Distance and Bike Purchase:** Another pivot table was designed to analyze the relationship between a customer's commute distance and their likelihood of purchasing a bike. This pivot table helps to understand how distance to work influences purchasing decisions.

### 2. Charts and Visualizations
The analysis includes various charts to visually represent the data:

- **Average Income per Purchase:** This chart visualizes the average income of customers who purchased bikes, helping to identify the income groups most likely to make a purchase.
- **Commute Distance vs. Bike Purchase:** A chart depicting the relationship between commute distance and bike purchases, showing whether customers with longer or shorter commutes are more inclined to buy a bike.
- **Customer Age Distribution:** A chart showing the distribution of customer ages, which helps in understanding the age demographics of bike purchasers.

### 3. Slicers
To make the data more interactive and user-friendly, slicers were added to the dashboard. These slicers allow users to filter the data based on different metrics such as:

- **Marital Status**
- **Region**
- **Education Level**

The slicers enable users to customize their view of the data and analyze specific segments of the customer base.

