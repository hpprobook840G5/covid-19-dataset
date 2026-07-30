COVID-19 Data Analysis

An end-to-end exploratory data analysis project on global COVID-19 data using Python, Pandas, NumPy, and Matplotlib.

Project Overview

The objective of this project was to clean, prepare, analyze, and visualize COVID-19 data to identify global, country-wise, regional, and time-based trends.

The dataset covers 22 January 2020 to 27 July 2020, with data from 187 countries/regions and 6 WHO regions.

Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Data Preparation & Cleaning

The dataset was examined for:

Missing values
Duplicate records
Data types
Date formatting
Province/state-level records

Province/State contained a significant number of missing values, which were retained because they represented countries without province-level reporting rather than invalid data.

The Date column was converted to a proper datetime format for time-series analysis.

Country-level data was aggregated to handle countries with multiple province/state records.

Exploratory Data Analysis

The analysis was performed at three levels:

Global Analysis

Total recorded values:

Confirmed cases: 16,248,167
Deaths: 640,049
Recovered: 9,368,365
Active cases: 6,239,753

Calculated rates:

Recovery rate: 57.66%
Active case rate: 38.40%
Death rate: 3.94%
Country Analysis

The analysis included rankings for:

Top 10 countries by confirmed cases
Top 10 countries by active cases
Top 10 countries by recovered cases
Top 10 countries by deaths

The United States ranked highest in confirmed, active, and death cases, while Brazil recorded the highest number of recoveries.

WHO Region Analysis

Key findings:

Americas had the highest confirmed cases.
Americas also had the highest active cases.
Eastern Mediterranean had the highest recovered cases.
Europe recorded the highest number of deaths.
Western Pacific was the least affected region based on confirmed cases.
Time-Series Analysis

Daily data was analyzed to understand how COVID-19 developed over the study period.

Key observations:

Confirmed cases and deaths showed relatively gradual growth until around March.
From April onwards, both showed a much steeper, approximately exponential growth pattern.
Recoveries increased more gradually and lagged behind the rise in confirmed cases.
The largest daily increase in confirmed cases in the analyzed dataset occurred on 23 July 2020, with approximately 282,756 new cases.
Visualizations

The project includes:

Top 10 country horizontal bar charts
WHO region bar charts
Confirmed, death, and recovery comparisons
COVID-19 time-series line charts
Daily new case analysis
WHO region share pie chart
Key Takeaways

The analysis shows a strong increase in global COVID-19 cases from April onwards, with the Americas carrying the largest overall burden in the dataset. Country and regional comparisons also show that confirmed cases, active cases, recoveries, and deaths can have significantly different rankings.
