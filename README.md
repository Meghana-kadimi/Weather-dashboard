# Flask Weather App

A simple **Flask web application** that fetches **real-time weather** and **Air Quality Index (AQI)** data using the OpenWeatherMap API.  
The app stores recent search history, generates a chart of weather stats, and displays alerts for extreme weather conditions.

---

## Features
- Search weather by city name 
- Fetch **temperature, humidity, wind speed, and conditions**
- Show **Air Quality Index (AQI)**
- Display **weather alerts** (e.g., high temperature, rain)
- Save **recent 5 search history** using SQLite
- Generate **bar chart visualization** with Matplotlib
- Responsive and user-friendly UI

---

## Tech Stack
- **Backend:** Flask, Flask-SQLAlchemy  
- **Frontend:** HTML + Jinja templates  
- **Database:** SQLite  
- **API:** OpenWeatherMap (Weather + AQI)  
- **Other:** Matplotlib for charts  

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Meghana-kadimi/weather-dashboard.git
cd weather-dashbooard
