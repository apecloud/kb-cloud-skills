# PATCH /admin/v1/organizations/{orgName}/tags/{tagId}

**Resource:** [clusterTag](../resources/clusterTag.md)
**Operation ID:** `updateTag`

Update cluster tags

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `tagId` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tagUpdate](../schemas/tagUpdate/tagUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[tag](../schemas/tag/tag.md)

