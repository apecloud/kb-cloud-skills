# PUT /admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**putSeaweedFSPolicy**
**Operation ID:** `putSeaweedFSPolicy`

Creates or replaces a named AWS IAM JSON policy document. Updates affect every identity and group that uses this policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `policyName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

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

