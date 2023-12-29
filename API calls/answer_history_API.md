# **/api/answerHistory**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: not needed (user route gets answer history)

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
  "rating": "number",
}
```

**Receive:** status: 200

### PUT: not needed

### DELETE: not needed
