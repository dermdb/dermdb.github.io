## Users

Endpoint: `/_/users`

Endpoint to select, create, and modify users.

This is the endpoint to create a new user account.

### Create

Method: POST

| Field | Value | Restrictions | Required |
| ----- | ----- | ------------ | -------- |
| firstName | Latin String | Length | True |
| lastName | Latin String | Length | True |
| email | String | Must contain @ and valid TLD | True |
| password | String | Length greater than 8, upper, lower, number, special | True |

### Select

Method: GET

Response:

Errors:

* 401 - [Not Authenticated](api/errors/not_authenticated.md)
* 403 - [Not Authorised](api/errors/not_authorised.md)
* 404 - [Not Found](api/errors/not_found.md)
* 405 - [Method Not Supported](api/errors/method_not_supported.md)
* 422 - [Missing Parameters](api/errors/missing_parameters.md)


### Replace

Method: PUT

### Update

Method: PATCH

### Delete

Method: DELETE

