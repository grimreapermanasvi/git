# # QuickWeather App

This is a command line application developed in Python that provides weather forecasting information using the OpenWeather API. The app allows users to enter a location and retrieve weather data such as sky type, temperature, sunset and sunrise time, and wind speed in the specified area.

## Features
- Retrieve weather data based on the user's specified location.
- Display the sky type (e.g., cloudy, sunny, rainy), temperature, humidity, pressure, and wind speed.
- Convert temperature from Kelvin to Celsius for a better user experience.
- Display the sunrise and sunset times in a readable format.
- Handle exceptions and provide informative error messages for a smooth user experience.

## Dependencies
- Python 3.7+
- `requests` library: Used for making API requests to OpenWeather API.

## Setup and Usage
1. Clone the repository or download the source code files to your local machine.
2. Obtain an API key from the OpenWeather website by signing up for a free account.
3. Replace the placeholder `YOUR_API_KEY` in the code with your actual API key.
4. Open a terminal or command prompt and navigate to the project directory.
5. Run the following command to install the `requests` library if not already installed:
   ```
   pip install requests
   ```
6. Execute the app by running the following command:
   ```
   python weather_app.py
   ```
7. Follow the prompts and enter the location for which you want to retrieve weather information.

## GitHub Copilot Integration
GitHub Copilot, an AI-powered coding assistant, was used during the development of this application. It provided helpful suggestions, such as modularizing code into functions, error handling, and generating informative error messages.

The suggestions from GitHub Copilot improved code readability and reduced the complexity of the main function. Copilot's assistance helped in enhancing the overall user experience of the app.

## Notes
- The weather data is fetched from the OpenWeather API, which requires an active internet connection.
- The API key is necessary to make requests to the OpenWeather API. Ensure that you have a valid API key and replace the placeholder `YOUR_API_KEY` in the code.
- The app displays temperature in Celsius and other units based on the API response.
- In case of any issues or exceptions during the API request, the app will display an informative error message.

Feel free to explore and enhance the app according to your needs. Contributions and feedback are always welcome!

Enjoy using the Weather Forecasting Command Line App!
