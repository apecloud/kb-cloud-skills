# engineLicenseCreate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the engine license |
| `engineName` | string | Yes | Name of the engine |
| `description` | string | No | Description of the engine license |
| `expiredAt` | string (date-time) | No | Expiration date and time of the license (optional) |
| `environmentID` | string | No | Environment ID of the license (optional) |
| `type` | string | Yes | Type of the license. Determines whether licenseFile is required. |
| `licenseFile` | string (binary) | No | The license file to upload. Required when type is not NodeScope; optional when type is NodeScope. |

