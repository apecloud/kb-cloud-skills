# PUT /admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/policies

**Resource:** [seaweedfs](../resources/seaweedfs.md)
**bindSeaweedFSPolicies**
**Operation ID:** `bindSeaweedFSPolicies`

Replaces named policy bindings. An empty policies array removes all direct bindings. Existing credentials, legacy actions and other identity attributes are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `policies` | string[] | Yes |  |

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

