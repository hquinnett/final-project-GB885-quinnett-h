# RUSH Sales Analysis

Hailey Quinnett  
GB 885 - Python Fundamentals  
Final Project  
8/9/2026

## Overview

RUSH is a globally renowned sportswear and footwear brand known for its innovative designs and performance-oriented products. This project analyzes RUSH's raw US sales data from 2020 and 2021 to identify trends and insights that can help company leadership understand the market and identify opportunities for growth.

The VP of US Sales has asked for answers to the following business questions:

1.   What product category (product) had the highest sales (in dollars) in 2021? How much did it sell?
2.   What state had the highest sales (in dollars) of women's products in 2021? How much was it?
3.   What state had the highest sales (in dollars) of men's products in 2021? How much was it?
4.   What retailer purchased the most units in 2021? In 2020?

## Data

The company stores its raw sales data as a collection of three tables. The csv files are stored in the data folder within this repository.

*   TABLE_PRODUCTS
*   TABLE_RETAILER
*   TABLE_SALES

The data includes the number of units sold, the total sales revenue, the location of the sales, the type of product sold, as well as other relevant information. For data field definitions and explanations, see the data dictionary in the resources folder of this repository.

## Results

### Business Questions

1.   Highest-selling product category in 2021: Men's Street Footwear - $22,011,662
2.   State with the highest sales of women's products in 2021: Tennessee - $905,013
3.   State with the highest sales of men's products in 2021: Arizona - %2,158,900
4.   Retailer with the most units purchased:
     *   2021: Foot Locker - 1,069,300 units
     *   2020: Amazon - 278,625 units

### Additional Insights

*   Foot Locker and Walmart were added as retailers in 2021. Foot Locker became the largest purchaser in its first year.
*   Online sales increased substantially from approximately $4.48 million in 2020 to $41.23 million in 2021. Walmart's 2021 sales were primarily generated through the online sales channel.
*   Monthly sales were examined for potential seasonal patterns, but no clear or consistent seasonal trend was identified.

## How to Run

Open the GB885_Final_Project_Draft.ipynb notebook in Google Colab and run the notebook from beginning to end. The notebook loads the csv files directly from the data folder in this repository.
