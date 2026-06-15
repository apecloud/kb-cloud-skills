# GET /api/v1/organizations/{orgName}/clusterTags

**Resource:** [clusterTag](../resources/clusterTag.md)
**Get cluster tags**
**Operation ID:** `getTags`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterIds` | query | string | Yes | Comma-separated list of cluster IDs |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list tags successfully |

**Success Response Schema:**

Array of [clusterTags](../schemas/clusterTags/clusterTags.md)

