# Geo City Weather Dashboard

The **Geo City Weather Dashboard** is a web-based application that provides users with a 5-day weather forecast for cities of their choice. It dynamically updates the HTML and CSS based on the selected location's weather conditions and stores previous city searches locally for easy access. The app uses the **OpenWeatherMap** API to retrieve real-time weather data.

## Features

- **Dynamic Weather Display**: Fetches and displays weather data, including temperature, humidity, wind speed, and conditions.
- **Search by City**: Users can search for any city and retrieve a 5-day weather forecast.
- **LocalStorage Integration**: Previously searched cities are saved locally and displayed for quick access.
- **Latitude & Longitude**: Retrieves forecast data using latitude and longitude coordinates for accurate location-based results.

## API Integration

This project uses the [OpenWeatherMap 5 Day Weather Forecast API](https://openweathermap.org/forecast5) to get weather data for cities. The API is accessed via the following endpoint:

```
https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API key}
```

Replace `{lat}`, `{lon}`, and `{API key}` with the appropriate values to retrieve weather data for the desired location.

## User Interface

The following is a screenshot of the weather dashboard, showcasing the 5-day forecast and the list of cities retrieved from **LocalStorage**:

![Weather Dashboard](./assets/images/displayTemp.png)

## Live Demo

You can try the application here:

[**City Weather Dashboard**](https://amandeepsandhu13.github.io/geo-city-weather/)

## Repository

You can find the source code in the GitHub repository:

[**City Weather Repository**](https://github.com/MrGithubby/Weather-Tracker)