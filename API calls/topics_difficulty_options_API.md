# **/api/topicOptions**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

get a current list of technologies and roles/difficulty levels

### GET:

**Send:**
/api/topicOptions/userid

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