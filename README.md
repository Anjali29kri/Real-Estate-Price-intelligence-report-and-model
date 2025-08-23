# Real Estate Price Intelligence & Prediction (2001–2030)

This project delivers data-driven insights and predictive modeling on Connecticut’s real estate market, analyzing 1M+ property records (2001–2021) and forecasting 2030 property prices. It combines data analysis, visualization, and machine learning to support informed decisions for investors, analysts, and policymakers.

## Key Features

-> Interactive Power BI dashboard for KPIs, trends, and regional segmentation.

-> Random Forest regression model (RMSE: 0.68) for accurate price prediction of 3BHK properties by 2030.

-> 2-year sales trend forecasting using Scikit-learn.

-> Analysis of 169 towns across 10 regions with historical performance and future projections.

# Dashboard Overview
## Page 1 – Historical Analysis (2001–2021)

1) KPIs: Total Sales, Properties Sold, Avg. Sales Ratio, Sales Cycle Duration.

2) Distribution Visuals: Property types, flat sizes, and under/overpriced ratios.

3) Geo Maps: Town-wise sales insights.

4) Trend Charts: Yearly and seasonal peaks with filter options.

## Page 2 – Price Forecast for 2030

1) Projected 3BHK sales: $387.33B.

2) Top towns by predicted revenue: Stamford ($14.97B), Bridgeport, Waterbury, Norwalk, New Haven.

3) Feature Importance: Assessed Value, Sales Ratio, Town, and Year.

## Tools & Technologies

-> Data Analysis & Cleaning: Python (Pandas, NumPy)

-> Modeling: Scikit-learn (Random Forest Regression)

-> Visualization: Power BI (DAX for calculated measures)

-> Data Preprocessing: Excel for calculated columns

## Insights Gained

~ Stamford is forecasted as the top-performing town by 2030 with ~$15B in sales.

~ 87% of properties are underpriced, indicating untapped investment potential.

~ Capital and South-Western regions dominate historical and future sales trends.

~ Assessed Value is the strongest predictor of property price fluctuations.

## How to Use

-> Open the Power BI file to explore interactive dashboards.

-> Check the Jupyter notebooks for data cleaning, feature engineering, and model training steps.

-> Use the scripts to replicate the Random Forest model or adapt it for other regions/datasets.
