# Weather App

A simple weather application built using HTML, CSS, and JavaScript. It uses the OpenWeather API to display current weather information for a searched city.

## Features

- Search for a city using the search button or the Enter key
- Display current temperature
- Display feels-like temperature
- Display humidity
- Display wind speed
- Display weather condition and icon
- Display country and city
- Show an error for invalid city names
- Display the time when the weather data was last updated
- Responsive design

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API

## API

This project uses the OpenWeather API to retrieve current weather data.

API source:
https://openweathermap.org/api

## Sample API Response

Example response received from the OpenWeather API:

```json
{
  "name": "Tyre",
  "main": {
    "temp": 26,
    "feels_like": 26,
    "humidity": 65
  },
  "weather": [
    {
      "main": "Clear",
      "description": "clear sky"
    }
  ],
  "wind": {
    "speed": 3.5
  },
  "sys": {
    "country": "LB"
  }
}

## Screenshots

### Start Screen
![Weather App Start Screen](<Screenshot%202026-09-29%20133328.png>)

### Weather Result - Tyr
![Weather App - Tyr](<Screenshot%202026-09-29%20133355.png>)

### Invalid City
![Invalid City](<Screenshot%202026-09-29%20133415.png>)
