# Weather App 🌦️

This is a simple weather monitoring application built using **React.js** and powered by the **OpenWeather API**. The app provides real-time weather updates based on the user's location, offering a smooth user experience with clean UI.

## Live Demo

Check out the deployed app here: [Weather App](https://vardhan077.github.io/weatherApp/)

## Features

- Displays real-time weather information for your current location.
- Utilizes the **OpenWeather API** to fetch data such as temperature, humidity, wind speed, etc.
- Clean and responsive user interface.
- Offers location-based weather details for enhanced interactivity.

## Tech Stack

- **React.js**: Frontend framework used to build the user interface.
- **OpenWeather API**: Provides weather data for various locations.
- **HTML5/CSS3**: Used for structuring and styling the app.
- **JavaScript (ES6+)**: Used for logic and API integration.

## How to Run Locally

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/vardhan077/weatherApp.git
    cd weatherApp
    ```

2. **Install dependencies**:
    Make sure you have Node.js installed. Then run:
    ```bash
    npm install
    ```

3. **Get OpenWeather API Key**:
    - Go to [OpenWeather](https://openweathermap.org/api) and sign up to get your free API key.
    - Create a `.env` file in the root directory of the project and add your API key:
      ```bash
      REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
      ```

4. **Start the app**:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to view the app.

## Future Improvements

- Add support for searching weather by city.
- Display 7-day forecast.
- Improve UI with animated weather icons.

## Contributing

Feel free to submit a pull request or open an issue if you would like to contribute to the project!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
