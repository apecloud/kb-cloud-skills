# POST /api/v1/organizations/{orgName}/benchmark/esrally

**Resource:** [benchmark](../resources/benchmark.md)
**Create an esrally benchmark task**
**Operation ID:** `createEsrally`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [esrally](../schemas/esrally/esrally.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[benchmark](../schemas/benchmark/benchmark.md)

