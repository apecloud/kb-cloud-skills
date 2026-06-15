# POST /api/v1/organizations/{orgName}/parent/{parentClusterID}/blueGreenDeployment

**Resource:** [blueGreenDeployment](../resources/blueGreenDeployment.md)
**Create a new blue-green deployment instance**
**Operation ID:** `createBlueGreenDeployment`

Create a blue-green deployment instance for the specified parent cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parentClusterID` | path | string | Yes | The unique identifier of the parent database cluster |
| `orgName` | path | string | Yes | Name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [blueGreenDeploymentCreation](../schemas/blueGreenDeploymentCreation/blueGreenDeploymentCreation.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when blue-green deployment instance is created successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 501 | (reference) |

