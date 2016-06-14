## Method Not Supported

Status Code: 405

The method used is not supported. If you have tried to use a PUT or a PATCH, try using a
POST in the unfortunate event that full behaviour of the PUT has not been created, such
as where creating a session is involved.

Example:

```json
{
    "status":"requestError",
    "session_id": "1234567",
    "code":405,
    "data":{},
    "time":3.553643
}
```