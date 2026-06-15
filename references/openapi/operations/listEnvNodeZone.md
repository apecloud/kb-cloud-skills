# GET /api/v1/organizations/{orgName}/environments/{environmentName}/availableZones

**Resource:** [environment](../resources/environment.md)
**List the availability zones where the environment's nodes are located**
**Operation ID:** `listEnvNodeZone`

List available zones of an environment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[stringList](../schemas/stringList/stringList.md)

