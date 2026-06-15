# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/autohealing

**Resource:** [autohealing](../resources/autohealing.md)
**list autohealing job**
**Operation ID:** `getAutohealing`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get autohealing job list |

**Success Response Schema:**

[autohealingList](../schemas/autohealingList/autohealingList.md)

