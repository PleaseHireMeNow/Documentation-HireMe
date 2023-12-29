# **/api/questions**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:

**Send:**
/api/questions/user_id/new

**Receive:** status: 200

```JSON
{
  "sessionQuestionList": [
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
  ],
  "current_question": "number"
}
```

**Send:**
/api/questions/user_id/prev

**Receive:** status: 200

```JSON
{
  "questions": [
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
      },
    }
  ],
  "current_question": "number",
  "timestamp": "Timestamp"
}
```

### POST:

unneeded

### PUT:

unneeded

### DELETE:

unneeded
