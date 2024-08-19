# Weather App

This is a simple Weather Application that allows users to search for the weather in a specific city. It fetches real-time weather data using the OpenWeatherMap API and displays the temperature, humidity, wind speed, and an appropriate weather icon.

## Features

- Search for weather by city name
- Displays real-time temperature, humidity, and wind speed
- Shows weather icon based on the current weather conditions (Clear, Clouds, Rain, Drizzle, Mist)
- Error handling for invalid city names

## Technologies Used

- **HTML5** for the structure of the app
- **CSS3** for styling the UI components
- **JavaScript (ES6)** for dynamic data fetching and display
- **OpenWeatherMap API** for fetching real-time weather data

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/KUMAR-AKASH-ER/weather-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd weather-app
    ```

3. Open `index.html` in your web browser to run the app locally:
    ```bash
    open index.html
    ```

4. Search for any city and view the weather data.

## OpenWeatherMap API Key

This project uses the OpenWeatherMap API to fetch weather data. You need to replace the existing API key with your own.

1. Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up to get an API key.
2. Replace the value of the `apiKey` variable in the `index.html` file:

    ```js
    const apiKey = "4bf07c5755fef2959e3eea43185c8657";
    ```

## Project Structure

```
├── index.html # Main HTML file
├── style.css # CSS file for styling
├── script.js # JavaScript file (included inline in the HTML for simplicity)
├── images/ # Folder for weather-related icons (e.g., rain, clouds, humidity)
└── README.md # Documentation file (you are reading this now)
```
## UI Components

- **Search Box:** Users can enter the city name to fetch the weather.
- **Error Message:** Displays "Invalid city name" if the city is not found.
- **Weather Info:** Displays the temperature, city name, humidity, wind speed, and a weather icon based on conditions.

## Screenshots

![Weather App Screenshot](https://github.com/KUMAR-AKASH-ER/practice_projects/blob/675d1a371196dd4c6ac11e953a35e01ee12221b0/HTML_CSS_JAVASCRIPT/Weather%20App/screenshots/search-bar.png)
![Weather App Screenshot](https://github.com/KUMAR-AKASH-ER/practice_projects/blob/675d1a371196dd4c6ac11e953a35e01ee12221b0/HTML_CSS_JAVASCRIPT/Weather%20App/screenshots/searched-result.png)
![Weather App Screenshot](https://github.com/KUMAR-AKASH-ER/practice_projects/blob/675d1a371196dd4c6ac11e953a35e01ee12221b0/HTML_CSS_JAVASCRIPT/Weather%20App/screenshots/invalid-search.png)

## Future Improvements

- Add autocomplete suggestions for city names.
- Include weather forecasts for multiple days.
- Improve the mobile responsiveness of the app.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

