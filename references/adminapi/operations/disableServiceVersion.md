# POST /admin/v1/engineVersions/disable

**Resource:** [engine](../resources/engine.md)
**Disable service version**
**Operation ID:** `disableServiceVersion`

Remove a service version from the engine version's service_versions list if no running clusters are using it

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [engineVersionDisableServiceVersion](../schemas/engineVersionDisableServiceVersion/engineVersionDisableServiceVersion.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineVersion](../schemas/engineVersion/engineVersion.md)

