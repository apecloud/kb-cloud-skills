# POST /api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment/precheck

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Run a precheck for blue-green deployment**
**Operation ID:** `createBlueGreenDeploymentPreCheck`

Trigger a precheck task to verify settings or readiness for blue-green deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Name of the organization |
| `parentClusterID` | path | string | Yes | The unique identifier of the parent database cluster |
| `greenClusterVersion` | query | string | Yes | The version of the green cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Precheck task creation response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentPreCheckResponse](../schemas/blueGreenDeploymentPreCheckResponse/blueGreenDeploymentPreCheckResponse.md)

