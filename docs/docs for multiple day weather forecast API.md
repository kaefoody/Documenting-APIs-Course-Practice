# Weather forecasting API
Represents a response from a [weather forecasting API](https://github.com/kaefoody/Documenting-APIs-Course-Practice/blob/main/Weather_Forecast_API/3-day-forecast.json) that returns the forecast for multiple days.

## Response 

| Element | | Description | Type | Notes |
|---|---|---|---|---|
| `longitude` | | Longitude of the location’s forecast | number | | 
| `latitude` | | Longitude of the location’s forecast | number | |
| `forecasts` | | An array of weather forecasts for several days | array of daily forecast objects | |
| | `date` | Date of one forecast | string | Format is YYYY-MM-DD. |
| | `description` | Text description of one day’s weather conditions | string | Valid values: "sunny", "overcast", "partly cloudy", "raining", and "snowing". |
| | `maxTemp` | Maximum high temperature for one day | number | Format in degrees Celsius. |
| | `minTemp` | Minimum low temperature for one day | number | Format in degrees Celsius. |
| | `windSpeed` | Wind speed for one day | number | Format in kilometers per hour. |
| | `danger` | Indicates if dangerous weather conditions are present | number | True if danger present; false if not. |