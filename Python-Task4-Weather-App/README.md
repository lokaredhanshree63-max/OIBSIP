# Basic Weather App

## Objective
The objective of this project is to create a Basic Weather App using Python that fetches and displays current weather information for a given city using the OpenWeatherMap API.

## Features
- Accepts city name from the user.
- Fetches real-time weather information.
- Displays temperature in Celsius and Fahrenheit.
- Displays humidity percentage.
- Displays current weather condition.
- Displays wind speed.
- Handles invalid API key errors.
- Handles city not found errors.
- Handles network connection and timeout errors.
- Rejects empty city input.

## Technologies Used
- Python
- Jupyter Notebook
- Requests Library
- OpenWeatherMap API
- JSON

## How It Works
1. The user enters the OpenWeatherMap API key.
2. The user enters a city name.
3. The application sends a request to the OpenWeatherMap API.
4. The API returns the current weather data in JSON format.
5. The program extracts the required weather details.
6. The weather information is displayed to the user.

## Weather Information Displayed
- City Name
- Temperature in °C
- Temperature in °F
- Humidity
- Weather Condition
- Wind Speed

## Example

### Input
- City: Pune

### Output
The application displays the current temperature, humidity, weather condition, and wind speed for the selected city.

## Error Handling
The application handles:
- Empty city name
- Invalid API key
- City not found
- Network connection problems
- Request timeout

## Conclusion
This project demonstrates the use of Python, API integration, JSON data handling, user input, exception handling, and the Requests library to build a simple weather application.