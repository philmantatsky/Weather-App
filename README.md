# Weather App 🌤️

A clean, responsive **React.js** weather website that lets users search any city in the world and instantly see real-time conditions — temperature, humidity, and wind speed — pulled live from the **OpenWeather API**.

![React](https://img.shields.io/badge/React-18.0+-61DAFB.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![API](https://img.shields.io/badge/API-OpenWeather-orange.svg)

---

## ✨ Features

- **Live city search** — type any city in the world and instantly fetch its current weather
- **Real-time data** — temperature, humidity, and wind speed pulled directly from the OpenWeather API
- **Clean, responsive UI** — built with React components that work on desktop and mobile
- **Default city display** — showcases conditions for several major cities right when the page loads
- **Fast and lightweight** — no unnecessary dependencies, just React and a clean fetch call

---

## 🛠️ How It Works

1. The user types a city name into the search bar
2. The app sends a request to the **OpenWeather API** with the city as a query parameter
3. The API response (JSON) is parsed and the relevant fields — temperature, humidity, wind — are pulled out
4. React updates the UI in real time with the new data

State is managed with React hooks (`useState`, `useEffect`), and API calls are handled with the native `fetch` function.

---

## 🚀 Getting Started

### Requirements
- Node.js 16+
- npm or yarn
- A free OpenWeather API key ([get one here](https://openweathermap.org/api))

### Setup

```bash
git clone https://github.com/philmantatsky/weather-app.git
cd weather-app
npm install
```

### Add your API key

Create a `.env` file in the project root:
