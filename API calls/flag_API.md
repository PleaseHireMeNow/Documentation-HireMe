# **/api/answerHistory**

<!-- ! ADD ROUTE DESCRIPTION HERE -->

### GET: not needed

### POST:
<!-- We need to run this route if the response in the get questions route included a flag indicating true -->
**Send:**
/api/flag/user_id
req.body = 
```JSON
{
  "flag": "true"
}
```

**Receive:** status: no response required

### PUT: not needed

### DELETE: not needed
