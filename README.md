# Sales-Forecasting
his project implements a comprehensive sales forecasting system for Walmart using historical sales data. The solution leverages time series analysis, feature engineering, and machine learning to predict future sales across different stores and departments.


Walmart needs to accurately forecast sales to:
Optimize inventory management
Improve supply chain efficiency
Enhance promotional planning
Reduce stockouts and overstock situations
Make data-driven business decisions


The project uses three main datasets from Walmart:
train.csv - Historical sales data (2010-2012)
Store, Department, Date, Weekly_Sales, IsHoliday
features.csv - Additional store information
Store, Date, Temperature, Fuel_Price, MarkDowns (1-5), CPI, Unemployment, IsHoliday
stores.csv - Store metadata
Store, Type, Size
test.csv - Test data for validation
Store, Department, Date, IsHoliday

