# POST /api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/promote

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**Promote a disaster recovery instance to the main instance**
**Operation ID:** `promoteDisasterRecovery`

Promote the disaster recovery instance to the primary database instance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `clusterID` | path | string | Yes | The ID of the disaster recovery instance |
| `orgName` | path | string | Yes | name of the org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [disasterRecoveryPromote](../schemas/disasterRecoveryPromote/disasterRecoveryPromote.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Disaster recovery instance async job task information. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryTask](../schemas/disasterRecoveryTask/disasterRecoveryTask.md)

