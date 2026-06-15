# POST /api/v1/organizations/{orgName}/benchmark/pgbench

**Resource:** [benchmark](../resources/benchmark.md)
**Create a pgbench benchmark task**
**Operation ID:** `createPgbench`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [pgbench](../schemas/pgbench/pgbench.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

