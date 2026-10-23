# Retail-AI-Optimisation-System

## Overview

This project aims to develop an end-to-end machine learning system to optimise retail inventory decisions through demand forecasting and waste prediction.

## Business Problem

Retail businesses must balance product availability with reducing waste. Poor demand estimation can result in overstocking, missed sales opportunities, and increased operational costs.

## Objectives

- Build a data pipeline to process retail transaction data
- Develop a demand forecasting model
- Identify products at risk of waste
- Generate actionable business recommendations

## Proposed Approach

1. Data collection and preprocessing
2. ETL pipeline development
3. SQL database design
4. Exploratory data analysis
5. Machine learning model development
6. Evaluation and business insights

## Technologies Used

- Python
- SQL
- Pandas
- Scikit-learn
- XGBoost
- Power BI
- Git

## Research Questions

### Can historical sales data predict future demand?

Historical sales data should provide useful signals for predicting future demand, as purchasing patterns often contain trends, seasonality and recurring behaviours. However, predictions are unlikely to be perfectly accurate due to external factors that cannot always be captured, such as sudden changes in consumer behaviour, social media trends, promotions, weather conditions and market changes.

This project will evaluate how accurately historical data can predict future demand and identify the limitations of using past sales behaviour.

---

### Which products are most difficult to forecast?

Products with unpredictable consumer demand are expected to be more difficult to forecast. This may include fresh produce, seasonal items and products influenced by changing consumer trends.

For example, health trends and social media influence can rapidly change demand for certain foods, meaning historical sales patterns may not always represent future behaviour.

This project will analyse forecast errors across different product categories to identify which products are most challenging to predict.

---

### Can we identify waste risks?

A machine learning system may be able to identify products at higher risk of waste by detecting changes in demand patterns earlier than traditional manual analysis.

By monitoring declining sales trends, unusual purchasing behaviour and historical waste patterns, the system could highlight products requiring further investigation or adjustments to ordering decisions.

### Can machine learning improve stock ordering decisions compared with simple historical averages?

Traditional stock ordering methods often rely on historical averages, such as previous sales volumes, to estimate future demand. While this approach can work for products with consistent purchasing patterns, it may fail to capture changing trends, seasonal effects and shifts in consumer behaviour.

This project investigates whether machine learning models can improve demand predictions by identifying complex patterns within historical sales data. Improved predictions could help businesses allocate stock more effectively by increasing availability of high-demand products while reducing investment in products with declining demand.

The performance of machine learning models will be compared against a simple historical average baseline to determine whether the additional complexity provides measurable improvements

## Project Roadmap

Phase 1:
- Research problem
- Obtain dataset
- Design database

Phase 2:
- Build ETL pipeline
- Perform exploratory analysis

Phase 3:
- Develop forecasting models
- Compare against baseline

Phase 4:
- Build recommendation dashboard
- Document findings

## Success Criteria

The success of this project will be evaluated across three areas: machine learning performance, data quality, and user experience.

### Machine Learning Performance

- The demand forecasting model should provide accurate predictions of future product demand.
- Machine learning models should be compared against a simple historical average baseline to determine whether predictive modelling provides measurable improvements.
- Model performance will be evaluated using appropriate regression metrics, including Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- The system should demonstrate whether improved predictions can support better stock ordering decisions.

### Data Quality and Organisation

- Raw retail data should be cleaned, structured and transformed into a reliable format suitable for analysis and machine learning.
- The ETL pipeline should successfully extract, transform and load data into an organised database structure.
- Data processing should handle common data quality issues, including missing values, duplicate records and inconsistent formats.
- The final dataset should be well documented and easy to understand for future analysis.

### User Experience

- The final application/dashboard should provide an understandable interface for viewing demand predictions and business insights.
- Users should be able to interpret model outputs without requiring technical machine learning knowledge.
- The system should provide clear error messages and feedback mechanisms to improve reliability and usability.

