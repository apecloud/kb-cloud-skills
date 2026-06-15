# POST /admin/v1/organizations/{orgName}/parent/{parentClusterID}/disasterRecovery

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**Create a new disaster recovery instance**
**Operation ID:** `createDisasterRecovery`

Create a new disaster recovery instance for a database cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parentClusterID` | path | string | Yes | The ID of the parent database cluster |
| `orgName` | path | string | Yes | name of the org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [disasterRecoveryCreate](../schemas/disasterRecoveryCreate/disasterRecoveryCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Disaster recovery instance async job task information. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryTask](../schemas/disasterRecoveryTask/disasterRecoveryTask.md)

