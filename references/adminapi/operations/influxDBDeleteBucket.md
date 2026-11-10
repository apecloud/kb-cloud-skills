# DELETE /admin/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets/{bucketID}

**Resource:** [database](../resources/database.md)
**InfluxDB DeleteBucket**
**Operation ID:** `influxDBDeleteBucket`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `bucketID` | path | string | Yes |  |
| `influxOrgID` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

