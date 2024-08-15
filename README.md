# Weather-Dashboard-Application

## Overview
The Weather Dashboard Application is a simple web app that allows users to check the current weather conditions for any city worldwide. The app retrieves weather data using the OpenWeatherMap API and displays key information, including temperature, humidity, wind speed, and weather conditions with dynamic icons and background colors based on the weather.

## Features
- **City Search:** Users can enter the name of any city to get the latest weather information.
- **Temperature Units:** Toggle between Celsius (°C) and Fahrenheit (°F) using a switch.
- **Dynamic Background:** The background color changes based on the weather condition (e.g., sunny, cloudy, rainy).
- **Weather Icons:** Visual representation of the weather conditions with FontAwesome icons.

## Files
- **index.html:** The main HTML file containing the structure of the web app.
- **style.css:** The CSS file for styling the web app, including layout, buttons, and dynamic background changes.
- **script.js:** The JavaScript file that handles fetching data from the OpenWeatherMap API, displaying weather information, and handling unit toggles.

## Usage
1. **Enter City Name:** Type the name of a city in the input field.
2. **Get Weather:** Click the "Get Weather" button to retrieve the latest weather data.
3. **Toggle Units:** Use the switch to toggle between Celsius and Fahrenheit.
4. **View Weather Info:** The app will display the temperature, humidity, wind speed, and an icon representing the weather condition.

## API Key
Replace the placeholder API key in the `script.js` file with your own OpenWeatherMap API key:
```javascript
const apiKey = 'YOUR_API_KEY_HERE';
```

## Installation
To use this application, simply download all the files and open `index.html` in your web browser.

## Credits
- **OpenWeatherMap API:** Used for fetching real-time weather data.
- **FontAwesome:** Provides weather icons for the application.

## License
This project is open-source and free to use.

Enjoy the Weather Dashboard Application!
