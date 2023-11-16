# **/api/answer-history**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: 

**Send:** 

```JSON
{
    "userid": "string",
    "question-id": "string"

}
```

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


### DELETE: get all user specific data

**Send:**

```JSON
{
    "userid": "string",
    "question-id": "string"

}
```

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
