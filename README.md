# Weather Now

Weather Now is a web application that provides real-time weather information and a 4-day weather forecast for any city. The app is built using HTML, CSS, and JavaScript, and leverages the WeatherAPI to fetch weather data.

## Features

- **Current Weather Information**: Displays the current temperature, weather condition, humidity, cloud cover, and wind speed.
- **4-Day Weather Forecast**: Shows the weather forecast for the next 4 days, including the date, condition, and temperature range.
- **City Search**: Allows users to search for weather information by entering a city name.
- **Predefined Cities**: Quick access to weather information for popular cities via clickable buttons.

## Technologies Used

- **HTML**: Structure of the web application.
- **CSS**: Styling and layout of the web application.
- **JavaScript**: Fetching weather data from the WeatherAPI and updating the UI dynamically.

## How to Use

1. **Search for a City**:
   - Enter the name of the city in the search bar and click the "Submit" button.
   - The app will fetch and display the current weather and 4-day forecast for the entered city.

2. **Predefined Cities**:
   - Click on any of the predefined city buttons (e.g., London, New York, Tokyo) to quickly view the weather information for that city.

## API Used

- **WeatherAPI**: Provides current weather data and forecasts. You can get your API key by signing up at [WeatherAPI](https://www.weatherapi.com/).

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/weather-now.git
   cd weather-now
   ```

2. **Open the Project**:
   - Open the `index.html` file in your web browser to view the app.

3. **Modify the API Key**:
   - Open the `script.js` file.
   - Replace `YOUR_API_KEY` with your actual WeatherAPI key.
   ```javascript
   const apiKey = 'YOUR_API_KEY';
   ```

## Project Structure

```
weather-now/
│
├── index.html        # Main HTML file
├── styles.css        # CSS for styling
├── script.js         # JavaScript for fetching and displaying weather data
└── README.md         # Project documentation
```