# GET /admin/v1/metrics/metaData/aggregate

**Resource:** [metrics](../resources/metrics.md)
**Get aggregate meta data**
**Operation ID:** `getAggregateMetaData`

Get aggregate meta data including total count and time series

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `metaData` | query | aggregateMetaDataType | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[aggregateMetaData](../schemas/aggregateMetaData/aggregateMetaData.md)

