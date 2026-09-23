# GET /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/root-password

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**getRootSeaweedFSAccountPassword**
**Operation ID:** `getRootSeaweedFSAccountPassword`

get root account password

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | query | string | Yes | name of the account |
| `component` | query | string | No | name of the component |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get root account password success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

