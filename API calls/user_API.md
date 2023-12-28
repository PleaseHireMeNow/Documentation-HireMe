# **/api/user**
<!-- ! ADD ROUTE DESCRIPTION HERE -->


### GET: get all user specific data

**Send:** 
```JSON
{
 "user_token": "string"
}
```

**Receive:** status: 200
```JSON
{
  "user": {

    "user_id": "string",
    "username": "string",
    "topic_selection": [
      {
        "topic": {
          "name": "string",
          "iconPath": "string"
        },
        "difficulty": {
          "name": "string",
          "iconPath": "string"
        }
      }
    ],
    "is_guest": "boolean",
  },
  "session_history": [

        {
            "question_content": {
                "text": "string",
                "answers": [
                    {
                        "is_correct": true,
                        "answer_content": {
                            "text": "string"
                        }
                    },
                ]
            },
            "answered_correctly": "number",
            "answered_incorrectly": "number",
            "question_id": "string",
            "responses": [
                {
                    "timestamp": {
                        "seconds": "number",
                        "nanoseconds": "number"
                    },
                    "response": {
                        "answer": {
                            "is_correct": "boolean",
                            "answer_content": {
                                "text": "string"
                            }
                        }
                    }
                }
            ]
        }
  ],
  "current_session": {
    "current_question": "number",
    "answered_correctly": "number",
    "timestamp": "Timestamp",
    "questions": [
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
          },
          "rating": "number"
        },
        "answer": {
          "answer_content": {
            "text": "string"
          },
          "is_correct": "boolean"
        }
      }
    ],
  }
  }
```
---

### POST:
unneeded


### PUT:
unneeded

### DELETE:
unneeded
