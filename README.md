
# Weather App ☁️🌞

This is a simple **Weather App** that provides real-time weather information based on the city name entered. It fetches weather data using the **OpenWeather API** and displays the current temperature, humidity, wind speed, and weather condition.

## Features
- 🌡️ Displays current temperature in Celsius.
- 💧 Shows humidity percentage.
- 🌬️ Provides wind speed in km/h.
- 🌍 Displays real-time weather data for any city.
- 🖼️ Weather icons change dynamically based on weather conditions (e.g., clear, rain, clouds, mist).

## Tech Stack
- **HTML**: Structure of the application.
- **CSS**: For styling the weather card and layout.
- **JavaScript**: Fetches weather data from the OpenWeather API and dynamically updates the DOM.
- **OpenWeather API**: Used for retrieving real-time weather data.


## How to Run Locally

Follow these steps to run the project on your local machine:

### Prerequisites
- A code editor like **VSCode**.
- A basic understanding of **HTML**, **CSS**, and **JavaScript**.
- **Node.js** (optional) for running a local server.

### Installation
1. **Clone the repository** to your local machine using Git:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```

2. **Navigate** into the project directory:
   ```bash
   cd weather-app
   ```

3. **Open the `index.html` file** in your browser:
   You can either double-click the `index.html` file or use a live server extension in VSCode (if you're using it).

4. **Add your API Key**:
   - Sign up for a free API key from [OpenWeather](https://openweathermap.org/api).
   - Replace the `apiKey` value in the script section of `index.html` with your API key:
     ```javascript
     const apiKey = 'YOUR_API_KEY';
     ```

### Usage
1. Open the app in your browser.
2. Enter the name of a city in the search box.
3. Click the **search button** to retrieve the current weather for that city.
4. If the city name is invalid, the app will display an error message.

## Project Structure

```bash
weather-app/
│
├── images/                     # Weather icons and images
├── style.css                   # CSS for styling the app
├── index.html                  # Main HTML file
└── README.md                   # This README file
```

## API Information
- The project uses the **OpenWeather API** for fetching weather data.
- The API documentation can be found [here](https://openweathermap.org/api).

## Contributing
Contributions are welcome! Here's how you can contribute:
1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, feel free to contact me at [your-email@example.com](mailto:your-email@example.com).
```

### Steps to Customize:
1. Replace `https://github.com/yourusername/weather-app.git` with the actual URL of your GitHub repository.
2. Add a **Live Demo** link if you deploy the app (e.g., using Netlify or Vercel).
3. Include screenshots of your app in the **Screenshots** section (upload them to GitHub and use the image URL).

This should give your project a professional-looking README, which provides clear instructions for anyone viewing your repository on GitHub!
