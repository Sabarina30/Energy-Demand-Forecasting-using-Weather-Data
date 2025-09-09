# Energy Demand Forecasting Project ⚡

## Project Overview
Accurate energy demand  forecasting is crucial for utilities and industries to ensure reliability,cost optimization and sustainability. Traditional forecasting methods often fail to capture non-linear pattern influenced 
by external factors like weather.

This project analyzes historical electricity consumption patterns, Incorporates weather and seasonal data to improve prediction accuracy.
The goal is to identify patterns, understand correlations with weather features, and build predictive models for short-term demand forecasting.

---
## Dataset
- **Source:** [Specify source, e.g., UCI, Delhi Power & Weather Data]  
- **Columns:**
  - 'datetime': Timestamp of observation
  - 'Power demand': Energy demand in MW
  - `temp`: Temperature (°C)
  - `dwpt`: Dew point (°C)
  - `rhum`: Relative humidity (%)
  - `wdir`: Wind direction (°)
  - `wspd`: Wind speed (m/s)
  - `pres`: Atmospheric pressure (hPa)
  - `year`, `month`, `day`, `hour`, `minute`: Extracted time features
  - `moving_avg_3`: 3-hour moving average of power demand

---

## Steps Followed

1. **Data Cleaning**
   - Handled missing values using:
     - Interpolation for `wdir`
     - Backward fill for `moving_avg_3`
   - Verified that no columns have missing values.

2. **Exploratory Data Analysis (EDA)**
   - Visualized power demand trends over time.
   - Analyzed correlations between weather variables and energy demand.
   - Used moving averages to observe short-term trends.

3. **Feature Engineering**
   - Created time-based features: year, month, day, hour, minute.
   - Added lag features to help with forecasting models.

4. **Modeling & Forecasting**
   - Considered machine learning models (Random Forest, XGBoost) for non-linear patterns.

5. **Visualization**
   - Plotted demand trends, correlations, and model predictions.
   
---

## 

