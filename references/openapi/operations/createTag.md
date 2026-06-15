# POST /api/v1/organizations/{orgName}/tags

**Resource:** [clusterTag](../resources/clusterTag.md)
**Create cluster tags**
**Operation ID:** `createTag`

create tag

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tagCreate](../schemas/tagCreate/tagCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | create tag successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[tagCreate](../schemas/tagCreate/tagCreate.md)

