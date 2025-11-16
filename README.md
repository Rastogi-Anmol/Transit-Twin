# 🚊 TransitTwin — Predictive Analytics for City Transit Delays

**TransitTwin** is a machine learning project that builds a *digital twin* of city transit systems.  
Using open public data (transit schedules, weather, and traffic incidents), it predicts bus delay times and visualizes network-wide performance trends.

---

## 🧠 Project Overview
Urban transportation systems are deeply affected by weather, congestion, and time-of-day patterns.  
TransitTwin combines these data sources into a unified pipeline to forecast transit delays and identify high-risk routes.

**Goal:**  
> Predict bus delay (in minutes) for any route–stop–time combination using real-world data.

---

## 🧩 Features
- 🕒 Time-series forecasting using **Prophet** and **XGBoost**
- 🌦️ Integration of **weather**, **traffic**, and **transit** datasets
- 📊 Interactive **Streamlit dashboard** for delay visualization
- 🔍 Feature importance analysis to explain key delay factors
- 🔁 Automated ETL pipeline for data ingestion and refresh

---

## ⚙️ Tech Stack
- **Python** · pandas · numpy · scikit-learn · prophet · xgboost  
- **Visualization:** matplotlib · seaborn · Plotly · Streamlit  
- **Data:** Edmonton Open Data (GTFS, weather, traffic)  
- **Deployment:** Streamlit / Power BI (optional)

---

## 📁 Repository Structure
