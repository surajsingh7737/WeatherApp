# Weather App 🌤️

A simple weather app built with HTML, CSS, and JavaScript. Type a city name and see the live weather for that city.

![Weather App Screenshot](images/screenshot.png)

**Live demo:** [add your link here]

## Features

- Search the weather for any city in the world
- Shows the current temperature, humidity, and wind speed
- Weather icon changes with the condition: clear, clouds, rain, drizzle, or mist
- Shows a clear message when the city name is invalid
- Clean gradient card design

## Built With

- **HTML5** for the structure
- **CSS3** for the layout and styling
- **JavaScript (ES6)** with `fetch` and `async/await`
- **[OpenWeatherMap API](https://openweathermap.org/api)** for the weather data

## Project Structure

```
Weather App/
├── images/        # Weather icons and other images
├── index.html     # Page structure
├── style.css      # Styling
└── app.js         # API call and app logic
```

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Get a free API key

1. Create a free account at [openweathermap.org](https://openweathermap.org/api).
2. Open the **API keys** tab in your account and copy your key.
3. New keys can take a few minutes to start working.

### 3. Add your key

Open `app.js` and replace the value on the first line:

```javascript
const apiKey = "YOUR_API_KEY";
```

> **Note:** Do not share your personal API key in a public repository. Anyone who finds it can use your quota.

### 4. Run the app

Open `index.html` in your browser. You can also use the **Live Server** extension in VS Code.

## How It Works

1. You enter a city name and click the search button.
2. `app.js` sends a request to the OpenWeatherMap API.
3. The API returns the weather data as JSON.
4. The app updates the city, temperature, humidity, wind speed, and icon on the page.
5. If the city is not found (HTTP status 404), the app shows an error message.

## Future Improvements

- [ ] 5-day forecast
- [ ] Dark mode
- [ ] Search by current location
- [ ] Switch between °C and °F
- [ ] More weather conditions, such as snow and thunderstorm
- [ ] Weather animations

## Author

Built by [@surajsingh7737](https://github.com/surajsingh7737)

If you like this project, please give it a ⭐ on GitHub.
