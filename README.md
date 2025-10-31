# 🌤️ SkyInsight – Weather Forecast App

![HTML](https://img.shields.io/badge/Frontend-HTML-orange)
![CSS](https://img.shields.io/badge/Styling-CSS-blue)
![JavaScript](https://img.shields.io/badge/Logic-JavaScript-yellow)
![API](https://img.shields.io/badge/API-OpenWeatherMap-lightblue)

**SkyInsight** is an interactive web application that provides real-time weather updates for your current location or any city you search for.  
It leverages the **OpenWeatherMap API** and **Geolocation API** to deliver accurate weather information in a clean, user-friendly interface.

---

##  Features

-  **Your Weather:** Automatically fetches weather data based on your current location using the Geolocation API.  
-  **Search Weather:** Search for any city and get its real-time weather information.  
-  **Temperature Display:** Shows the temperature in Celsius.  
-  **Wind Speed:** Displays wind speed in meters per second.  
-  **Humidity:** Shows the humidity percentage.  
-  **Cloudiness:** Displays cloud coverage in percentage.  
-  **Country Flag:** Displays the national flag of the city’s country.  
-  **Interactive UI:** Smooth transitions between user location and search modes.

---

##  Color-Coded UI

- **Tabs:** Switch between "Your Weather" and "Search Weather".  
- **Loading Animation:** Displays a loading screen while fetching data.  
- **Cards:** Key parameters like wind speed, humidity, and clouds are highlighted in separate cards.  
- **Responsive Layout:** Works on both mobile and desktop screens.

---

##  How It Works

1. **Grant Location Access:**  
   Users can allow access to their location to fetch local weather data automatically.  

2. **Search for City:**  
   Users can type a city name in the search tab and get weather updates for that location.  

3. **API Calls:**  
   - User location → OpenWeatherMap API → Weather data  
   - City search → OpenWeatherMap API → Weather data  

4. **Display:**  
   Weather information is displayed, including:  
   - City Name & Country Flag  
   - Weather Description & Icon  
   - Temperature  
   - Wind Speed, Humidity, Cloudiness  

---

##  Project Structure

SkyInsight/
├── index.html # Main HTML page
├── style.css # Styling for the app
├── script.js # JavaScript functionality
├── images/ # Icons & images (location, wind, cloud, humidity, search, loading)
└── README.md # Project documentation

---

## Future Enhancements

 - Forecast: Add 7-day or hourly weather forecast.
 - Dark Mode: Theme toggle based on time of day.
 - Map Integration: Show city on a map using Leaflet or Google Maps API.
 - Unit Conversion: Toggle between Celsius and Fahrenheit.
 - Weather Alerts: Notify users about severe weather conditions.

---

 👩‍💻 Author

Sonam Ravindra Kadam

