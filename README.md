# WeatherMelon

This is a simple React application that allows users to search for and view the current weather information for any city. The application fetches data from the OpenWeatherMap API and displays it, including temperature, humidity, wind speed, and weather condition icons.

## Features

- **Search Functionality**: Users can search for the weather in any city by entering the city name.
- **Current Weather Display**: Displays the current temperature, humidity, wind speed, and an appropriate weather icon.
- **Default Weather Display**: On initial load, the app displays the weather for a default city (Abuja).


## Components

- **Weather.js**: The main component that contains the logic for fetching and displaying weather data.
- **Weather.css**: Contains the styling for the Weather component.

## API Integration

The application integrates with the OpenWeatherMap API to fetch real-time weather data. Ensure you have a valid API key and have set it in the `.env` file as shown above.

## Icon Mapping

The app includes a set of weather icons that correspond to different weather conditions. The icons are mapped based on the weather codes returned by the OpenWeatherMap API.

## Environment Variables

- **VITE_APP_ID**: Your OpenWeatherMap API key.

## Dependencies

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast build tool for modern web projects.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

