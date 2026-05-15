# 🚖 Maximize Revenue for Drivers Through Payment Type

## 📊 Project Overview

This project analyzes **NYC Yellow Taxi Trip Data** to understand how **payment methods (card vs cash)** influence:

- Driver revenue
- Customer tipping behavior
- Trip characteristics

The core objective is to evaluate whether encouraging **digital payments** can help maximize overall taxi driver earnings.

---

## 🧩 Business Problem

Taxi drivers generate income through:

- Fare amount
- Tips
- Additional surcharges

Customer payment behavior can significantly impact total earnings, especially tips.

### Key Question:
> Does payment type affect total driver revenue and tipping behavior?

---

## 📁 Dataset Information

- **Dataset:** NYC Yellow Taxi Trip Data  
- **Source:** NYC Taxi & Limousine Commission (TLC)

### Features Used:
- Pickup & dropoff timestamps  
- Passenger count  
- Trip distance  
- Fare amount  
- Tip amount  
- Total amount  
- Payment type  

---

## 🛠️ Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Statsmodels  
- Jupyter Notebook  

---

## 🔄 Project Workflow

### 1. Data Loading
- Imported NYC taxi dataset using Pandas
- Selected relevant data for analysis

### 2. Data Cleaning
- Converted datetime columns
- Created trip duration feature
- Handled missing values
- Removed outliers using IQR method

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis
- Correlation analysis
- Payment type comparison
- Passenger behavior insights
- Revenue visualization

### 4. Statistical Analysis
- Descriptive statistics
- Q-Q plot analysis
- Hypothesis testing (t-test)
- Revenue comparison across payment types

---

## 🔍 Key Insights

- 💳 Card payments generate higher average revenue than cash payments  
- 💳 Card users tend to give higher tips  
- 👥 Most trips involve 1–2 passengers  
- 📏 Fare amount is strongly correlated with trip distance  
- 📊 Revenue distribution is right-skewed due to high-value trips  

---

## 📈 Visualizations

The project includes multiple visual analytics:

- Pie charts (payment distribution)
- Bar charts (revenue comparison)
- Stacked bar charts
- Histograms (distribution analysis)
- Correlation heatmap
- Q-Q plots (normality check)
- Box plots (outlier detection)

---

## 📊 Statistical Methods

### 📌 Correlation Analysis
Used Pearson correlation to study relationships between:

- Fare amount  
- Trip distance  
- Trip duration  

### 📌 Hypothesis Testing
Performed **t-test** to determine whether:

> Revenue differs significantly between card and cash payments

---

## 📌 Conclusion

The analysis shows that:

- Digital/card payments significantly increase driver revenue
- Card users contribute higher tips compared to cash users

### 💡 Recommendation:
Encouraging digital payment adoption can improve overall taxi driver earnings and operational efficiency.

---

## 🚀 Future Improvements

- Build predictive models for fare and tip estimation
- Perform time-series demand analysis
- Create interactive dashboards (Power BI / Tableau)
- Analyze peak-hour and seasonal revenue trends

---

## 👩‍💻 Author

**Jyoti Behera**  
Frontend & Data Analytics Enthusiast  
📍 Bhubaneswar, Odisha, India  

🔗 LinkedIn: [Profile](https://www.linkedin.com/in/jyoti-behera-5283a72a7)

---

## ⭐ If you like this project
Feel free to star the repository and explore more projects!



