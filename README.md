# Instacart Market Basket Analysis

*This project was completed as part of PG Level Advanced Certification Programme in Computational Data Science coursework at Centre for Continuing Education - Indian Institute of Science in collaboration with Talent Sprint*

A special thanks to Prof. Shashi Jain & Mentor Mr. Sachin Sharma

Problem Statement: Extract association rules and find groups of frequently purchased items from a large-scale grocery orders dataset. 

Module: Business Analytics

Project Type: Team

## Project Overview
A comprehensive analysis of Instacart's customer purchase patterns using market basket analysis techniques. The project analyzes over 3 million grocery orders from 200,000+ Instacart users to uncover shopping patterns, product associations, and temporal trends.

## Dataset
- Over 3 million grocery orders
- 200,000+ Instacart users
- Data spread across multiple files:
  - orders.csv
  - products.csv
  - aisles.csv
  - departments.csv
  - order_products_train.csv

## Analysis Components

### 1. Data Integration & Preprocessing
- Merged multiple data sources into a unified dataset
- Handled missing values and data transformations
- Created purchase frequency matrices

### 2. Exploratory Data Analysis
- Product frequency analysis
- Department-wise purchase patterns
- Temporal analysis (day of week, hour of day)
- Reorder behavior analysis

### 3. Market Basket Analysis
- Implemented Apriori algorithm
- Generated association rules
- Analyzed product co-occurrence patterns

## Key Findings

### Shopping Patterns
- Most popular product: Bananas
- Peak ordering hours: 10 AM - 4 PM
- Higher order frequencies during weekends
- Clear patterns in reorder behavior

### Product Associations
- Generated frequent itemsets with minimum support of 0.01
- Identified strong product associations using lift metric
- Discovered valuable product grouping patterns

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- MLxtend (for Apriori algorithm)
- Scipy
- Apriori Algorithm

## Business Applications
- Inventory optimization
- Store layout recommendations
- Targeted marketing strategies
- Product recommendation systems
- Staffing optimization
- Reorder prediction

## Future Improvements
- Implement more sophisticated association algorithms
- Add seasonal trend analysis
- Develop product recommendation system
- Include price analysis
- Add customer segmentation

## Acknowledgments
- Instacart for providing the dataset

---
**Note**: This project is for educational purposes and uses a public dataset from Instacart.
