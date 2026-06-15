# PATCH /admin/v1/engineVersions

**Resource:** [engine](../resources/engine.md)
**Update the specified engine version**
**Operation ID:** `patchEngineVersion`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [engineVersionUpdate](../schemas/engineVersionUpdate/engineVersionUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[engineVersion](../schemas/engineVersion/engineVersion.md)

