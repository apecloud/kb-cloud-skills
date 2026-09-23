# DELETE /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**deleteSeaweedFSAccount**
**Operation ID:** `deleteSeaweedFSAccount`

delete an account in cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accountName` | path | string | Yes | name of the account |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Identity deleted |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

