# DELETE /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/retention

**Resource:** [clusterLog](../resources/clusterLog.md)
**Reset cluster log retention**
**Operation ID:** `deleteClusterLogRetention`

Removes cluster overrides and returns the retention inherited from the environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Effective log retention settings |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[logRetention](../schemas/logRetention/logRetention.md)

