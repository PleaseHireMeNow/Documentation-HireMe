# **/api/answerHistory**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:

**Send:**
/api/answer_history/user_id

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

**Send:**
/api/answer_history/user_id

```JSON
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
  "usefulness": "number",
  "accuracy": "number"
}
```

**Receive:** status: 200

### PUT: not needed

### DELETE:

**Send:**
/api/answer_history/user_id/question_id

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
