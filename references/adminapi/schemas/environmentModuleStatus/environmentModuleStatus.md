# environmentModuleStatus

Status of an environment module. Enabled is only used as the desired state when creating an environment. NotInstalled, Installing, and InstallationFailed describe quick installation; Upgradeable, Upgrading, and UpgradeFailed describe quick upgrade. Upgradeable means the component is running but an ApeCloud-bundled newer version is available. Unknown means the current state could not be determined.

**Type:** enum

## Values

- `Running`
- `Updating`
- `Error`
- `Disabled`
- `Enabled`
- `NotInstalled`
- `Installing`
- `InstallationFailed`
- `Upgradeable`
- `Upgrading`
- `UpgradeFailed`
- `Unknown`
