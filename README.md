# Weather CLI Live Coding: Python vs Rust

**URL**
`https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={api_key}`

**Env name**
`WEATHER_API_KEY`

**Response body**
```json
{
    "weather": [{"main": "STRING"}],
    "main": {"feels_like": "FLOAT64"}  // Is in °K (- 273.15 to convert to °C)
}
```
