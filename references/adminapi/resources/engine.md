# engine

Engine APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/upgradeableServiceVersion` | list upgraded service version of the component | [View](../operations/ListUpgradeableServiceVersion.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}/serviceVersion` | list the service version of the engine | [View](../operations/ListServiceVersion.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}/availableServiceVersion` | list the service version of the engine | [View](../operations/availableServiceVersion.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}/imageUploadProgress` | get the progress of uploading image task | [View](../operations/GetUploadImageProgress.md) |
| GET | `/admin/v1/engineLicenseEntities` | List all engine license entities by license ID | [View](../operations/listEngineLicenseEntities.md) |
| GET | `/admin/v1/engineLicenseEntity` | Get an engine license entity by ID | [View](../operations/getEngineLicenseEntity.md) |
| POST | `/admin/v1/engineLicenseEntity` | Create a new engine license entity | [View](../operations/createEngineLicenseEntity.md) |
| DELETE | `/admin/v1/engineLicenseEntity` | Delete an engine license entity by ID | [View](../operations/deleteEngineLicenseEntity.md) |
| GET | `/admin/v1/engineTypes` | List engine types | [View](../operations/listEngineTypes.md) |
| GET | `/admin/v1/environments/{environmentName}/engines` | List engines in environment | [View](../operations/listEnginesInEnv.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}` | Get engine in environment | [View](../operations/getEngineByNameInEnv.md) |
| POST | `/admin/v1/environments/{environmentName}/engines/{engineName}` | Manage engine in environment | [View](../operations/engineAction.md) |
| GET | `/admin/v1/engines` | List all engines | [View](../operations/listAllEngines.md) |
| GET | `/admin/v1/engines/resourceConstraints` | List engine resource constraints | [View](../operations/listEngineResourceConstraints.md) |
| POST | `/admin/v1/engines/resourceConstraints` | Create engine resource constraint | [View](../operations/createEngineResourceConstraint.md) |
| DELETE | `/admin/v1/engines/resourceConstraints/{id}` | Delete engine resource constraint | [View](../operations/deleteEngineResourceConstraint.md) |
| PATCH | `/admin/v1/engines/resourceConstraints/{id}` | Update engine resource constraint | [View](../operations/updateEngineResourceConstraint.md) |
| POST | `/admin/v1/engineVersions` | Create engine version | [View](../operations/createEngineVersion.md) |
| DELETE | `/admin/v1/engineVersions` | Delete engine version | [View](../operations/deleteEngineVersion.md) |
| PATCH | `/admin/v1/engineVersions` | Update the specified engine version | [View](../operations/patchEngineVersion.md) |
| POST | `/admin/v1/engineVersions/disable` | Disable service version | [View](../operations/disableServiceVersion.md) |
| GET | `/admin/v1/engineVersions/{engineName}` | Get engine version list | [View](../operations/listEngineVersions.md) |
| GET | `/admin/v1/engines/{engineName}/schedulingPolicies` | List engine scheduling policies | [View](../operations/listEngineSchedulingPolicies.md) |
| PATCH | `/admin/v1/engines/{engineName}/schedulingPolicies` | Patch engine scheduling policy | [View](../operations/patchEngineSchedulingPolicy.md) |
| GET | `/admin/v1/engines/{engineName}/schedulingRules` | List engine scheduling rules | [View](../operations/listEngineSchedulingRules.md) |
| POST | `/admin/v1/engines/{engineName}/schedulingRules` | Create engine scheduling rule | [View](../operations/createEngineSchedulingRule.md) |
| DELETE | `/admin/v1/engines/{engineName}/schedulingRules/{ruleId}` | Delete engine scheduling rule | [View](../operations/deleteEngineSchedulingRule.md) |
| PATCH | `/admin/v1/engines/{engineName}/schedulingRules/{ruleId}` | Patch engine scheduling rule | [View](../operations/patchEngineSchedulingRule.md) |
| GET | `/admin/v1/environments/{environmentName}/engineOptions` | List environment engine options | [View](../operations/listEnvironmentEngineOptions.md) |
| POST | `/admin/v1/environments/{environmentName}/engineOptions` | Create environment engine option | [View](../operations/createEnvironmentEngineOption.md) |
| PUT | `/admin/v1/environments/{environmentName}/engineOption/{id}` | Update environment engine option | [View](../operations/updateEnvironmentEngineOption.md) |
| DELETE | `/admin/v1/environments/{environmentName}/engineOption/{id}` | Delete environment engine option | [View](../operations/deleteEnvironmentEngineOption.md) |
| GET | `/admin/v1/environments/{environmentName}/engineNetworkModes/supported` | Get supported network modes for engine+mode from engineOption config | [View](../operations/getEngineNetworkModeSupported.md) |
| GET | `/admin/v1/environments/{environmentName}/engineNetworkModes/options` | Get available network modes for all engines from engineOption config | [View](../operations/getEngineNetworkModeOptions.md) |
