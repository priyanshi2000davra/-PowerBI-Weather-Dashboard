# PowerBI-Weather-Dashboard
This project presents an interactive Power BI dashboard that visualizes real-time weather and air quality data using the WeatherAPI.com service. It provides insights into temperature, humidity, AQI, and forecasts for multiple cities in an intuitive and visually appealing format.

Example Data: London & Indore

Temperature: 17.2°C
Condition: Mist
Humidity: 77%
Pressure: 30.00
Wind Speed: 4.30 km/h
Visibility: 2.5 km
Air Quality Index (PM10): 495


Project Overview
Tool Used: Microsoft Power BI
Data Source: Live WeatherAPI.com REST endpoint
Objective: To analyze and visualize daily and forecasted weather data for selected cities, including air quality indicators.
Data Source: WeatherAPI Integration
The Power BI dashboard fetches live weather data from WeatherAPI.com using a REST API connection integrated directly into Power BI through Power Query.

API Endpoint Used (secured): = Json.Document(Web.Contents( "http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=London&days=7&aqi=yes&alerts=no") )
