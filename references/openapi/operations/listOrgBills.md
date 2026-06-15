# GET /api/v1/organizations/{orgName}/bills

**Resource:** [billing](../resources/billing.md)
**List bills in the organization**
**Operation ID:** `listOrgBills`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `billID` | query | string | No | The ID of the bill |
| `clusterID` | query | string | No | The ID of the cluster |
| `projectName` | query | string | No | name of the project |
| `aggregationTime` | query | aggregationTimeType | No | The type of aggregation time |
| `aggregationGroup` | query | orgAggregationGroupType | No | The type of aggregation group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List bill details |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[BillList](../schemas/Bill/BillList.md)

