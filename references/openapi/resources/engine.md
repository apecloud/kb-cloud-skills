# engine

Engine APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/clusters/{clusterName}/upgradeableServiceVersion` | list upgraded service version of the component | [View](../operations/ListUpgradeableServiceVersion.md) |
| GET | `/api/v1/environments/{environmentName}/engines/{engineName}/serviceVersion` | list the service version of the engine | [View](../operations/ListServiceVersion.md) |
| GET | `/api/v1/engineTypes` | List engine types | [View](../operations/listEngineTypes.md) |
| GET | `/api/v1/environments/{environmentName}/engines` | List engines in environment | [View](../operations/listEnginesInEnv.md) |
| GET | `/api/v1/engines/resourceConstraints` | List engine resource constraints | [View](../operations/listEngineResourceConstraints.md) |
| GET | `/api/v1/engineLicenses` | List all engineLicenses | [View](../operations/listEngineLicenses.md) |
| GET | `/api/v1/engines/{engineName}/schedulingPolicies` | List engine scheduling policies | [View](../operations/listEngineSchedulingPolicies.md) |
| GET | `/api/v1/environments/{environmentName}/engineNetworkModes/supported` | Get supported network modes for engine+mode from engineOption config | [View](../operations/getEngineNetworkModeSupported.md) |
