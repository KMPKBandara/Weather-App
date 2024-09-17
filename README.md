# Weather App

A simple weather app that displays current weather conditions for a city entered by the user. This app uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch real-time weather data and dynamically updates the weather information and background image based on the conditions.

## Features
- Search for weather by city.
- Displays the following weather details:
  - Temperature
  - Weather condition (e.g., sunny, cloudy, rainy)
  - Humidity
  - Wind speed
- Changes the image based on the weather condition.
  
## Technologies Used
- HTML for the structure of the webpage.
- CSS for styling the app and making it responsive.
- JavaScript for handling the logic, fetching data from the API, and updating the UI.
- OpenWeatherMap API for retrieving weather data.

## How to Use
1. Enter the name of the city in the search box.
2. The app will display the weather details such as temperature, weather condition, humidity, and wind speed for the entered city.
3. The picture will change according to the current weather condition.

## API Key Setup
1. Sign up on [OpenWeatherMap](https://openweathermap.org/) and generate an API key.
2. In the JavaScript code, replace the placeholder with your API key:

```javascript
const apiKey = 'YOUR_API_KEY_HERE';
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KMPKBandara/Weather-App.git
   ```

2. Open the `index.html` file in your browser to run the app.

## Project Structure
```bash
Weather-App/
├── index.html
├── style.css
├── script.js
└── README.md
```
