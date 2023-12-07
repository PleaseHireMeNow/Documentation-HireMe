# **/api/user**
<!-- ! ADD ROUTE DESCRIPTION HERE -->


### GET: get all user specific data

**Send:** 
```JSON
{
 "user_token": "string"
}
```

**Receive:** status: 200
```JSON
{
  "user_id": "string",
  "username": "string",
  "topic_selection": [
    {
      "topic": "string",
      "difficulty": "string"
    }
  ],
  "is_guest": "boolean",
  "history": [
    {
      "question_id": "string",
      "question_content": {
        "prompt": "string",
        "responses": [
          {
            "response_content": {
              "text": "string"
            },
            "is_correct": "boolean"
          }
        ]
      }
    }
  ],
  "userAnswer": [
    {
      "question_id": "string",
      "question_content": {
        "prompt": "string",
        "responses": [
          {
            "response_content": {
              "text": "string"
            },
            "is_correct": "boolean"
          }
        ]
      },
      "response_content": {
        "text": "string"
      },
      "is_correct": "boolean"
    }
  ]
}
```
---

### POST:
unneeded


### PUT:
unneeded

### DELETE:
unneeded
