# Weather App

A simple and intuitive weather application that fetches current weather data using the Rapid API.

## Features

- Displays current weather conditions including temperature, humidity, wind speed, and more.
- Supports multiple locations.
- User-friendly interface with responsive design.
- Error handling for API requests.

## Screenshots

![Home Screen](screenshots/screenshot1.png)
![Weather Details](screenshots/screenshot2.png)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Rapid API account

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory
   ```bash
   cd weather-app
   ```
3. Install dependencies
   ```bash
   npm install
   ```

### Configuration

1. Sign up on [Rapid API](https://rapidapi.com) and subscribe to a weather API (e.g., OpenWeatherMap, WeatherAPI).
2. Obtain your API key from Rapid API.
3. Create a `.env` file in the root of the project and add your API key:
   ```plaintext
   REACT_APP_RAPIDAPI_KEY=your_api_key_here
   ```

2. Open your browser and navigate to `http://localhost:3000`

Follow the prompts to complete the deployment process.

## Built With

- [Rapid API](https://rapidapi.com/) - API marketplace for accessing weather data

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Weather by API- Ninjas](https://rapidapi.com/apininjas/api/weather-by-api-ninjas/) for the weather data API
- [Rapid API](https://rapidapi.com/) for providing the API marketplace
