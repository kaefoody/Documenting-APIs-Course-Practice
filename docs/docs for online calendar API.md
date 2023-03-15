# Represents a single meeting for an online calendar. 

| Element | | Description | Type | Required | Notes |
|---|---|---|---|---|---|
| `meeting` | | Top level | meeting data objects | Required | |
| | `time` | Date and time meeting begins. Timezone is GMT. | string | Required | Format is YYYY-MM-DD HH:MM. |
| | `duration` | Length of the meeting, in minutes | number | Required | |
| | `description` | Text description of the meeting | string | Required | |
| | `location` | Location of the meeting | string | Optional | Default is an empty string. |
| | `reminder` | Amount of minutes before the meeting that participants are reminded | number | Optional | Default is 10 minutes. |
| | `invitees` | Emails of persons invited to the meeting | array of strings | Optional | Default is an empty array. |


