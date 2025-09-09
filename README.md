# Week-2-AI-for-Sustainable-Urban-Water-Demand-and-Distribution

📌 Project Overview

This project focuses on analyzing and predicting water demand and distribution in urban cities using Machine Learning.
It uses synthetic city-level data (Hyderabad, Mumbai, Chennai, Kolkata, Delhi) with features like population, demand, potable/non-potable supply, groundwater levels, rainwater harvesting, and energy consumption.

The main goals are:

1.Predict demand for water based on city parameters.

2.Model potable and non-potable water distribution separately.

3.Identify shortages where demand exceeds supply.



🗂 Dataset Structure : 

City – City name

Area – Local area within the city

Population – People in the area

Daily_Demand_MLD – Daily water demand (Million Litres/Day)

Potable_Available_MLD – Drinking water supply available

NonPotable_Available_MLD – Non-drinking water supply

Recycled_Usage_MLD – Recycled water usage

Rainwater_Harvest_MLD – Rainwater harvested

Groundwater_Level_m – Groundwater level (m)

Energy_Consumption_kWh – Energy used for water pumping/treatment

Water_Loss_% – Distribution losses

Shortage – added the Calculated shortage column (if demand > supply)

⚙️ Tech Stack

Python – Data processing & ML

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

scikit-learn – Machine Learning models (Linear Regression, Random Forest)

Jupyter Notebook  – Development environment

🔑 Models Implemented

=> Demand Prediction Model

Input: Population, groundwater, rainwater harvest

Output: Daily water demand

=> Potable Distribution Model

Predicts drinking water distribution capacity

=>Non-Potable Distribution Model

Predicts non-drinking water distribution (industrial, cleaning, parks, etc.)

=> Combined Distribution Model(Potable + nonPortable)

Predicts total distributed water (potable + non-potable) for urban planning


✅ Results & Insights

R² for potable distribution: ~0.99 (high accuracy)

R² for non-potable distribution: ~0.99 (high accuracy)

Top factors: Population, demand, rainwater harvest, and groundwater strongly affect distribution.



🚀 Next Extensions

Add time-series forecasting (ARIMA, LSTM) if daily/monthly data is available.

Build Power BI dashboards 

Include climate/rainfall predictions for demand estimation.

Optimize energy–demand balance for sustainable pumping.

👨‍💻 Author ->

Developed by Chandrashekar  – B.Tech Data Science | Data Analyst | Web Developer + ML Enthusiast | Power BI 
