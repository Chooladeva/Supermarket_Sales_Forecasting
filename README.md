# Supermarket Sales Forecasting

This project focuses on **predicting next-week sales** for the top 5 fast-moving categories across selected departments and stores. Key departments include **Grocery, Beverages, and Chilled**, while target stores are **A, B, C, D, and E**. The objective is to develop a **robust predictive model** using historical transactional data to improve inventory management and supply chain operations.

---

## **Project Overview**

1. **Descriptive Analysis (EDA):**  
   - Explored historical sales data to identify trends, patterns, and correlations.  
   - Validated assumptions and ensured data quality using descriptive statistics, visualizations, and hypothesis testing.  
   - Determined key drivers affecting sales across departments and stores.

2. **Folder Structure & Pipeline Organization:**  
   The project is structured for **maintainability and scalability**:
   - **Data Processing:** Clean and preprocess raw data to generate model-ready inputs.  
   - **Primary Keys:** Identify unique identifiers such as outlet, item category, and week.  
   - **Target Variable:** Define sales for the next week as the prediction target.  
   - **Feature Engineering:** Create features based on sales history, item characteristics, time, and outlet information.  
   - **Pipeline Creation (`src/` folder):** Modular pipeline for preprocessing, feature engineering, and model training.  
   - **Model Training & Evaluation:** Train predictive models and evaluate performance using **Mean Absolute Percentage Error (MAPE)** at the granularity of **Outlet | Item Category | Week**.

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
