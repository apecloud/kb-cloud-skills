# user

User APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/user` | Get authenticated user | [View](../operations/getAuthenticatedUser.md) |
| PATCH | `/api/v1/user` | Update user information | [View](../operations/patchAuthenticatedUser.md) |
| PATCH | `/api/v1/user/password` | Update current authenticated user password | [View](../operations/updateAuthenticatedUserPassword.md) |
| POST | `/api/v1/user/phone-verification-code` | Send verification code to user's phone | [View](../operations/phoneVerification.md) |
| DELETE | `/api/v1/user/apikey/{keyName}` | Delete apikey | [View](../operations/deleteApikey.md) |
| PATCH | `/api/v1/user/apikey/{keyName}` | Update apikey information | [View](../operations/patchAPIkey.md) |
| GET | `/api/v1/user/apikeys` | Get apikeys of the authenticated user | [View](../operations/readUserApikeys.md) |
| POST | `/api/v1/user/apikeys` | Create apikey of the authenticated user | [View](../operations/createUserApikey.md) |
