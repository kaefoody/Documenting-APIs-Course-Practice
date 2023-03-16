# Temperature and humidity API
Represents a response from an [API that measures the temperature and humidity](https://github.com/kaefoody/Documenting-APIs-Course-Practice/blob/main/Temperature_and_Humidity_API/temperature-and-humidity-api.xml) of multiple museum exhibits. 

## Response 


### Top level
| Element | Description | Type | Notes |
|---| --- | --- | --- |
| `dailyData`   | Data from multiple humidity and temperature readings for one day, measured hourly | `dailyData` element  |                       |

### `dailyData`: Represents a collection of hourly data readings for one day
| Element | Description | Type | Notes |
|---| --- | --- | --- |
| `date`        | Date of data readings                                                             | string               | Format is YYYY-MM-DD. |
| `hourlyData`  | Data for one hourly reading                                                       | `hourlyData` element |                       |


### `hourlyData`: Represents the details of one hourly data reading
| Element | Description | Type | Notes |
|---| --- | --- | --- |
| `time`        | Local time that the hourly reading was recorded                                   | string               | Format is HH:MM.      |
| `device`      | Details of the hourly data reading measured by one device                         | `device` element     |                       |

### `device`: Represents the temperature and humidity data measured by one device
| Element | Description | Type | Notes |
|---| --- | --- | --- |
| `id`          | The device’s identification number                                                | number               |                       |
| `temperature` | Details of the hourly data reading measured by one device                         | number               |                       |
| `humidity`    | The measured humidity, in percentage                                              | number               |                       |
