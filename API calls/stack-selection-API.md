# **/api/stackSelection**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/stackSelection/userid

**Receive:** status: 200
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topics": 
      {
          "name": "string",
          "iconPath": "string"
      }
  }
] 
```

### POST: 

**Send:** 
/api/stackSelection/userid
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topics": 
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
/api/stackSelection/userid
```JSON
[
  {
    "difficulty": 
      {
        "name": "string",
        "iconPath": "string"
      }, 
    "topics": 
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
/api/stackSelection/userid


**Receive:** status: 200