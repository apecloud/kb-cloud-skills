# GET /api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**listSeaweedFSAccounts**
**Operation ID:** `listSeaweedFSAccounts`

Lists SeaweedFS identities and access-key metadata without secret keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[accountList](../schemas/accountList/accountList.md)

