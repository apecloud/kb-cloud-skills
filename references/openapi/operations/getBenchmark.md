# GET /api/v1/organizations/{orgName}/benchmark/{benchmarkId}

**Resource:** [benchmark](../resources/benchmark.md)
**Get benchmark task info**
**Operation ID:** `getBenchmark`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `benchmarkId` | path | string | Yes | id of the benchmark |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

