# Customer Segmentation & Product Recommendation (R)

## Overview
This project analyzes customer demographics and purchase behavior to identify
distinct customer segments and recommend frequently purchased product combinations.
The goal is to support data-driven marketing, customer retention, and revenue growth.

---

## Business Context
Acme Innovations is a long-established household appliance company experiencing
declining customer retention due to changing customer preferences.
This project applies analytical techniques to identify loyal customer segments
and uncover cross-selling opportunities.

---

## Objectives
- Segment customers based on demographic and behavioral data
- Identify high-value and loyal customer groups
- Discover frequently purchased product combinations for bundling and cross-selling

---

## Datasets Used
- **customer_data.csv**
  - Age
  - Salary
  - Spending Score
  - Time as Customer

- **customer_purchase_history_final.csv**
  - Transaction-level purchase data

---

## Tools & Technologies
- R
- dplyr, tidyr
- ggplot2
- cluster
- arules, arulesViz

---

## Analysis Performed

### 1. Data Exploration & Cleaning
- Checked for missing values and data structure
- Converted data types where required
- Handled missing values using mean imputation
- Visualized distributions using histograms

### 2. Customer Segmentation (K-Means Clustering)
- Selected relevant numerical features for clustering
- Used the Elbow Method to determine optimal number of clusters
- Applied K-Means clustering to segment customers
- Visualized clusters using 2D and 3D plots

### 3. Product Recommendation (Association Rule Mining)
- Converted transaction data into transaction format
- Applied the Eclat algorithm to identify frequent itemsets
- Analyzed top purchased products and common product combinations

---

## Key Insights
- Identified distinct customer segments based on income and spending behavior
- High-value customer clusters show strong loyalty potential
- Frequent product combinations support effective bundling strategies

---

## Business Recommendations
- Focus loyalty programs on high-value customer segments
- Bundle frequently purchased products to increase average order value
- Run targeted marketing campaigns based on customer segments

---

## Project Files
- `Group_Project.R` – Complete R script for data cleaning, clustering, and recommendation engine
- `customer_data.csv` – Customer demographic dataset
- `customer_purchase_history_final.csv` – Transaction purchase history data

---

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Unsupervised machine learning (K-Means clustering)
- Association rule mining (Eclat algorithm)
- Data visualization
- Business insight generation
