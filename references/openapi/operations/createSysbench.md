# POST /api/v1/organizations/{orgName}/benchmark/sysbench

**Resource:** [benchmark](../resources/benchmark.md)
**Create a sysbench benchmark task**
**Operation ID:** `createSysbench`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [sysbench](../schemas/sysbench/sysbench.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

