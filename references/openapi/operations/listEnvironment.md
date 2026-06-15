# GET /api/v1/organizations/{orgName}/environments

**Resource:** [environment](../resources/environment.md)
**List environments**
**Operation ID:** `listEnvironment`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `engine` | query | string | No | engine name |
| `version` | query | string | No | version of the engine |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentList](../schemas/environmentList/environmentList.md)

