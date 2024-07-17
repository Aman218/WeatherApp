# Weather Forecast Application

This application is fetching data from API , then displaying it in a pretty fashion on user Interface. In this project i did make use of HTML,CSS and JS.

## Features

- Fetching the current temperature data,humidity,windSpeed.

- Also fetching the weather forecast for 5 days with consecutive dates.

- Weather can be fetched using user's current location.

## File Structure

- 'index.html': Contains the structure of the web page.
- 'style.css' : Contains the style for the web page.
- 'index.js' : Contains the javascript code for getting weather details based on user's input or user's current location.


## API KEY
- To access the OpenWeatherMap API, you need an API key. In this application, the key is stored in the variable apikey.
 
## Local Storage

- The application uses the browser's local storage to maintain a list of recently searched cities. The list is limited to 5 cities to avoid clutter.

## Core functions
- getweather(city): Fetches weather data for a given city using the OpenWeatherMap API.
- getweatherByCoordinates(lat, lon): Fetches weather data for given geographical coordinates.
- updateWeather(result, cityName): Updates the HTML elements with the fetched weather data.
- addCityToRecent(city): Adds a city to the recent cities list and updates the dropdown.
- updateRecentCitiesDropdown(): Updates the recent cities dropdown with the stored recent cities.

## Initialization

- On page load, the weather data for "Kota" is fetched and displayed.
- The recent cities dropdown is updated with the stored recent cities.

## Dependencies
- OpenWeatherMap API: Used to fetch weather data


## Link of the github

- PLease find the github link here-> https://github.com/Aman218/WeatherApp

## Link of my hosted Weather App

 - https://aman218.github.io/WeatherApp/

## Author

- Aman Singh