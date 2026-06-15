# POST /api/v1/organizations/{orgName}/benchmark/tpcc

**Resource:** [benchmark](../resources/benchmark.md)
**Create a tpcc benchmark task**
**Operation ID:** `createTpcc`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [tpcc](../schemas/tpcc/tpcc.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

