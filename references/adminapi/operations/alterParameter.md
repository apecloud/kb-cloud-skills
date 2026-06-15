# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameter

**Resource:** [dms](../resources/dms.md)
**alter cluster parameter**
**Operation ID:** `alterParameter`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `tenantId` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsObAlterParameter](../schemas/Dms/DmsObAlterParameter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | close the session success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

