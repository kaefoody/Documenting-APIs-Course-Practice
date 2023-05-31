# Weather forecasting API

Learn how to read and understand a response from our weather forecasting API.

## Response

This response represents a weather forecast for one location over multiple days.

            {
               "longitude": 47.60,
               "latitude": 122.33,
               "forecasts": [
               {
                   "date": "2015-09-01",
                   "description": "sunny",
                   "maxTemp": 22,
                   "minTemp": 20,
                   "windSpeed": 12,
                   "danger": false
               },
               {
                  "date": "2015-09-02",
                  "description": "overcast",
                  "maxTemp": 21,
                  "minTemp": 17,
                  "windSpeed": 15,
                  "danger": false
               },
               {
                  "date": "2015-09-03",
                  "description": "raining",
                  "maxTemp": 20,
                  "minTemp": 18,
                  "windSpeed": 13,
                  "danger": false
               }
               ]
            }

## Elements

| Element | | Description | Data type | Notes |
|---|---|---|---|---|
| `longitude` | | Longitude of the location’s forecast | Number | |
| `latitude` | | Longitude of the location’s forecast | Number | |
| `forecasts` | | Array of weather forecasts for several days | Array of forecast objects | |
| | `date` | Date of one forecast | String | Format is YYYY-MM-DD |
| | `description` | Text description of one day’s weather conditions | String | Valid values: "sunny", "overcast", "partly cloudy", "raining", and "snowing" |
| | `maxTemp` | Maximum high temperature for one day | Number | Format in degrees Celsius |
| | `minTemp` | Minimum low temperature for one day | Number | Format in degrees Celsius |
| | `windSpeed` | Wind speed for one day | Number | Format in kilometers per hour |
| | `danger` | Indicates if dangerous weather conditions are present | Number | True if danger present; false if not |
