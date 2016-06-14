## Service Unavailable

Status Code: 503

The remote service is currently offline, try again shortly.

Example:

```json
{
    "status":"requestError",
    "code":503,
    "data":{},
    "time":3.553643
}
```

This endpoint will not return a `session_id` because the proxy server/load balancer does not manage or have access to
session data.