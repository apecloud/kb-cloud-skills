# DELETE /admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**deleteSeaweedFSPolicy**
**Operation ID:** `deleteSeaweedFSPolicy`

Deletes an unused named policy. Attached policies are rejected; no identities or groups are implicitly changed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `policyName` | path | string | Yes |  |

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

