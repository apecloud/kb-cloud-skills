# GET /api/v1/organizations/{orgName}/disasterRecovery/{clusterID}/switchHistory

**Resource:** [disasterRecovery](../resources/disasterRecovery.md)
**Get switch history of a disaster recovery instance**
**Operation ID:** `getDisasterRecoveryHistory`

Retrieve the history of failover and failback operations for a specific disaster recovery instance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `clusterID` | path | string | Yes | The ID of the disaster recovery instance |
| `orgName` | path | string | Yes | name of the org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Switch history retrieved successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[disasterRecoveryHistory](../schemas/disasterRecoveryHistory/disasterRecoveryHistory.md)

