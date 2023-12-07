# **/api/topicSelection**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/topicSelection/userid

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
/api/topicSelection/userid
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
/api/topicSelection/userid
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
/api/topicSelection/userid


**Receive:** status: 200