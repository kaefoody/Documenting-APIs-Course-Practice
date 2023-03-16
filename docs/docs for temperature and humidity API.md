# Temperature and humidity API
Represents a response from an [API that measures the temperature and humidity](https://github.com/kaefoody/Documenting-APIs-Course-Practice/blob/main/Temperature_and_Humidity_API/temperature-and-humidity-api.xml) for multiple museum exhibits. 

## Response 


#### Top level
| <div style="width:100px">Element</div> |<div style="width:300px">Description</div> | <div style="width:100px">Type</div> | <div style="width:300px">Notes</div> |
|---| --- | --- | --- |
| `dailyData` | Data from multiple humidity and temperature readings for one day, measured hourly | `dailyData` element  | |
| `date` | Date of data readings | string | Format is YYYY-MM-DD. |

#### `dailyData`: Represents a collection of hourly data readings for one day

#### `hourlyData`: Represents the details of one hourly data reading

#### `device`: Represents the temperature and humidity data measured by one device
