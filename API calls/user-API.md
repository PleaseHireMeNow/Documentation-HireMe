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
        "text": "string",
        "answers": [
          {
            "answer-content": {
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
      "answer-content": {
        "text": "string"
      },
      "is-correct": "boolean"
    }
  ]
}
```
---

### POST: get all user specific data

**Send:** 
```JSON
{

}
```

**Receive:** status: 200
```JSON
{
  
}
```

### PUT: get all user specific data

**Send:** 
```JSON
{
  
}
```

**Receive:** status: 200
```JSON
{
  
}
```

### DELETE: get all user specific data

**Send:** 
```JSON
{
  
}
```

**Receive:** status: 200
```JSON
{
  
}
```

