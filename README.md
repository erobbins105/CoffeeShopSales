#### This project explores [transactional data from a fictional coffee shop](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training/data), including details such as date and time of purchase, product names, categories, quantities, and prices. The dataset captures trends across different locations, time periods, and product types.
Dataset Credit: [Ahmed Mohamed](https://www.kaggle.com/ahmedmohamed2003).

#### **Goal**:
The primary aim is to derive actionable business insights that can help increase revenue and improve operational efficiency. This includes identifying peak sales periods, top-performing items, customer purchasing behavior, and opportunities for upselling or inventory optimization. In addition to descriptive analysis, the project applies machine learning to forecast future sales and segment customer purchasing behavior.

#### **Key skills and tools demonstrated**:
- **Data Cleaning & Preparation**  
  - Used `pandas` to handle missing values, parse timestamps, and standardize product names and categories  
  - Engineered features such as day-of-week, hour, and holiday indicators to enrich the dataset for modeling

- **Exploratory Data Analysis (EDA)**  
  - Analyzed sales by product category, time of day, and location  
  - Identified high-revenue items and underperforming products using aggregation and `groupby` operations

- **Data Visualization**  
  - Built plots with `matplotlib` and `seaborn` to uncover trends, seasonal patterns, and peak sales periods  
  - Visualized model predictions vs. actual sales to assess performance

- **Machine Learning Applications**  
  - Built regression models (e.g., `LinearRegression`, `RandomForestRegressor`) to forecast daily or weekly sales  
  - Applied unsupervised learning (`KMeans`) to cluster customer purchase behaviors and identify key segments  
  - Evaluated models using metrics like RMSE and silhouette score

- **Insight Communication**  
  - Translated model results and EDA findings into actionable business insights  
  - Recommended strategies based on data patterns, such as product bundling or adjusted store hours
