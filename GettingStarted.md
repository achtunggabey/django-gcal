# Installation #



# Writing an Adapter #

| **Method** | **Description** |
|:-----------|:----------------|
| `get_event_data(instance)` | Returns an object conforming to the CalendarEventData interface. |
| `can_save(instance)` | Returns True if the adaptee should be stored or updated in Google Calendar, returns False otherwise. |
| `can_delete(instance)` | Returns True if the adaptee should be removed from Google Calendar, returns False otherwise. |

# Connecting Models to Google Calendar #