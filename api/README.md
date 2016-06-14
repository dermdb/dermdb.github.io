## DermDB API Documentation

### Introduction

DermDB follows a RESTful API structure, taking in and responding with JSON packets.

### Create Account

1. POST to `/_/users`
2. Save cookie
3. PUT to `/_/users`, to update account
4. Continue as new user

### Authentication

1. POST to `/_/users`
2. Save cookie
3. Continue as normal

### List of endpoints

| Action | Method | Endpoint |
| ------ | ------ | -------- |
| Get Session Information | GET  | [`/_/session`](api/endpoints/session.md#Select) |
| Login |  POST  | [`/_/session`](api/endpoints/session.md#Create) |
| Logout | DELETE   | [`/_/session`](api/endpoints/session.md#Delete) |
| Select User | GET | [`/_/users`](api/endpoints/users.md#Select) |
| Create New User Account | POST | [`/_/users`](api/endpoints/users.md#Create) |
| Replace User |  PUT  | [`/_/users`](api/endpoints/users.md#Replace) |
| Delete Account | DELETE | [`/_/users`](api/endpoints/users.md#Delete) |
| Update User Information |  PATCH  | [`/_/users`](api/endpoints/users.md#Update) |
| Select Problem | GET   | [`/_/problems`](api/endpoints/problems.md#Select) |
| Create Problem | POST   | [`/_/problems`](api/endpoints/problems.md#Create) |
| Replace Problem | PUT   | [`/_/problems`](api/endpoints/problems.md#Replace) |
| Update Problem | PATCH  | [`/_/problems`](api/endpoints/problems.md#Update) |
| Delete Problem | DELETE   | [`/_/problems`](api/endpoints/problems.md#Delete) |
| Select Snapshot | GET   | [`/_/snapshots`](api/endpoints/snapshots.md#Select) |
| Create Snapshot |  POST  | [`/_/snapshots`](api/endpoints/snapshots.md#Create) |
| Replace Snapshot | PUT   | [`/_/snapshots`](api/endpoints/snapshots.md#Replace) |
| Update Snapshot | PATCH   | [`/_/snapshots`](api/endpoints/snapshots.md#Update) |
| Delete Snapshot | DELETE   | [`/_/snapshots`](api/endpoints/snapshots.md#Delete) |
| Select Image | GET   | [`/_/images`](api/endpoints/images.md#Select) |
| Create Image |  POST  | [`/_/images`](api/endpoints/images.md#Create) |
| Replace Image | PUT   | [`/_/images`](api/endpoints/images.md#Replace) |
| Update Image | PATCH   | [`/_/images`](api/endpoints/images.md#Update) |
| Delete Image | DELETE   | [`/_/images`](api/endpoints/images.md#Delete) |

### Errors

Error documentation can be found [here](api/errors).
