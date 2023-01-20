# Weather API - Laravel Developer Test Task

We will use [**Open Weather API**](https://openweathermap.org/current) to get current weather data based on latitude/longitude.

- **API Link**: [https://openweathermap.org/current](https://openweathermap.org/current)
- **API Key**: `1077481787381398496a922389d0eea2` 
- **Technology: Laravel, MySQL, Redis**

---

# Task

Create a project, that will pull the weather information of **ALL** cities of Uzbekistan and will store it in the database every hour.

# Rest API Endpoints

- Store the data about cities in the database 
- Get the list of the stored weather information
- Ability to filter the weather information by city name (exact match)

# Data

## Columns that should be stored about city

- City name
- Latitude
- Longitude

## Columns that should be stored about weather information in the table:

- Time
- Weather name
- Latitude
- Longitude
- Temperature (in Celsius)
- Pressure
- Humidity
- MIN Temperature
- MAX Temperature

# Example Cities

| Name    | Latitude | Longitude |
|---------|----------|-----------|
| Tashkent | 41.31    | 69.24     |
| Fergana   | 40.38    | 71.78     |

# Note:

In your solution include the readme with the explanation of how to run the project and get the data.
