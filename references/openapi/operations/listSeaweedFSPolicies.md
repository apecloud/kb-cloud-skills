# GET /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**listSeaweedFSPolicies**
**Operation ID:** `listSeaweedFSPolicies`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `items` | object[] | Yes |  |

**`items` fields:**

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `document` | object | Yes |  |

