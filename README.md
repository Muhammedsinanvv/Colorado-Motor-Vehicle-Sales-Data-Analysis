# Colorado-Motor-Vehicle-Sales-Data-Analysis
A comprehensive data analytics project analyzing motor vehicle sales trends across Colorado counties from 2008 to 2023. This project demonstrates proficiency in time series analysis, predictive modeling, and data visualization using Python and machine learning techniques.

- Domain: Financial Analytics

- Duration: Full quarterly time series (2008–2023)

# Objectives:-

- Identify long-term trends and seasonal patterns in vehicle sales

- Forecast future sales performance using time series models

- Build predictive models to understand factors influencing sales

- Provide actionable insights for automotive and economic analysts

# Key Insights:-

- Seasonal Peaks: Q2 and Q4 show consistently higher sales, reflecting consumer behavior and model year releases.

- Economic Indicator: Sales dropped significantly during the 2008–2009 financial crisis, demonstrating market sensitivity to economic conditions.

- Overall Growth: Despite volatility, the market recovered and grew from 2008–2023, showing resilience.

- County Variations: Denver and Arapahoe counties dominate sales; rural counties show lower but steady performance.

- Forecasting Works: Both ARIMA and Random Forest models accurately predict future sales based on historical patterns.

- Non-Linear Factors: Random Forest outperformance suggests complex relationships in sales drivers beyond simple linear trends.

# Files Included:-

- Colorado_Vehicle_Sales_Analysis.ipynb - analysis notebook

- colorado_motor_vehicle_sales.csv - Source Data file

- sales_forecast.csv -  Contains the forecasted sales results for the next 8 quarters generated from the ARIMA model

- model_performance.csv - Contains the Random Forest model performance metrics

- Screenshots - Visualization Previews


================================================================================
# COLORADO MOTOR VEHICLE SALES DATA ANALYSIS REPORT
================================================================================

1. DATA OVERVIEW
────────────────────────────────────────────────────────────────────────────────
   - Time Period: 2008 - 2015
   
   - Total Records: 501
   
   - Number of Counties: 17
   
   - Total Sales: $88205.30M

2. KEY FINDINGS
────────────────────────────────────────────────────────────────────────────────
   -  Average Quarterly Sales: $176.06M
   
   - Peak Sales Year: 2015
   
   - Top County: Arapahoe ($20142.32M total)
   
   - Most Sales Quarter: Q3

3. STATISTICAL ANALYSIS
────────────────────────────────────────────────────────────────────────────────
   -  Seasonal Pattern: Identified quarterly seasonality in sales data

   - Trend: Overall upward trend observed

   - Correlation: Strong positive correlation among top county sales

5. PREDICTIVE MODELING
────────────────────────────────────────────────────────────────────────────────
   
   ARIMA Model (Time Series Forecasting):
   - Model: ARIMA(2,1,2)
   
   - Forecast Horizon: 8 quarters (2 years)
   
   - Next Quarter Forecast: $3435.43M
   
   Random Forest Model:
   -  Test RMSE: $21.21M
   
   - Test R² Score: 0.9829
   
   - Test MAE: $14.58M

   - Most Important Feature: County

7. BUSINESS INSIGHTS
────────────────────────────────────────────────────────────────────────────────
   -  Denver metro area (Arapahoe, Denver, Jefferson) dominates sales
     
   - Q4 typically shows strongest sales performance

   - County location is the most important predictor of sales

   - Sales show recovery trend after 2008 financial crisis

9. RECOMMENDATIONS
────────────────────────────────────────────────────────────────────────────────
   - Focus marketing efforts in high-performing counties
   
   - Increase inventory in Q4 to meet seasonal demand
   
   - Monitor economic indicators for early warning of sales shifts

   - Develop county-specific strategies based on local trends


