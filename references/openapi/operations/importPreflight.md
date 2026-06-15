# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight

**Resource:** [import](../resources/import.md)
**Data source preflight check**
**Operation ID:** `importPreflight`

Initiates async validation with the selected source configuration

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Request Body

Data source connection configuration and selection rules

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ImportPreflightRequest](../schemas/Import/ImportPreflightRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Preflight initiated successfully, returns task ID for querying results |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[preCheckTaskResponse](../schemas/preCheckTaskResponse/preCheckTaskResponse.md)

