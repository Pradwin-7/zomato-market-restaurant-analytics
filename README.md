# 📊 Zomato Market & Restaurant Analytics

An exploratory data analytics project analyzing **20,000+ Zomato restaurant records** to understand restaurant ratings, pricing, cuisines, customer engagement, and online delivery patterns.

## 🎯 Project Overview

The project uses Python-based data analytics techniques to explore restaurant data and identify patterns related to restaurant performance and customer preferences.

The analysis covers data preprocessing, exploratory data analysis, statistical analysis, and visualization to extract meaningful insights from the dataset.

## 👥 Project Type

**Academic Group Project**

This project was developed as part of a six-member academic group.

My contribution included working with the **data preprocessing, exploratory analysis, visualizations, and interpretation of results**.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## 📌 Project Objectives

- Analyze restaurant performance and ratings
- Explore pricing patterns across restaurants and cities
- Study cuisine distribution and customer preferences
- Examine the relationship between votes and ratings
- Analyze online delivery availability
- Identify patterns and insights from restaurant data

## 🔄 Data Analysis Workflow

The project followed several stages:

1. **Data Loading & Inspection**
   - Loaded the Zomato dataset
   - Examined the dataset structure and data types
   - Performed descriptive analysis

2. **Data Cleaning & Preprocessing**
   - Identified missing values
   - Converted online delivery information into binary values
   - Detected and handled outliers using the IQR method
   - Applied feature normalization

3. **Exploratory Data Analysis**
   - Analyzed restaurant ratings
   - Examined votes and customer engagement
   - Compared restaurant costs and ratings
   - Studied cuisine distributions
   - Analyzed city-wise patterns

4. **Data Visualization**
   - Distribution plots
   - Violin plots
   - Boxplots
   - Hexbin plots
   - Bubble charts
   - Quadrant analysis

## 📈 Key Areas Explored

### Restaurant Ratings

The project examined the distribution of aggregate restaurant ratings and explored whether ratings followed a normal distribution.

### Votes vs. Ratings

A hexbin analysis was used to explore the relationship between customer votes and aggregate ratings.

### Cost vs. Ratings

The analysis examined whether higher restaurant costs were associated with higher ratings.

### Cuisine Analysis

Different cuisine categories were compared based on restaurant ratings, consistency, and customer demand.

### City & Market Analysis

Restaurant pricing, ratings, and customer engagement were compared across major cities to identify differences in market characteristics.

## 🔍 Key Findings

The analysis identified several patterns, including:

- Budget and moderate-price restaurants represented a large portion of the dataset.
- Higher restaurant prices did not necessarily correspond to higher ratings.
- Customer vote counts and aggregate ratings did not show a simple direct relationship.
- Different cuisines showed relatively similar median rating patterns.
- Restaurant markets varied across cities in terms of pricing, ratings, and customer engagement.

## 📂 Repository Contents

```text
zomato-market-restaurant-analytics/
│
├── README.md
└── zomato_restaurant_analytics.ipynb
