# WeatherApp #

This Weather Web App is a simple and elegant application that fetches real-time weather data for the user's location using OpenWeatherMap API. It displays temperature (in C and F), weather descriptions, sunrise and sunset times.

## Features

  * Retrieves weather information based on the user's geolocation
  * Displays temperature in both Celsius and Fahrenheit
  * Shows weather description and corresponding icon
  * Provides sunrise and sunset times
  * Simple and responsive UI with clean design

## Technologies used

  * **HTML5:** Structure of the web app
  * **CSS3:** Styling and layout
  * **JavaScript:** Fetching and displaying weather data
  * **OpenWeatherMAp API:** Provides real-time weather data

## API setup

  1. Sign up at OpenWeatherMap and obtain an API key
  2. Replace ```YOUR API KEY``` in ```script.js``` with your actual API key:
     ```JavaScript
     const api = 'YOUR API KEY';
     ```

## How it works

  1. The app requests the user's geolocation
  2. It fetches weather data from the OpenWeatherMap API based on the user's coordinates
  3. The retrieved data is displayed on the UI, including temperature, weather description, sunrise and sunset times

## Notes

  * Ensure location services are enabled in your browser for accurate weather data
  * The API key must be a valid one
  * All you have to do is refresh the page, give the app your permission to access the geolocation and it is live.
