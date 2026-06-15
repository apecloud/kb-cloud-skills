# license

License info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterID` | string | Yes | The kubernetes cluster ID |
| `email` | string | Yes | The licensed user email |
| `userName` | string | Yes | The licensed user or organization name |
| `unit` | string | Yes | The licensed unit, such as CPU or Node |
| `quantity` | string | Yes | The licensed total count of the unit |
| `engines` | engineQuota[] | Yes | The supported engines and their quotas |
| `notAfter` | string (date-time) | Yes | The license expiration time |
| `notBefore` | string (date-time) | Yes | The license start time |
| `used` | number (double) | Yes | The used count of the unit |
| `license` | string | Yes | The license key |
| `mode` | string | No | If KubeBlocks Enterprise is embedded in another platform, the license may be managed by the platform. It this case, we should extract the KubeBlocks Enterprise license from the platform and use it. Different platforms may have different ways to provide the license. The licenseMode is used to specify the different platform. For KubeSphere Enterprise, the licenseMode is `kse`. |

