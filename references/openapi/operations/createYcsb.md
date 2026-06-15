# POST /api/v1/organizations/{orgName}/benchmark/ycsb

**Resource:** [benchmark](../resources/benchmark.md)
**Create a ycsb benchmark task**
**Operation ID:** `createYcsb`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ycsb](../schemas/ycsb/ycsb.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

