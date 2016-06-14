## Not Found

Status Code: 404

Not found will always pass the URL, omitting the implied `/_/` as all API routes have this
preceding the entity endpoint.

Example:

```json
{
    "status":"requestError",
    "session_id": "1234567",
    "code":404,
    "data":{
        "message":"Not Found",
        "url":"/snapshots"
    },
    "time":3.553643
}
```