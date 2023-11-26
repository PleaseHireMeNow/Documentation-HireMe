# **/api/answer-history**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:

**Send:**
/api/answer-history/userid

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

**Send:**
/api/answer-history/userid

```JSON
{
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
        },
        "usefulness": "number",
        "accuracy": "number"
    }
}
```

**Receive:** status: 200

### PUT: not needed

### DELETE: 

**Send:**
/api/answer-history/userid/question-id

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
