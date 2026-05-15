Maximize Revenue for Drivers Through Payment Type
Project Overview

This project analyzes NYC Yellow Taxi Trip data to identify how payment methods influence taxi driver revenue, customer tipping behavior, and trip characteristics. The analysis focuses on comparing card and cash payments using statistical analysis, data preprocessing, and visualization techniques.

The primary objective is to determine whether encouraging digital payment methods can help maximize driver earnings.

Business Problem

Taxi drivers earn revenue through:

Fare amount
Tips
Additional surcharges

Customer payment behavior can significantly affect total earnings, especially tip amounts. This project investigates whether payment type impacts overall driver revenue.

Dataset

Dataset used:

NYC Yellow Taxi Trip Data
Source: NYC Taxi and Limousine Commission (TLC)

The dataset contains information about:

Pickup and dropoff times
Passenger counts
Trip distance
Fare amount
Tip amount
Total payment amount
Payment type

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Statsmodels
SciPy
Jupyter Notebook

Project Workflow
1. Data Loading
Imported NYC taxi dataset using Pandas
Loaded selected rows for analysis
2. Data Cleaning
Converted datetime columns
Created trip duration feature
Checked missing values
Removed outliers using IQR method
3. Exploratory Data Analysis (EDA)

Performed:

Distribution analysis
Correlation analysis
Payment type comparison
Passenger behavior analysis
Revenue visualization


4. Statistical Analysis
Descriptive statistics
Q-Q plot analysis
Hypothesis testing using t-test
Revenue comparison by payment type


Key Insights
Card payments generated higher average revenue compared to cash payments.
Customers using card payments provided higher average tips.
Most taxi rides involved 1–2 passengers.
Fare amount showed strong positive correlation with trip distance.
Revenue distribution was right-skewed due to high-value trips.


Visualizations Included
Pie charts
Bar charts
Stacked horizontal bar charts
Histograms
Correlation matrix
Q-Q plots
Box plots

Statistical Methods Used
Correlation Analysis

Used Pearson correlation to measure relationships between:

Fare amount
Trip distance
Duration

Hypothesis Testing
Performed t-test to determine whether payment type significantly affects driver revenue.

Conclusion
The analysis indicates that digital/card payments contribute significantly higher driver revenue and customer tips compared to cash payments.
Encouraging customers to use digital payment methods can help taxi drivers maximize overall earnings.

