# SkySphere - Weather App

## Overview
SkySphere is a simple and stylish weather application that allows users to enter a location and view the current temperature and weather conditions. The app fetches real-time weather data using the WeatherAPI and displays weather icons along with a dynamic background.

## Features
- User-friendly interface with a modern design.
- Fetches real-time weather data based on user input.
- Displays temperature, weather conditions, and weather icons.
- Background dynamically changes with weather-themed imagery.

## Technologies Used
- **HTML** - For structuring the web page.
- **CSS** - For styling and effects.
- **JavaScript** - For fetching weather data and handling user interactions.
- **WeatherAPI** - Provides real-time weather data.

## How to Use
1. Open the `index.html` file in a web browser.
2. Enter a location (city or town) in the input field.
3. Click the "Get Weather" button.
4. View the temperature, weather condition, and a corresponding weather icon.

## API Used
- **WeatherAPI**: [WeatherAPI](https://www.weatherapi.com/) is used to fetch real-time weather data.
- Example API Call:
  ```
  http://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=London&aqi=yes
  ```

## Project Setup
1. Clone this repository.
2. Open the `index.html` file in any modern web browser.
3. Ensure you have a valid API key from WeatherAPI and update it in the JavaScript code.

## Future Enhancements
- Add forecast functionality for upcoming days.
- Implement geolocation to fetch the user's current weather automatically.
- Improve UI with animated weather effects.

## License
This project is open-source and available for personal or educational use.
