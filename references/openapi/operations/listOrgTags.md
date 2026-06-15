# GET /api/v1/organizations/{orgName}/tags

**Resource:** [clusterTag](../resources/clusterTag.md)
**List tags by organization name**
**Operation ID:** `listOrgTags`

List tags by organization name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list tags successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[orgTagsList](../schemas/orgTagsList/orgTagsList.md)

