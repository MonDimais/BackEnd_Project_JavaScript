
---

# 🌤️ Weather API Wrapper Service  

This project is based on the [Weather API Wrapper roadmap project](https://roadmap.sh/projects/weather-api-wrapper-service).  
It allows users to search for **current weather data** by city name or by using their **current location**.  
The app fetches weather information from the [Open-Meteo API](https://open-meteo.com/) and displays it with location details, weather conditions, and a dynamic UI theme (clear, rainy, snowy, thunderstorm).  

---

## 🚀 Features  
- Search current weather by city name  
- Get weather based on user’s geolocation  
- Weather details: temperature, feels like, humidity, wind, precipitation  
- Icons, sounds, and theming for weather conditions  
- Uses **Open-Meteo Geocoding API** and **Forecast API**  

---

## 📦 Tech Stack  
- **HTML, CSS, JavaScript** (Vanilla JS frontend)  
- **Open-Meteo API** for weather & geocoding data  

---

## 🛠️ Setup Instructions  

### 1. Download the repo or clone it 
```bash
git clone https://github.com/MonDimais/BackEnd_Project_JavaScript.git
```

### 2. Open `weather.html` in your browser  
No extra build steps are required since this is a frontend-only project.  
Double-click `weather.html`.

### 3. Usage  
- Enter a **city name** in the search box and press Enter.  
- Or click the **📍 Location button** to use your current location.  
- The app will fetch and display the current weather.  

---

## 🌍 APIs Used  
1. **Open-Meteo Geocoding API**  
   ```
   https://geocoding-api.open-meteo.com/v1/search?name={city}
   ```
2. **Open-Meteo Weather Forecast API**  
   ```
   https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current=temperature_2m,weather_code,wind_speed_10m,relative_humidity_2m
   ```
3. **Reverse Geocoding API** (when using geolocation)  
   ```
   https://geocoding-api.open-meteo.com/v1/reverse?latitude={lat}&longitude={lon}
   ```

---

## 📖 Reference  
This project is part of the learning roadmap on [roadmap.sh](https://roadmap.sh/projects/weather-api-wrapper-service).  

---