# Weather App

A simple weather application that allows users to search for a city and view the current weather conditions, including temperature, weather type, and high/low temperatures.

## Live Demo

Check out the live demo of the application [here](https://1-weathr-app.vercel.app/).

## Project Structure

- **`index.html:`** The main structure of the Weather App.
- **`style.css:`** Contains the styles and layout for the application.
- **`index.js:`** Handles fetching weather data from the OpenWeatherMap API and updating the UI.

## Usage

1. Clone the repository or download the files.
2. Open the `index.html` file in your web browser to run the application.
3. Enter the name of a city in the search box and press Enter to fetch and display the weather details.

## Screenshots

### Main Interface
![Main Interface](screenshot.png)

## How It Works

### Searching for a City
- Enter the city name in the search box and press Enter.
- The app will fetch weather data for the city from the OpenWeatherMap API.

### Displaying Weather Data
- The current temperature, weather condition (e.g., Sunny, Rainy), and high/low temperatures are displayed for the city.
- The date and city location are also shown.

## Code Explanation

### API Integration
- **API Key:** The app uses the OpenWeatherMap API with a key stored in the `api` object.
- **Fetching Data:** When a user enters a city name, the `getResults` function fetches weather data from the API.
- **Displaying Data:** The `displayResults` function updates the UI with the fetched weather data.

### Date Handling
- The `dateBuilder` function formats and displays the current date based on the user's system date.



