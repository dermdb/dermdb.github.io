### Request Errors

These are usually with status code 4xx where the client has performed a request error
and needs to change this before continuing.

For example, a 401 will not change on retry until the user performs a login but a 404
will never work until either the resource is created, or the user changes their request.

A 401 is endpoint specific, whereas a 404 is request specific.

Here are the full list of supported client errors:

| Name | Status Code |
| ---- | ----------- |
| [Not Authenticated](api/errors/not_authenticated.md) | 401 |
| [Not Authorised](api/errors/not_authorised.md) | 403 |
| [Not Found](api/errors/not_found.md) | 404 |

Alternatively, for 500 errors, see [Server Errors](api/erors/serverError.md)

