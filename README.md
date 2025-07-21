Sales Forecasting & Analytics Dashboard
Date: July 21, 2025
Author: Manav Singh
Overview
This project provides an end-to-end workflow for sales forecasting and analysis, using Python for machine learning and Power BI for interactive business dashboards.
It is designed for users of all skill levels to visualize sales trends, perform comparisons, and extract actionable insights.

Tech Stack
Technology	Purpose
Power BI Desktop	Data visualization and dashboard building (trend lines, comparisons, KPIs, filtering)
Python 3.8+	Data preprocessing, feature engineering, machine learning modeling
Jupyter Notebook / VS Code	Developing and running Python code and notebooks
Pandas	Data manipulation, cleaning, aggregation for analysis and forecasting
Numpy	Numeric operations and calculations needed for feature engineering
XGBoost	Machine learning (gradient boosting) for sales forecasting
Matplotlib	Visualization of results in Python (exploratory/analytical charts)
CSV	Data storage and exchange format (Power BI <-> Python)
Repository Structure
text
├── data/
│   └── powerbi_sales_forecast_data.csv          # Sample data
├── notebooks/
│   └── sale_forecasting_model.ipynb             # Python forecasting code (XGBoost)
├── dashboard/
│   └── sales_dashboard.pbix                     # Power BI dashboard
├── requirements.txt                             # Python dependencies
├── README.md                                    # Project documentation
Getting Started
Prerequisites
Install Power BI Desktop
Install Python 3.8+ and required libraries (see requirements.txt)
(Recommended) Jupyter Notebook or VS Code for executing Python scripts
Data
Put the sales data file in the data/ directory as powerbi_sales_forecast_data.csv.
It should contain at least: Date, Sales, Category, Region, Store, etc.
Forecasting with Python
Open notebooks/sale_forecasting_model.ipynb
Run the cells as instructed:
Load and clean data
Create lag/rolling features
Train XGBoost model
Save forecast results for Power BI
Power BI Dashboard
Open dashboard/sales_dashboard.pbix in Power BI Desktop.
Make sure data source paths match your environment.
Use built-in filters and visuals:
Trend lines (actual vs. forecast)
Month/year comparison
High/low periods
KPI/summary cards
Customization
Adjust visuals and calculations in Power BI for your business context.
Re-train or tweak the Python model for improved forecasts as needed.
Contributing
Contributions are welcome. Please open an issue first to discuss your ideas.
License
MIT License (or specify your own).
Contact
For help or suggestions, contact singh507manav@gmail.com.
