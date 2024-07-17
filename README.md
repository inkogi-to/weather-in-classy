# Classy Weather

Classy Weather is a React-based weather forecasting application that fetches weather data for a specified location. The app uses the Open-Meteo API to provide accurate weather forecasts.

## Features

- Search for weather information by location.
- Displays weather icons based on WMO codes.
- Shows maximum and minimum temperatures for the next few days.
- Uses local storage to remember the last searched location.
- Loading indicator while fetching data.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js and npm installed on your machine. If you don't have them installed, you can download and install them from [here](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/classy-weather.git
   ```

2. Navigate to the project directory:

   ```bash
   cd classy-weather
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

   The app should now be running on `http://localhost:3000`.

## Usage

1. Enter a location in the search input field.
2. Click on the "Get weather" button to fetch the weather data for the entered location.
3. The weather forecast, including weather icons and temperature ranges, will be displayed for the next few days.

## Code Structure

- `src/App.js`: Main component that handles the state and logic for fetching and displaying weather data.
- `src/Input.js`: Input component for entering the location.
- `src/Weather.js`: Component for displaying the weather information.
- `src/Day.js`: Component for displaying individual day's weather details.
- `src/utils.js`: Utility functions for converting country codes to flags and formatting dates.

## API Reference

The application uses the [Open-Meteo API](https://open-meteo.com/) for fetching weather data and the [Geocoding API](https://open-meteo.com/en/docs#api-formats) for converting location names to coordinates.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Open-Meteo](https://open-meteo.com/) for providing the weather and geocoding APIs.
- Emoji icons used for weather representation.
