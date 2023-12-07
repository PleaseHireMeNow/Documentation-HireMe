# **/api/topicSelection**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/topic_selection/user_id

**Receive:** status: 200
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topic": 
      {
          "name": "string",
          "iconPath": "string"
      }
  }
] 
```

### POST: 

**Send:** 
/api/topic_selection/user_id
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topic": 
      {
          "name": "string",
          "iconPath": "string"
      }
  }
]
```

**Receive:** status: 200


### PUT:

**Send:** 
/api/topic_selection/user_id
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topic": 
      {
          "name": "string",
          "iconPath": "string"
      }
  }
]
```

**Receive:** status: 200


### DELETE: 

**Send:** 
/api/topic_selection/user_id


**Receive:** status: 200