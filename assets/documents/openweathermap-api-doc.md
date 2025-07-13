# OpenWeatherMap API Documentation

The OpenWeatherMap API provides access to current weather data, forecasts, and historical weather.

## Base URL

https://api.openweathermap.org/data/2.5/


## Example Request

GET https://api.openweathermap.org/data/2.5/weather?q=Toronto&appid=YOUR_API_KEY&units=metric


## Response
```json
{
  "weather": [{"main": "Clouds"}],
  "main": { "temp": 22.5 }
}

