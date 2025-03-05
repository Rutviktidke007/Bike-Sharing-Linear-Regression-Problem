# Bike-Sharing Demand Analysis Using Linear Regression

## Project Overview
This project aims to identify the key factors influencing bike sales using **Linear Regression**. By analysing various independent variables, we determine their impact on bike demand and provide actionable business insights. 

## Dataset
The dataset contains **5,000+ records** with features such as **seasonality, temperature, weather conditions, holidays, and working days**.

## Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values by imputing averages or removing inconsistent records.
   - Ensured categorical variables were properly encoded.
   
2. **Exploratory Data Analysis (EDA)**
   - Conducted **correlation analysis, box plots, and statistical summaries**.
   - Identified key relationships between independent variables and bike demand.
   
3. **Feature Selection & Model Optimisation**
   - Built a **Linear Regression model** to predict bike sales.
   - Dropped multicollinear variables using **Variance Inflation Factor (VIF < 5)**.
   - Eliminated statistically insignificant variables (**p-value < 0.05**).
   - Iteratively optimised the model, improving **R² from 0.76 to 0.82**.
   
## Key Findings & Business Insights
- **Seasonality impacts bike sales**, with demand peaking in September and lowest in Spring.
- **Temperature strongly correlates** with demand, while bad weather negatively affects usage.
- **Holidays and weekdays have minimal impact**, indicating consistent user behaviour.
- The optimised model provides **accurate demand forecasting** for strategic decision-making.

## Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels)
- **Linear Regression, Feature Selection (VIF, p-values), Data Visualisation**


## Conclusion
This project successfully identifies the key factors influencing bike demand using **Linear Regression**, providing actionable insights for business strategy and demand forecasting. 


