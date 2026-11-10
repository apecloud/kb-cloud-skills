# PUT /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/retention

**Resource:** [clusterLog](../resources/clusterLog.md)
**Set cluster log retention**
**Operation ID:** `putClusterLogRetention`

Replaces the current settings. Applies to the next cleanup.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [logRetention](../schemas/logRetention/logRetention.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Log retention settings |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[logRetention](../schemas/logRetention/logRetention.md)

