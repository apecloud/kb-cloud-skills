# DELETE /admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys/{accessKey}

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**deleteSeaweedFSAccessKey**
**Operation ID:** `deleteSeaweedFSAccessKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `accessKey` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

