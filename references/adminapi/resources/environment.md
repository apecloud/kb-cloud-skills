# environment

Environment APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/admin/v1/kubernetes/nodes` | List Kubernetes nodes | [View](../operations/listKubernetesNode.md) |
| POST | `/admin/v1/kubernetes/storageclasses` | List Kubernetes storageclass | [View](../operations/listKubernetesStorageClass.md) |
| POST | `/admin/v1/kubernetes/dns` | Get Kubernetes DNS | [View](../operations/getKubernetesDNS.md) |
| GET | `/admin/v1/environments` | List environments | [View](../operations/listEnvironment.md) |
| POST | `/admin/v1/environments` | Create environment | [View](../operations/createEnvironment.md) |
| POST | `/admin/v1/environments/preflight` | Preflight check before create Environment | [View](../operations/preflightEnvironment.md) |
| GET | `/admin/v1/environments/{environmentName}` | Get environment | [View](../operations/getEnvironment.md) |
| DELETE | `/admin/v1/environments/{environmentName}` | Delete environment | [View](../operations/deleteEnvironment.md) |
| PATCH | `/admin/v1/environments/{environmentName}` | Update environment | [View](../operations/patchEnvironment.md) |
| GET | `/admin/v1/environments/{environmentName}/statusHistory` | Get environment status history | [View](../operations/getEnvironmentStatusHistory.md) |
| GET | `/admin/v1/environments/{environmentName}/credentials` | List environment credentials | [View](../operations/listEnvironmentCredential.md) |
| POST | `/admin/v1/environments/{environmentName}/credentials` | Create environment credential | [View](../operations/createEnvironmentCredential.md) |
| GET | `/admin/v1/environments/{environmentName}/credentials/{credentialName}` | Get environment credential | [View](../operations/getEnvironmentCredential.md) |
| DELETE | `/admin/v1/environments/{environmentName}/credentials/{credentialName}` | Delete environment credential | [View](../operations/deleteEnvironmentCredential.md) |
| PATCH | `/admin/v1/environments/{environmentName}/credentials/{credentialName}` | Update environment credential | [View](../operations/patchEnvironmentCredential.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes/monitorStatus` | Get environment MetricsMonitorStats | [View](../operations/getEnvironmentMetricsMonitorStats.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes` | List Kubernetes nodes in an environment | [View](../operations/listNodes.md) |
| POST | `/admin/v1/environments/{environmentName}/nodes` | Add nodes to environment | [View](../operations/addNodes.md) |
| DELETE | `/admin/v1/environments/{environmentName}/nodes` | Delete nodes from environment | [View](../operations/deleteNodes.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/cordon` | Cordon environment node | [View](../operations/cordonEnvironmentNode.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/uncordon` | Cordon environment node | [View](../operations/uncordonEnvironmentNode.md) |
| POST | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/drain` | Drain environment node | [View](../operations/drainEnvironmentNode.md) |
| POST | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/undrain` | Undrain environment node | [View](../operations/undrainEnvironmentNode.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/maintenance/on` | Set the node to maintenance mode | [View](../operations/setNodeMaintenanceMode.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/maintenance/off` | Remove the node from maintenance mode | [View](../operations/removeNodeMaintenanceMode.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes/{nodeName}` | Get node info | [View](../operations/getNode.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes/{nodeName}/pods` | List Pod in the environment node | [View](../operations/listNodePod.md) |
| GET | `/admin/v1/environments/{environmentName}/kubeconfig` | Get environment kubeconfig | [View](../operations/getEnvironmentKubeconfig.md) |
| POST | `/admin/v1/environments/{environmentName}/kubeconfig` | update environment kubeconfig | [View](../operations/updateEnvironmentKubeconfig.md) |
| GET | `/admin/v1/environments/{environmentName}/bootstrapManifests` | Get bootstrap manifests of an environment | [View](../operations/getEnvironmentBootstrapManifests.md) |
| GET | `/admin/v1/environments/{environmentName}/status` | Get environment status | [View](../operations/getEnvironmentStatus.md) |
| GET | `/admin/v1/environments/{environmentName}/progress` | Get environment provisioning progress | [View](../operations/getEnvironmentProvisioningProgress.md) |
| GET | `/admin/v1/latestEnvModuleVersion` | Get environment module latest version | [View](../operations/getLatestEnvModuleVersion.md) |
| GET | `/admin/v1/environments/{environmentName}/nodeGroups` | List environment node groups | [View](../operations/listNodeGroups.md) |
| POST | `/admin/v1/environments/{environmentName}/nodeGroups` | Create environment node group | [View](../operations/createNodeGroup.md) |
| DELETE | `/admin/v1/environments/{environmentName}/nodeGroups/{nodeGroupName}` | Delete environment node group | [View](../operations/deleteNodeGroup.md) |
| PATCH | `/admin/v1/environments/{environmentName}/nodeGroups/{nodeGroupName}` | Patch node group | [View](../operations/patchNodeGroup.md) |
| GET | `/admin/v1/environments/{environmentName}/availableZones` | List the availability zones where the environment's nodes are located | [View](../operations/listEnvNodeZone.md) |
| POST | `/admin/v1/environmentObjectStorage` | List environment object storage | [View](../operations/listEnvironmentObjectStorage.md) |
| POST | `/admin/v1/environmentBackupRepo` | get environment backup repo | [View](../operations/getEnvironmentBackupRepo.md) |
| POST | `/admin/v1/checkKubeconfig` | check kubeconfig | [View](../operations/checkKubeconfig.md) |
| GET | `/admin/v1/environments/{environmentName}/modules` | Get environment module information in an environment | [View](../operations/getEnvironmentModuleInfo.md) |
| PATCH | `/admin/v1/environments/{environmentName}/modules` | update environment module | [View](../operations/updateEnvironmentModule.md) |
| GET | `/admin/v1/environments/{environmentName}/modules/{moduleName}/details` | Get details information for an environment module | [View](../operations/getEnvironmentModuleDetails.md) |
| GET | `/admin/v1/environments/{environmentName}/modules/{moduleName}/pods/{podName}/logs` | Get logs for an environment module pod. When no parameters other than containerName and search are provided, start streaming logs in real-time. | [View](../operations/getEnvironmentModuleLogs.md) |
| GET | `/admin/v1/environments/optional-modules` | get option environment module info | [View](../operations/getOptionalEnvironmentModules.md) |
