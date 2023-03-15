
# Represents weather forecasts for multiple days

| Element | | Description | Type | Notes |
|---|---|---|---|---|
| `longitude` | Data for a TV program recording | number | | 
| `latitude` | The date and time the program starts | number | |
| `forecasts` | An array of weather forecasts for different days | array of daily forecast objects | |
| | `date` | Date of the forecast | string | Format is YYYY-MM-DD |
| | `description` | Text description of the day’s weather conditions | string | Valid values: "sunny", "overcast", "partly cloudy", "raining", and "snowing". |
| | `maxTemp` | Maximum high temperature for the day | number | Format in degrees Celsius |
| | `minTemp` | Minimum low temperature for the day | number | Format in degrees Celsius |
| | `windSpeed` | Wind speed for the day | number | Format in kilometers per hour |
| | `danger` | Indicates if dangerous weather conditions are present | number | True if danger present; false if not. |