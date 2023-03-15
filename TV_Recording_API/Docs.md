
# Description: Represents a request for a TV recording API

| Element | Attribute | Description | Type | Optional | Notes |
|---|---|---|---|---|---|
| `code` recordTV | | Data for a TV program recording | TV program data | Required | |
| when | | The date and time the program starts | date and time data | Required | |
| | date | Date the program starts | string | Optional | Format is YYYY-MM-DD. Default is today’s date. |
| | time | Time the program starts | string | Required | Format is HH:MM, with am or pm after for 12 hour format. |
| | format | Time format in either 12 or 24 hours | number | Required | Valid values: 12 or 24. |
| duration | | Length of the program | number data | Required | |
| | hours | Length of the program in hours | number | Required | |
| station | | Station number to record | station data | Required | |
| | channel | Channel number to record | number | Required | |