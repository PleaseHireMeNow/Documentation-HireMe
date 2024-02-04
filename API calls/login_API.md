# **/api/login**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:



### POST:

**Send:**
<!-- get a new session for the user -->
/api/questions/current/new/user_id/
<!-- get the most recent active session for the user -->
/api/questions/current/current/user_id/ 
<!-- get a previous session by submitting the previous session id -->
/api/questions/previous/user_id/session_id

**Receive:** status: 200

```JSON
{
  "logintoken": "string"
}
```

### PUT:

unneeded

### DELETE:

unneeded
