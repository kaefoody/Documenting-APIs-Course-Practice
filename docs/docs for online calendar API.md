# Online calendar API
Represents a single meeting for an [online calendar scheduling API](https://github.com/kaefoody/Documenting-APIs-Course-Practice/blob/main/Online_Calendar_API/online-calendar-API.json).

## Request 

| Element | | Description | Type | Required | Notes |
|---|---|---|---|---|---|
| `meeting` | | Top level | meeting data objects | Required | |
| | `time` | Date and time meeting begins; timezone is GMT | string | Required | Format is YYYY-MM-DD HH:MM. |
| | `duration` | Length of the meeting, in minutes | number | Required | |
| | `description` | Text description of the meeting | string | Required | |
| | `location` | Location of the meeting | string | Optional | Default is an empty string. |
| | `reminder` | Amount of time before the meeting that participants are reminded, in minutes | number | Optional | Default is 10 minutes. |
| | `invitees` | Emails of persons invited to the meeting | array of strings | Optional | Default is an empty array. |