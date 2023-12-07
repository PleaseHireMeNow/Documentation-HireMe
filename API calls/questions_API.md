# **/api/questions**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/questions/userid

**Receive:** status: 200

```JSON
[
    {
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
    }
]
```


### POST: 
unneeded

### PUT:
unneeded

### DELETE:
unneeded
