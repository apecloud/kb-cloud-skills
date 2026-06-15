# POST /api/v1/user/phone-verification-code

**Resource:** [user](../resources/user.md)
**Send verification code to user's phone**
**Operation ID:** `phoneVerification`

to update user phone number, send verification code first

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `phoneNumber` | [phoneNumber](../schemas/phoneNumber/phoneNumber.md) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Verification code sent to user's phone |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

