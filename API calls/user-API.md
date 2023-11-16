# **/api/user**
<!-- ! ADD ROUTE DESCRIPTION HERE -->


### GET: get all user specific data

**Send:** 
```JSON
{
 "user-token": "string"
}
```

**Receive:** status: 200
```JSON
{
  "userId": "string",
  "username": "string",
  "stack-selection": ["string"],
  "is-guest": "boolean",
  "history": [
    {
      "question-id": "string",
      "question-content": {
        "prompt": "string",
        "responses": [
          {
            "response-content": {
              "text": "string"
            },
            "is-correct": "boolean"
          }
        ]
      }
    }
  ],
  "userAnswer": [
    {
      "question-id": "string",
      "question-content": {
        "prompt": "string",
        "responses": [
          {
            "response-content": {
              "text": "string"
            },
            "is-correct": "boolean"
          }
        ]
      },
      "response-content": {
        "text": "string"
      },
      "is-correct": "boolean"
    }
  ]
}
```
---

### POST: get all user specific data
unneeded


### PUT: get all user specific data
unneeded

### DELETE: get all user specific data
unneeded
