# GET /admin/v1/bills

**Resource:** [billing](../resources/billing.md)
**List bills**
**Operation ID:** `listBills`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `billID` | query | string | No | The ID of the bill |
| `clusterID` | query | string | No | The ID of the cluster |
| `orgName` | query | string | No | name of the organization |
| `projectName` | query | string | No | name of the project |
| `aggregationTime` | query | aggregationTimeType | No | The type of aggregation time |
| `aggregationGroup` | query | aggregationGroupType | No | The type of aggregation group |

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

