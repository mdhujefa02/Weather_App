# Weather_App

# Project Overview

The Weather App is a dynamic web application designed to provide users with real-time weather updates for any city. With an interactive and user-friendly interface, users can easily access information such as temperature, humidity, wind speed, and a brief weather description.

# Features

City-Based Weather Search: Enter any city name to get instant weather details.
Real-Time Updates: Fetches live weather data using OpenWeatherMap's API.
User-Friendly Interface: Clean and responsive design for a seamless user experience.
Detailed Weather Information: Displays temperature, humidity, wind speed, and weather description.

# Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: JSP (Java Server Pages), Servlets
API:OpenWeatherMap

# Navigate to the project directory:

cd weather-app
Set up a local server (using tools like Apache Tomcat).
Deploy the application by placing it in the Tomcat webapps folder.
Start the Tomcat server and access the app at:
http://localhost:8080/weather-app
Configuration

# API Key Setup:

Obtain an API key from OpenWeatherMap.
Replace the API key placeholder in the servlet file:
String apiKey = "724926a80faa659c845c6d2246287299";

Usage

Enter the name of any city in the search bar.
Click on the search button.
View the weather details, including temperature, humidity, wind speed, and weather description.

# Project Structure

weather-app/
|-- index.html
|-- styles/
|   |-- styles.css
|-- scripts/
|   |-- main.js
|-- WEB-INF/
|   |-- web.xml
|   |-- classes/
|       |-- WeatherServlet.class

# Roles and Responsibilities

Frontend Development: Created a responsive and interactive user interface using HTML and CSS.
Backend Development: Handled API requests and responses using JSP and Servlets.
API Integration: Integrated OpenWeatherMap API to fetch real-time weather data.

# Thank you for visiting the project. Happy coding!
