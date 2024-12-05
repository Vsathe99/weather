
# Weather Forcast 

A brief description of what this project does and who it's for




## Features

- City-based Weather Search: Get weather details by entering a city name.
- Clean Data Presentation: Displays temperature, humidity, and a forecast in an easy-to-read UI.
- Error Handling: Handles invalid inputs, API failures, and rate limits gracefully.



## Getting Started
### Prerequisites

- Node.js and npm installed on your system.
- An OpenWeather API key. Sign up for a free account [here](https://openweathermap.org/api) to get your API key.

### Setup Instructions

1. Clone this repository

```bash
  git clone https://github.com/your-username/weather-dashboard.git
  cd weather-dashboard
```

2. Install dependencies

```bash
  npm install

```
3. Setup your API Key:
- Create a .env file in the root directory.
- Add the following line, replacing YOUR_API_KEY with your OpenWeather API key.
```bash
  REACT_APP_OPENWEATHER_API_KEY=YOUR_API_KEY


```
4. Start the application:
```bash
  npm start

```
## How It Works

- Enter the name of a city in the input field.
- View the current temperature, weather description, and humidity.

## Challenges and Resolutions
- API Rate Limits: Implemented efficient error handling to manage exceeded limits.
- Data Transformation: Parsed complex API responses into a simplified structure for easier UI rendering.
## Demo

![image](https://github.com/user-attachments/assets/e91b2d48-3a1f-48e1-84b7-09ae586d988c)


