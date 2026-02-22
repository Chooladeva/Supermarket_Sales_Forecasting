# Supermarket Sales Forecasting — Next-Week Demand Prediction

## Executive Summary

This project develops a robust machine learning pipeline to predict next-week sales for the top 5 fast-moving categories across selected supermarket departments and stores.

**Target departments include:**

- Grocery
- Beverages
- Chilled

**Target outlets:**

- Store A
- Store B
- Store C
- Store D
- Store E

The objective is to improve inventory optimization, replenishment planning, and supply chain efficiency by leveraging historical transactional data and structured forecasting techniques.

## Business Problem

Retail environments require accurate short-term forecasts to:

- Prevent stockouts
- Reduce overstocking
- Optimize working capital
- Improve customer satisfaction
- Traditional rule-based replenishment methods fail to capture:
- Weekly seasonality
- Store-level variations
- Category-level demand fluctuations
- Promotion-driven demand shifts

This project addresses these limitations through a data-driven forecasting framework.

## Exploratory Descriptive Analysis (EDA):
   - Explored historical sales data to identify trends, patterns, and correlations.  
   - Validated assumptions and ensured data quality using descriptive statistics, visualizations, and hypothesis testing.  
   - Determined key drivers affecting sales across departments and stores.

EDA ensured that modelling assumptions were grounded in data behavior rather than guesswork.

## Project Architecture

The project is structured for maintainability, scalability, and production readiness.

### Folder Structure & Pipeline Organization:

The project is structured for **maintainability and scalability**:

├── data/
├── notebooks/
├── src/
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
├── models/
├── outputs/
└── README.md

---

## **Key Benefits**

- Provides **accurate sales forecasts** for top-selling categories.  
- Enables better **inventory planning and stock optimization**.  
- Supports **supply chain management** by predicting customer demand effectively.  
- Modular pipeline allows easy **scalability and adaptation** for additional stores or categories.

---

## **Technologies Used**

- **Programming:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Pipeline Management:** Modular Python scripts (`src/` folder)  
- **Evaluation Metrics:** Mean Absolute Percentage Error (MAPE)  

---

The project provides a comprehensive solution for forecasting sales for different departments and stores, helping to improve inventory management, optimize supply chain operations, and ensure that businesses can meet customer demand effectively.
