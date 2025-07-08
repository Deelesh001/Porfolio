# ☀️ ÖkoStrom Solarpark 2.0 – AI-Powered Solar Forecasting

This project is a smart, AI-powered web application that predicts daily solar energy production using weather data and a trained machine learning model. It also provides real-time energy usage tips based on predicted output — supporting smarter planning for sustainable energy systems.

Developed in collaboration with **E.ON** and **XU Exponential University**.

---

## 🔍 Project Overview

🌍 **Location**: Gerdshagen, Germany  
⚡ **Goal**: Help solar operators or planners estimate daily solar output and adapt energy usage based on forecast conditions.

### 🎯 Key Features
- 🔮 Predict solar energy output based on temperature & cloud cover
- ☁️ Real-time weather data from OpenWeatherMap
- 💡 Smart energy tips based on prediction levels
- 📈 Interactive web interface with Streamlit

---

## 🧠 How It Works

1. Pulls 3-hourly weather forecasts using OpenWeatherMap API
2. Aggregates temperature and cloud coverage for the selected day
3. Estimates solar irradiance from cloud cover
4. Uses a trained regression model (`.pkl`) to predict kWh output
5. Provides energy usage suggestions based on output range

---

## 🖥️ Tech Stack

- **Python**
- **Streamlit** (UI)
- **scikit-learn** (ML model)
- **Requests** (API integration)
- **NumPy, Pandas**
- **OpenWeatherMap API**
- **Docker** (optional for containerization)

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/eon-solar-forecast-app.git
cd eon-solar-forecast-app
