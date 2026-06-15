# engineOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `engineName` | string | Yes |  |
| `maturityLevel` | string | No | engine maturity level |
| `title` | string | Yes |  |
| `status` | [engineOptionStatus](engineOptionStatus.md) | No |  |
| `description` | [localizedDescription](localizedDescription.md) | Yes |  |
| `versions` | string[] | No |  |
| `components` | componentOption[] | Yes |  |
| `modes` | modeOption[] | Yes |  |
| `defaultMode` | string | No | The default mode name to be selected when creating a cluster.
This field is used by the frontend only.
The value should match one of the mode names defined in the modes array.
 |
| `account` | [accountOption](accountOption.md) | No |  |
| `database` | [databaseOption](databaseOption.md) | No |  |
| `dms` | [dmsOption](dmsOption.md) | Yes |  |
| `backup` | [backupOption](backupOption.md) | No |  |
| `bench` | [benchOption](benchOption.md) | No |  |
| `endpoints` | endpointOption[] | Yes |  |
| `networkModes` | [networkModeOption](networkModeOption.md) | No |  |
| `promote` | componentOpsOption[] | Yes |  |
| `stop` | componentOpsOption[] | Yes |  |
| `start` | componentOpsOption[] | Yes |  |
| `restart` | componentOpsOption[] | Yes |  |
| `hscale` | componentOpsOption[] | Yes |  |
| `vscale` | componentOpsOption[] | Yes |  |
| `license` | object | No |  |
| `storageExpansion` | componentOpsOption[] | No |  |
| `rebuildInstance` | componentOpsOption[] | No |  |
| `upgrade` | componentOpsOption[] | No |  |
| `metrics` | [metricsOption](metricsOption.md) | No |  |
| `dashboards` | dashboardOption[] | Yes |  |
| `logs` | logOption[] | Yes |  |
| `parameters` | parameterOption[] | Yes |  |
| `disasterRecovery` | [disasterRecoveryOption](disasterRecoveryOption.md) | No |  |
| `cdc` | cdcOption[] | No |  |
| `dataReplication` | [dataReplicationOption](dataReplicationOption.md) | No |  |
| `import` | [importOption](importOption.md) | No |  |
| `architectures` | string[] | No | List of CPU architectures supported by this engine. If not set, all architectures are supported.
 |
| `blueGreenDeployment` | [blueGreenDeploymentEngineOption](blueGreenDeploymentEngineOption.md) | No |  |
| `tls` | [engineTlsOption](engineTlsOption.md) | No |  |
| `tde` | tdeOption[] | No | Transparent data encryption configuration. |

## Nested Fields

### `license`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `required` | boolean | No | Indicate whether the current cluster requires users to input the license |
| `secretName` | string | Yes | support to refer the cluster name with variable ${clusterName} |
| `fileName` | string | Yes | the license file name |
| `components` | licenseOption[] | No | set the custom ops to update license for different components |

