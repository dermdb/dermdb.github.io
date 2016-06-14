## Internal Server Error

Status Code: 500

An unknown error occurred, you may try this resource again, but the error may persist.

Example:

```json
{
    "status":"requestError",
    "session_id":"1234",
    "code":503,
    "data":{},
    "time":3.553643
}
```

This error *may* not have a `session_id`, but this edge case is unlikely. If there is no
`session_id` this error can be treated with similar behaviour to a `503 - Service Unavailable`
error.