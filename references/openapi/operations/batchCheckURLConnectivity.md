# POST /api/v1/alerts/checkURL

**Resource:** [alert](../resources/alert.md)
**Batch check URLs connectivity**
**Operation ID:** `batchCheckURLConnectivity`

Tests multiple URLs for connectivity in parallel

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [URLCheck](../schemas/URLCheck/URLCheck.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[URLCheck](../schemas/URLCheck/URLCheck.md)

