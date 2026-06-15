# GET /api/v1/organizations/{orgName}/blueGreenDeployment/precheck/{preCheckID}

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Get blue-green deployment precheck task detail**
**Operation ID:** `getBlueGreenDeploymentPreCheckDetail`

Retrieve the details of a precheck task for a blue-green deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `preCheckID` | path | string | Yes | The unique identifier of the precheck task |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details of the precheck task. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentPreCheckResponse](../schemas/blueGreenDeploymentPreCheckResponse/blueGreenDeploymentPreCheckResponse.md)

