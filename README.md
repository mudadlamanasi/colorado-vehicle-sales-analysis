# 🚗 Colorado Motor Vehicle Sales Forecasting 📊

This project presents a comprehensive analysis and forecasting model for quarterly motor vehicle sales across counties in Colorado. It aims to uncover sales trends, assess seasonality, and predict future sales using time series modeling. The data is visualized using Python and Tableau to support strategic business or policy decisions.

---

## 📁 Dataset

**Name:** `colorado_motor_vehicle_sales.csv`  
**Source:** Provided in project context  
**Columns:**
- `year`: Year of the sales record
- `quarter`: Quarter of the year (1 to 4)
- `county`: County in Colorado
- `sales`: Total motor vehicle sales (in dollars)

---

## 🎯 Objectives

- Analyze historical vehicle sales data
- Visualize quarterly trends and seasonality
- Forecast future sales using ARIMA
- Create interactive Tableau dashboards

---

## 🛠️ Tools & Technologies

| Tool        | Usage                                |
|-------------|---------------------------------------|
| Python      | Data analysis, time series modeling  |
| Jupyter Notebook | Exploratory & predictive analysis |
| ARIMA (Statsmodels) | Forecasting future sales        |
| Tableau     | Interactive visualization dashboards |
| Git & GitHub| Version control and project sharing  |

---

## 📈 Python Analysis & Modeling

### Key Steps:
1. **Data Cleaning & Aggregation**  
   Converted year & quarter to a datetime format, aggregated total sales per quarter.

2. **Exploratory Data Analysis (EDA)**  
   Visualized trends and patterns using Matplotlib and Seaborn.

3. **Seasonal Decomposition**  
   Performed to identify trend and seasonal components.

4. **ARIMA Forecasting Model**  
   - ARIMA(5,1,0) fitted to time series
   - Forecasted the next 8 quarters of sales
   - Evaluation using Mean Squared Error (MSE):  
     `7.82e+16`

---

## 📊 Tableau Dashboard

The project includes a Tableau visualization dashboard with:
- Quarterly sales trends over time
- County-level comparison
- Filters for year, quarter, and county
- Forecasting using Tableau's built-in model

## 📌 Results & Takeaways

- Vehicle sales exhibit clear seasonal trends (peaking in Q2–Q3).
- ARIMA model provides a reliable sales forecast.
- Tableau dashboard offers an interactive view for business users.
- The project supports economic insights and inventory planning strategies.

---

## 🔍 Future Improvements

- Incorporate external factors (e.g., fuel prices, population growth)
- Explore advanced ML models like XGBoost, SARIMA
- Add predictive segmentation by county

---

## 🤝 Contact

**Author:** Manasi Mudadla  
**Connect:** [LinkedIn](https://www.linkedin.com/in/manasimudadla)  
**Email:** [manasimudadla0902@gmail.com]

---

> ⭐ If you found this project insightful, feel free to star the repo and share your thoughts!
