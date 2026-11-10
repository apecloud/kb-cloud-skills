# licenseOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `opsDefName` | string | Yes |  |
| `fileDigestParameter` | string | No | Optional custom Ops parameter receiving a JSON object of candidate file SHA256 digests. |
| `restartAfterUpdate` | boolean | No | Create a standard restart dependent on successful license installation. |

