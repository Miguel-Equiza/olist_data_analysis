# Olist Profit Improvement Analysis
![image](https://github.com/user-attachments/assets/51d5e822-db16-4213-bcf2-204f6a82cc09)

## Overview

This project aims to analyze how Olist, a leading e-commerce service in Brazil, can increase its profits. Olist connects merchants to major marketplaces and offers various services, including inventory management, handling customer reviews, and logistics. Olist charges sellers a progressive monthly fee based on their volume of orders.

By exploring key factors such as seller performance, product catalog, and customer feedback, this analysis uncovers actionable insights to enhance profitability.
---

## Objective

The primary objective of this analysis is to understand the factors influencing Olist's profits and to provide recommendations for increasing profitability. This involves exploring the seller and product dynamics and identifying key drivers that affect revenue and profit margins.

---

## Dataset

The dataset consists of approximately 100,000 orders placed between 2016 and 2018 on Olist’s platform. It was derived from 9 initial CSV files, which were combined into 3 datasets that capture various aspects of the business, including:

1. **Order details** (seller information, product details, logistics performance, etc.).
2. **Seller performance**.
3. **Product details**.

---

## Methodology

### 1. **Data Preprocessing**
   - **Merged datasets**: Combined the 9 raw CSV files into 3 coherent datasets for analysis.
   - **Data cleaning**: Handled missing data, removed duplicates, and performed data normalization.
   
### 2. **Exploratory Data Analysis (EDA)**
   - **Descriptive statistics**: Generated summaries to understand the distribution of key metrics like profit, orders, and review scores.
   - **Visual analysis**: Created plots (histograms, scatterplots, heatmaps) to examine relationships between variables.
   
### 3. **Correlation Analysis**
   - Computed correlation matrices to identify relationships between numeric variables (e.g., order volume, seller reviews, delivery delays, and profit).
   - Focused on understanding which seller behaviors and product characteristics were positively or negatively correlated with profit.

### 4. **Predictive Modeling**
   - **Linear Regression**: Used to predict the impact of specific features (e.g., number of orders, delay to carrier, and review scores) on profit.
   - **Logistic Regression**: Performed classification analysis to understand the likelihood of a seller achieving high or low profitability.
   
### 5. **Profit Impact Analysis**
   - **Seller analysis**: Identified which sellers were underperforming in terms of profit.
   - **Product analysis**: Determined how specific products and categories contributed to profit margins.
   - **Impact of seller/product removal**: Simulated scenarios where low-performing sellers or low-rated products were removed from the platform and analyzed the resulting impact on overall profit.


