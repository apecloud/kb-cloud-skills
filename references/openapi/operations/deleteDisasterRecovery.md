# DELETE /api/v1/organizations/{orgName}/disasterRecovery

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**Delete a disaster recovery instance**
**Operation ID:** `deleteDisasterRecovery`

Delete a specific disaster recovery instance

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `logicalInstanceID` | query | string | No | The ID of the disaster recovery logical instance |
| `clusterID` | query | string | No | The ID of the disaster recovery cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Disaster recovery instance async job task information. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryTask](../schemas/disasterRecoveryTask/disasterRecoveryTask.md)

