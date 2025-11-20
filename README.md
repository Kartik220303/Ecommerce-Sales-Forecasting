# E-Commerce Sales Forecasting Project  
**Tools:** Python, Pandas, NumPy, Matplotlib, Scikit-Learn, Prophet  
**Skills:** Data Cleaning, EDA, Feature Engineering, ML Modeling, Forecasting  

---

## Executive Summary  
This project analyzes past e-commerce sales data to uncover key patterns and forecast future revenue using machine learning and time-series models.  
The insights help online businesses optimize inventory, pricing, and marketing strategies by predicting demand more accurately.

---

## Business Problem  
E-commerce businesses often struggle with:  
- Unpredictable sales fluctuations  
- Overstocking or understocking inventory  
- Inaccurate demand planning  
- Difficulty estimating future revenue  

**Goal:** Build a system that forecasts sales trends and identifies products driving revenue, enabling data-driven decisions.

---

## Methodology  
1. **Data Collection**  
   - Used two datasets: *products.csv* and *orders.csv*  
   - Merged both to create a unified sales dataset.

2. **Data Cleaning & Preparation**  
   - Removed duplicates and fixed incorrect values  
   - Converted date formats  
   - Created new fields (Revenue, Month, Category)

3. **Exploratory Data Analysis (EDA)**  
   - Identified seasonal patterns, top categories, high-revenue periods  
   - Visualized monthly sales trends  
   - Detected top-selling products and customer behavior

4. **Feature Engineering**  
   - Extracted time features (Year, Month, Week, Day)  
   - Aggregated daily revenue  
   - Prepared dataset for forecasting

5. **Machine Learning & Forecasting**  
   - Regression Models: Random Forest / Linear Regression  
   - Time-Series Model: **Prophet**  
   - Evaluated using MAE, RMSE

6. **Visualization**  
   - Sales trend graphs  
   - Forecast charts  
   - Category-level revenue visuals

---

## Impact  
- Improved sales visibility for future weeks/months  
- Helps businesses plan inventory levels more accurately  
- Reduces risk of stockouts and overstocking  
- Supports marketing teams with promotional timing  
- Increases revenue predictability for better decision-making  

---

## Results  
- Identified consistent sales patterns and seasonal peaks  
- Top-performing product categories contributed highest revenue  
- Prophet model produced reliable forecasts for upcoming months  
- Monthly revenue trends showed significant business growth  
- Regression model predicted sales with stable accuracy  

---

## Business Recommendations  
- **Increase inventory** for products predicted to have rising demand  
- **Run seasonal marketing campaigns** during peak months  
- **Reduce stock** for categories with declining sales  
- **Optimize pricing strategies** based on product performance  
- **Introduce bundle offers** for low-performing items  
- Use forecast insights to **plan warehouse capacity**

---

## Next Steps  
- Integrate live data automation (daily updates)  
- Deploy forecasting model as a dashboard or API  
- Add more ML models like XGBoost or LSTM  
- Include customer segmentation for deeper insights  
- Integrate with Power BI for real-time decision support

---

**Author:**  
Kartik K. N
