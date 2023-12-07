# **/api/answerHistory**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:

**Send:**
/api/answerHistory/userid

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
/api/answerHistory/userid

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
/api/answerHistory/userid/question_id

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
