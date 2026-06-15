# GET /admin/v1/environments

**Resource:** [environment](../resources/environment.md)
**List environments**
**Operation ID:** `listEnvironment`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | name of the Org |
| `cloudProvider` | query | string | No | cloud provider of the Environment |
| `cloudRegion` | query | string | No | cloud region of the Environment |
| `environmentType` | query | environmentType | No | type of the Environment |
| `engine` | query | string | No | engine name |
| `version` | query | string | No | version of the engine |
| `slaEnabled` | query | boolean | No | whether the environment is enabled for SLA |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[environmentList](../schemas/environmentList/environmentList.md)

