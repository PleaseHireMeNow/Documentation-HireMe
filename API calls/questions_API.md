# **/api/questions**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET:

**Send:**
<!-- get a new session for the user -->
/api/questions/current/new/user_id/
<!-- get the most recent active session for the user -->
/api/questions/current/current/user_id/ 
<!-- get a previous session by submitting the previous session id -->
/api/questions/previous/user_id/session_id

**Receive:** status: 200

```JSON
{
  "session_id": "string",
  "current_question": "number",
  "answered_correctly": "number",
  "timestamp": "Timestamp",
  "topic_selection": {
    "topic": {
      "name": "string",
      "iconPath": "string"
    },
    "difficulty": {
      "name": "string",
      "iconPath": "string"
    }
  },
  "questions": [
    {
      "question":  {
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
      },
      "answer": {
        "answer_content": {
          "text": "string";
        },
        "is_correct": "boolean"
      }
    }
  ]
}
```

### POST:

unneeded

### PUT:

unneeded

### DELETE:

unneeded
