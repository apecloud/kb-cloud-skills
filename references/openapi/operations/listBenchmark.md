# GET /api/v1/organizations/{orgName}/benchmark

**Resource:** [benchmark](../resources/benchmark.md)
**List benchmark tasks**
**Operation ID:** `listBenchmark`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `cluster` | query | string | No | name of the cluster |
| `benchType` | query | string | No | type of the benchmark |
| `clusterID` | query | string | No | id of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmarkList](../schemas/benchmarkList/benchmarkList.md)

