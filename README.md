# Retail-AI-Optimisation-System

## Overview

This project aims to develop an end-to-end machine learning system to optimise retail inventory management through demand forecasting and identifying potential overstocking risks.

The system will investigate whether machine learning models can improve stock ordering decisions compared with traditional historical averaging methods by analysing historical sales patterns, product information and external factors affecting consumer demand.

---

## Business Problem

Retail businesses must balance product availability with reducing waste. Poor demand estimation can result in overstocking, missed sales opportunities, increased operational costs and inefficient inventory decisions.

Traditional stock ordering methods often rely on historical averages, which may not capture changing consumer behaviour, seasonal patterns, promotional effects or external events.

This project explores whether data-driven forecasting can provide more accurate demand predictions and support improved inventory management decisions.

---

## Motivation

This project was inspired by the challenges involved in retail inventory management. Working in a retail environment highlighted the importance of balancing product availability with reducing unnecessary stock and waste.

This project explores how machine learning and data analytics can support better decision-making by identifying demand patterns that may not be immediately visible through manual analysis.

---

## Objectives

- Build a data pipeline to process and transform retail transaction data
- Design and implement a structured SQL database for retail analytics
- Perform exploratory data analysis to identify demand patterns and trends
- Develop machine learning models for demand forecasting
- Compare machine learning performance against a historical average baseline
- Identify products with increased overstocking risk based on demand behaviour
- Generate actionable business recommendations from model outputs

---

## Proposed Approach

1. Data collection and understanding
2. Data cleaning and preprocessing
3. ETL pipeline development
4. SQL database design and implementation
5. Exploratory data analysis
6. Feature engineering
7. Machine learning model development
8. Model evaluation against baseline methods
9. Business insight generation
10. Dashboard/application development

---

## Technologies Used

- Python
- SQL
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Power BI
- Git

---

# Dataset

This project uses the Corporación Favorita Grocery Sales Forecasting dataset, which contains historical supermarket sales data from Ecuador.

The dataset was selected because it represents realistic retail forecasting challenges and provides multiple factors that can influence consumer demand. This allows the project to investigate whether machine learning models can improve stock ordering decisions compared with traditional historical averaging methods.

The dataset includes:

- Historical daily sales data (`unit_sales`)
- Product information, including product categories and perishability
- Store information, including location and store clusters
- Promotional information
- Transaction counts
- Holiday and event information
- External economic factors, including oil prices

The dataset also contains real-world data challenges, including:

- Missing promotional values
- Negative sales values representing product returns
- Products with limited historical sales information
- Changes in consumer behaviour caused by external events

These challenges provide an opportunity to demonstrate data cleaning, feature engineering and model evaluation techniques required in real-world data science projects.

The dataset will be processed through an ETL pipeline before being stored in a structured SQL database for analysis and machine learning development.

---

# Research Questions

## Can historical sales data predict future demand?

Historical sales data should provide useful signals for predicting future demand, as purchasing patterns often contain trends, seasonality and recurring behaviours.

However, predictions are unlikely to be perfectly accurate due to external factors that cannot always be captured, such as sudden changes in consumer behaviour, social media trends, promotions, weather conditions and market changes.

This project will evaluate how accurately historical data can predict future demand and identify the limitations of relying only on past sales behaviour.

---

## Which products are most difficult to forecast?

Products with unpredictable consumer demand are expected to be more difficult to forecast. This may include fresh produce, seasonal products and items affected by changing consumer trends.

The project will analyse forecasting errors across different product categories to identify which products create the greatest prediction challenges.

Factors such as perishability, demand volatility and promotional effects will be investigated.

---

## Can we identify overstocking risks?

A machine learning system may be able to identify products with increased overstocking risk by detecting changes in demand patterns earlier than traditional manual analysis.

By analysing declining sales trends, unusual purchasing behaviour and demand uncertainty, the system could highlight products requiring further investigation or adjustments to ordering decisions.

---

## Can machine learning improve stock ordering decisions compared with simple historical averages?

Traditional stock ordering methods often rely on historical averages, such as previous sales volumes, to estimate future demand.

While this approach can work for products with consistent purchasing patterns, it may fail to capture changing trends, seasonal effects and shifts in consumer behaviour.

This project investigates whether machine learning models can improve demand predictions by identifying more complex patterns within historical sales data.

The performance of machine learning models will be compared against a simple historical average baseline to determine whether the additional complexity provides measurable improvements.

---

# Project Roadmap

## Phase 1: Research and Planning

- Research the retail forecasting problem
- Analyse and select the dataset
- Define project requirements
- Design database structure

## Phase 2: Data Engineering and Analysis

- Build ETL pipeline
- Clean and transform raw data
- Store processed data in SQL database
- Perform exploratory data analysis

## Phase 3: Machine Learning Development

- Create forecasting features
- Develop machine learning models
- Compare models against baseline approaches
- Evaluate model performance

## Phase 4: Application and Documentation

- Develop recommendation dashboard/application
- Generate business insights
- Document methodology and results
- Produce final project report

---

# Success Criteria

The success of this project will be evaluated across three areas: machine learning performance, data quality and user experience.

## Machine Learning Performance

- The demand forecasting model should provide accurate predictions of future product demand.
- Machine learning models should be compared against a simple historical average baseline to determine whether predictive modelling provides measurable improvements.
- Model performance will be evaluated using appropriate regression metrics, including Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- The system should demonstrate whether improved predictions can support better stock ordering decisions.

## Data Quality and Organisation

- Raw retail data should be cleaned, structured and transformed into a reliable format suitable for analysis and machine learning.
- The ETL pipeline should successfully extract, transform and load data into an organised database structure.
- Data processing should handle common data quality issues, including missing values, duplicate records and inconsistent formats.
- The final dataset should be well documented and easy to understand for future analysis.

## User Experience

- The final application/dashboard should provide an understandable interface for viewing demand predictions and business insights.
- Users should be able to interpret model outputs without requiring technical machine learning knowledge.
- The system should provide clear error messages and feedback mechanisms to improve reliability and usability.

---

# Model Evaluation

Models will be evaluated using forecasting metrics suitable for regression problems, including:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

Machine learning models will be compared against a simple historical average baseline to determine whether they provide improved forecasting performance.

---

# Future Improvements

Potential future improvements include:

- Incorporating additional external data sources
- Deploying the model using cloud infrastructure
- Implementing real-time data updates
- Adding a natural language assistant for querying retail insights
- Improving recommendations using optimisation techniques
