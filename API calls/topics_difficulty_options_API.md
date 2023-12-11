# **/api/topic_options**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

get a current list of technologies and roles/difficulty levels

### GET:

**Send:**
/api/topic_options/user_id

**Receive:** status: 200

```JSON
{
  "difficulty": [
      {
        "name": "string",
        "iconPath": "string"
      }
  ],
  "topics": [
      {
          "name": "string",
          "iconPath": "string"
      }
  ]
}
```

### POST:

unneeded

### PUT:

unneeded

### DELETE:

unneeded
