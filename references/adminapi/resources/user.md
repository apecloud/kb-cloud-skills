# user

User APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/user` | Get authenticated user | [View](../operations/getAuthenticatedUser.md) |
| PATCH | `/admin/v1/user` | Update user information | [View](../operations/patchAuthenticatedUser.md) |
| PATCH | `/admin/v1/user/password` | Update current authenticated user password | [View](../operations/updateAuthenticatedUserPassword.md) |
| DELETE | `/admin/v1/user/apikey/{keyName}` | Delete apikey | [View](../operations/deleteApikey.md) |
| PATCH | `/admin/v1/user/apikey/{keyName}` | Update apikey information | [View](../operations/patchAPIkey.md) |
| GET | `/admin/v1/user/apikeys` | Get apikeys of the authenticated user | [View](../operations/readUserApikeys.md) |
| POST | `/admin/v1/user/apikeys` | Create apikey of the authenticated user | [View](../operations/createUserApikey.md) |
| GET | `/admin/v1/users` | List users | [View](../operations/listUsers.md) |
| POST | `/admin/v1/users` | Create a new user | [View](../operations/createUser.md) |
| DELETE | `/admin/v1/users/{userID}` | delete user | [View](../operations/deleteUser.md) |
| PATCH | `/admin/v1/users/{userID}` | Update the information of the specified user | [View](../operations/patchUser.md) |
| PATCH | `/admin/v1/users/{userID}/password` | Update user password | [View](../operations/updateUserPassword.md) |
| GET | `/admin/v1/users/{userID}/authorization` | Get user roles in multiple organizations | [View](../operations/getUserAuthorization.md) |
