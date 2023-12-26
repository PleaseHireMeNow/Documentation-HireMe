# **/api/questions**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/questions/user_id/new

**Receive:** status: 200

```JSON
[
  {
    "question": {
      "question_id": "string",
      "question_content": {
          "text": "string",
          "answers": [
                  {
                  "answer_content": {
                        "text": "string"
                    },
                    "is_correct": "boolean"
                }
            ]
        }
    },
    "is_complete": "boolean"
    }
]
```

**Send:** 
/api/questions/user_id/prev

**Receive:** status: 200

```JSON
[
  {
    "question": {
      "question_id": "string",
      "question_content": {
          "text": "string",
          "answers": [
                  {
                  "answer_content": {
                        "text": "string"
                    },
                    "is_correct": "boolean"
                }
            ]
        }
    },
    "is_complete": "boolean"
    }
]
```

### POST: 
unneeded

### PUT:
unneeded

### DELETE:
unneeded
