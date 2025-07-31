# Weather App

A sleek and responsive Weather App that provides real-time weather updates for cities around the world. Built with **React**, **Vite**, and **Tailwind CSS**, it fetches data from the **OpenWeatherMap API** to display current temperature, humidity, wind conditions, sunrise/sunset times, and more.

## 🔗 Live Demo

[View Demo](#) *(optional — add link if deployed)*

---

## Preview

![Weather App Screenshot](./screenshot.png) *(optional — add a screenshot of your app UI)*

---

## Features

- Search any city/country to get real-time weather data
- Shows temperature, humidity, wind speed, visibility, and pressure
- Sunrise and  Sunset timings
- Dynamic background based on weather and time of day
- Autocomplete suggestions for city names
- Temperature toggle: Celsius ↔ Fahrenheit

---

## Tech Stack

- **React.js** – UI library
- **Vite** – Development server and build tool
- **Tailwind CSS** – Styling
- 🌐 **OpenWeatherMap API** – Weather data provider

---

##  Project Structure

```bash
weather-app/
├── public/
│   └── index.html
├── src/
│   ├── assets/            # Background GIFs, icons
│   ├── components/        # WeatherBackground, Icons, Helpers
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env                  # Environment file (not committed)
├── .gitignore
└── README.md
