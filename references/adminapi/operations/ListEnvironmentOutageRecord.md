# GET /admin/v1/sla/outages

**Resource:** [SLA](../resources/SLA.md)
**List outage record for environments**
**Operation ID:** `ListEnvironmentOutageRecord`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | query | string | No | name of the environment, if not specified, return all environments |
| `orgName` | query | string | No | name of the organization |
| `clusterID` | query | string | No | id of the cluster |
| `activeOnly` | query | boolean | No | whether to return only active outage records |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Outage record retrieved successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[OutageRecordList](../schemas/Outage/OutageRecordList.md)

