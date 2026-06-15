# DELETE /api/v1/organizations/{orgName}/blueGreenDeployment/{deploymentID}

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Delete a blue-green deployment instance**
**Operation ID:** `deleteBlueGreenDeployment`

Delete a specified blue-green deployment instance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deploymentID` | path | string | Yes | The unique identifier of the blue-green deployment instance |
| `orgName` | path | string | Yes | Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Async job task information for blue-green deployment instance deletion. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[blueGreenDeploymentTask](../schemas/blueGreenDeploymentTask/blueGreenDeploymentTask.md)

