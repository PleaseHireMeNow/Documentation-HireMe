# **/api/questions**
<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 
**Send:** 
/api/questions/userid

**Receive:** status: 200

```JSON
{
    [
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
    ]
}
```


### POST: 
unneeded

### PUT: get all user specific data
unneeded

### DELETE: get all user specific data
unneeded
