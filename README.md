# Supermarket_Sales_Forecasting


This sales forecasting project aims to predict next-week sales for the top 5 fast-moving categories within selected departments and stores. The key departments for this task are Grocery, Beverages, and Chilled, while the focus stores include A, B, C, D, and E. The core objective is to develop a robust predictive model that can accurately forecast future sales based on historical transactional data.

#### Approach Overview:

**Descriptive Analysis:** The first step involves performing thorough exploratory data analysis (EDA) on the available dataset to understand sales trends, validate assumptions, and identify significant patterns or correlations. Descriptive statistics, visualizations, and hypothesis testing will be employed to ensure data quality and determine the key drivers for sales in different departments and stores.

**Folder Structure:** The project is organized under a well-defined folder structure for maintainability, with the following sections:

- Data Processing: Preprocess raw data to generate useful inputs.
- Primary Keys: Identify unique keys like outlet, item category, and week.
- Target Variable: Define the sales target for next week.
- Feature Engineering: Derive features related to sales, item characteristics, time, and outlets to improve model performance.
- Pipeline Creation: A modular pipeline will be created under the src/ folder, enabling easy testing, scalability, and maintainability:
- Model Training: Fits a predictive model on the prepared dataset to generate accurate sales forecasts.

**Model Fitting and Evaluation:** A forecasting model will be trained using the historical data to predict sales for the top 5 fast-moving categories. The model's performance will be assessed using Mean Absolute Percentage Error (MAPE) at following granular level:

- Outlet | Item Category | Week

The project provides a comprehensive solution for forecasting sales for different departments and stores, helping to improve inventory management, optimize supply chain operations, and ensure that businesses can meet customer demand effectively.
