# shared

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| DELETE | `/admin/v1/user/apikey/{keyName}` | Delete apikey | [View](../operations/deleteApikey.md) |
| PATCH | `/admin/v1/user/apikey/{keyName}` | Update apikey information | [View](../operations/patchAPIkey.md) |
| GET | `/admin/v1/user/apikeys` | Get apikeys of the authenticated user | [View](../operations/readUserApikeys.md) |
| POST | `/admin/v1/user/apikeys` | Create apikey of the authenticated user | [View](../operations/createUserApikey.md) |
| GET | `/admin/v1/organizations/{orgName}` | Get organization | [View](../operations/readOrg.md) |
| DELETE | `/admin/v1/organizations/{orgName}` | Delete organization | [View](../operations/deleteOrg.md) |
| PATCH | `/admin/v1/organizations/{orgName}` | Update organization | [View](../operations/patchOrg.md) |
| GET | `/admin/v1/organizations/{orgName}/members` | List members | [View](../operations/listOrgMember.md) |
| POST | `/admin/v1/organizations/{orgName}/members` | Add member | [View](../operations/addOrgMember.md) |
| GET | `/admin/v1/organizations/{orgName}/members/{memberId}` | Get member | [View](../operations/readOrgMember.md) |
| DELETE | `/admin/v1/organizations/{orgName}/members/{memberId}` | Delete member | [View](../operations/deleteOrgMember.md) |
| PATCH | `/admin/v1/organizations/{orgName}/members/{memberId}` | Update member role | [View](../operations/patchOrgMember.md) |
| POST | `/admin/v1/organizations/{orgName}/members/{memberId}/freeze` | freeze the member in org | [View](../operations/freezeMember.md) |
| POST | `/admin/v1/organizations/{orgName}/members/{memberId}/unfreeze` | unfreeze the member in org | [View](../operations/unfreezeMember.md) |
| GET | `/admin/v1/permissions` | List all permissions | [View](../operations/listPermissions.md) |
| GET | `/admin/v1/organizations/{orgName}/roles` | List roles of a organization | [View](../operations/listRoles.md) |
| POST | `/admin/v1/organizations/{orgName}/roles` | Create role | [View](../operations/createRole.md) |
| GET | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Get role by name | [View](../operations/getRoleByName.md) |
| DELETE | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Delete role by name | [View](../operations/deleteRoleByName.md) |
| PATCH | `/admin/v1/organizations/{orgName}/roles/{roleName}` | Update role by name | [View](../operations/updateRoleByName.md) |
| GET | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions` | List permissions of a role | [View](../operations/listRolePermissions.md) |
| POST | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch add permissions to a role | [View](../operations/batchAddRolePermissions.md) |
| DELETE | `/admin/v1/organizations/{orgName}/roles/{roleName}/permissions/batch` | Batch remove permissions from a role | [View](../operations/batchRemoveRolePermissions.md) |
| GET | `/admin/v1/organizations/{orgName}/parameters` | List parameters of an organization | [View](../operations/listOrgParameters.md) |
| POST | `/admin/v1/organizations/{orgName}/parameters` | Batch update parameters of an organization | [View](../operations/batchUpdateOrgParameters.md) |
| GET | `/admin/v1/organizations/{orgName}/parameters/{parameterName}` | Get a parameter of an organization | [View](../operations/getOrgParameter.md) |
| PATCH | `/admin/v1/organizations/{orgName}/parameters/{parameterName}` | Update a parameter of an organization | [View](../operations/patchOrgParameter.md) |
| GET | `/admin/v1/clusters` | Get cluster list | [View](../operations/listClusters.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters` | List clusters in the Org | [View](../operations/listCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters` | Create new cluster | [View](../operations/createCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/validate` | Validate cluster creation | [View](../operations/validateClusterCreation.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}` | Get cluster details | [View](../operations/getCluster.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}` | Delete cluster | [View](../operations/deleteCluster.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}` | Update cluster specified fields | [View](../operations/patchCluster.md) |
| GET | `/admin/v1/organizations/{orgName}/clustersWithDelete/{clusterID}` | Get cluster details by ID | [View](../operations/getClusterByID.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/instances` | List cluster instances | [View](../operations/listInstance.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/offlineInstances` | List offline cluster instances | [View](../operations/listOfflineInstance.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/restart` | Restart instance of cluster | [View](../operations/restartInstance.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/events` | List instance events | [View](../operations/listInstanceEvents.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/log` | Tail cluster instance container log | [View](../operations/getInstanceContainerLog.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/workloads/{workloadName}/log` | Tail cluster instance container log | [View](../operations/getClusterInstanceLog.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/endpoints` | List cluster endpoints | [View](../operations/listEndpoints.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit` | Get SQL audit log status | [View](../operations/getSqlAudit.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/sqlAudit` | Update SQL audit log status | [View](../operations/updateSqlAudit.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tde` | Get TDE status | [View](../operations/getTDE.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tde` | Enable TDE | [View](../operations/updateTDE.md) |
| GET | `/admin/v1/organizations/{orgName}/clusterTags` | Get cluster tags | [View](../operations/getTags.md) |
| DELETE | `/admin/v1/organizations/{orgName}/tags/{tagId}` | Delete tag | [View](../operations/deleteTag.md) |
| PATCH | `/admin/v1/organizations/{orgName}/tags/{tagId}` |  | [View](../operations/updateTag.md) |
| GET | `/admin/v1/organizations/{orgName}/tags` | List tags by organization name | [View](../operations/listOrgTags.md) |
| POST | `/admin/v1/organizations/{orgName}/tags` | Create cluster tags | [View](../operations/createTag.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/autohealing` | list autohealing job | [View](../operations/getAutohealing.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/metrics` | Query cluster metrics | [View](../operations/queryClusterMetrics.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/metrics` | Get instaces metrics in cluster | [View](../operations/getInstacesMetrics.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tls` | Get cluster TLS certificate | [View](../operations/getTLSCertificate.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tls` | Enable or disable cluster TLS | [View](../operations/tlsSwitcher.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist` | List IP whitelists | [View](../operations/listIPWhitelist.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist` | Create IP whitelist | [View](../operations/createIPWhitelist.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist/{ipWhitelistId}` | Delete IP whitelist | [View](../operations/deleteIPWhiteList.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/ipWhitelist/{ipWhitelistId}` | Update IP whitelist | [View](../operations/updateIPWhitelist.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/haHistory` | describe cluster HA history | [View](../operations/describeClusterHaHistory.md) |
| GET | `/admin/v1/organizations/{orgName}/events` | List events | [View](../operations/listOrgEvents.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameters` | List parameter properties of the cluster | [View](../operations/listParameterProps.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterHistories` | List parameters history of the cluster | [View](../operations/listParametersHistory.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Get cluster parameter template | [View](../operations/getClusterParameterTemplate.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Export parameter template from cluster | [View](../operations/exportParameterTemplateFromCluster.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate` | Update cluster parameter template | [View](../operations/updateClusterParameterTemplate.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}` | get the datasource | [View](../operations/getDataSourceV2.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}` | delete the datasource | [View](../operations/deleteDataSourceV2.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource` | list the datasource of a cluster | [View](../operations/listDataSourceV2.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/testDS` | test the datasource | [View](../operations/testDataSourceV2.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/createDS` | create the datasource | [View](../operations/createDataSourceV2.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/updateDS` | update the datasource | [View](../operations/updateDataSourceV2.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/query` | create a SQL query | [View](../operations/query.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/export` | Data Export | [View](../operations/DataExport.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/import` | Data Import | [View](../operations/DataImport.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/task` | Get the task progress | [View](../operations/GetTaskProgress.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/tasks` | Get the task list | [View](../operations/GetTaskList.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/databases` | list all databases of the datasource | [View](../operations/listDmsDatabases.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/schemas` | list all databases or schema of the cluster | [View](../operations/getSchemaList.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}` | list the type and number of database objects in the specified database or schema | [View](../operations/ListObjectTypesInSchema.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}` | list the all name for the specified object type | [View](../operations/ListObjectNamesByType.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/{schema}/{type}/{objectName}` | get the detail object info | [View](../operations/GetObjectInfo.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/history` | list the query History | [View](../operations/listQueryHistory.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/sqlExplain` | explain a SQL | [View](../operations/sqlExplain.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/generateDDL` | support ddl and dml operations | [View](../operations/generateDDL.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/showData` | read data of table or view | [View](../operations/showData.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/sessions` | list all session for the cluster | [View](../operations/listSessionsOld.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/session/{session}` | close the session for the cluster | [View](../operations/closeSessions.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/pod` | Query cluster pod logs | [View](../operations/queryPodLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/running` | Query cluster running logs | [View](../operations/queryRunningLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow` | Query cluster slow logs | [View](../operations/querySlowLogs.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/explain` | Explain cluster slow log SQL | [View](../operations/explainSlowLog.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates` | Query cluster slow log templates | [View](../operations/querySlowLogTemplates.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}` | Get cluster slow log template | [View](../operations/getSlowLogTemplate.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}/explain` | Explain cluster slow log template | [View](../operations/explainSlowLogTemplate.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates/{templateId}/samples` | Query cluster slow log template samples | [View](../operations/querySlowLogTemplateSamples.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/aggregate` | Aggregate cluster slow logs | [View](../operations/aggregateSlowLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/stats` | Get cluster slow log statistics | [View](../operations/getSlowLogStats.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/audit` | Query cluster audit logs | [View](../operations/queryAuditLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/error` | Query cluster error logs | [View](../operations/queryErrorLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/hits` | Query log hits histogram | [View](../operations/queryLogHits.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/reconfigure` | Update cluster configuration | [View](../operations/reconfigureCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restart` | Restart cluster | [View](../operations/restartCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance` | rebuild the instance | [View](../operations/rebuildInstance.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/rebuildInstance/availableNodes` | List available nodes for rebuilding instance | [View](../operations/listAvailableNodes.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/upgrade` | Upgrade cluster version | [View](../operations/upgradeCluster.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/upgradeableServiceVersion` | list upgraded service version of the component | [View](../operations/ListUpgradeableServiceVersion.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/volume-expand` | Expand cluster volume size | [View](../operations/clusterVolumeExpand.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/vscale` | Vertical scale cluster | [View](../operations/verticalScaleCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/hscale` | Horizontal scale cluster | [View](../operations/horizontalScaleCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/promote` | Promote cluster intance to primary | [View](../operations/promoteCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/stop` | Stop cluster | [View](../operations/stopCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/start` | Start cluster | [View](../operations/startCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/expose` | Expose cluster loadbalancer endpoint | [View](../operations/exposeCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/updateLicense` | Update the cluster license | [View](../operations/updateClusterLicense.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/custom-ops` | Create custom OpsRequest | [View](../operations/customOps.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/volumes/io-quotas` | Specify IOPS and BPS of cluster volumes | [View](../operations/specifyClusterIOQuotas.md) |
| GET | `/admin/v1/environments/{environmentName}/nodes/resourceStats` | Get resource statistics of nodes | [View](../operations/listNodesResourceStats.md) |
| GET | `/admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}` | Get backup repo | [View](../operations/getBackupRepo.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backups` | Create backup | [View](../operations/createClusterBackup.md) |
| POST | `/admin/v1/environments/{environmentName}/organizations/{orgName}/engines/{engineName}/buildBackup` | build backup object with a existing backup directory | [View](../operations/buildBackupObj.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy` | Get backup policy | [View](../operations/getClusterBackupPolicy.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy` | Update backup policy | [View](../operations/updateBackupPolicy.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/listObjectsForSelectiveBackup` | List objects tree for selective backup | [View](../operations/listObjectsTreeForSelectiveBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules` | List backup schedules | [View](../operations/listBackupSchedules.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules` | Create backup schedule | [View](../operations/createBackupSchedule.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}` | Delete backup schedule | [View](../operations/deleteBackupSchedule.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/backupSchedules/{scheduleName}` | Update backup schedule | [View](../operations/updateBackupSchedule.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}` | Get backup | [View](../operations/getBackup.md) |
| DELETE | `/admin/v1/organizations/{orgName}/backups/{backupId}` | Delete backup | [View](../operations/deleteBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}/logs` | Get backup log | [View](../operations/getBackupLog.md) |
| POST | `/admin/v1/organizations/{orgName}/backups/{backupId}/view` | view backup info | [View](../operations/viewBackup.md) |
| GET | `/admin/v1/organizations/{orgName}/backups/{backupId}/download` | Download full backup | [View](../operations/downloadBackup.md) |
| POST | `/admin/v1/organizations/{orgName}/backups/{backupId}/download` | Download multiple backup files | [View](../operations/downloadMultipleBackups.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}/serviceVersion` | list the service version of the engine | [View](../operations/ListServiceVersion.md) |
| GET | `/admin/v1/environments/{environmentName}/engines/{engineName}/availableServiceVersion` | list the service version of the engine | [View](../operations/availableServiceVersion.md) |
| GET | `/admin/v1/organizations/{orgName}/{engineName}/clusterBackupMethod` | get backup method | [View](../operations/getBackupMethod.md) |
| GET | `/admin/v1/organizations/{orgName}/clustersWithDelete/restoreTimeRange` | Get cluster restore time ragne | [View](../operations/getRestoreTimeRange.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | List restore tasks | [View](../operations/listClusterRestore.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Restore current cluster or instance | [View](../operations/doRestore.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore` | Delete restore task | [View](../operations/deleteRestoreObject.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/restore/{restoreId}/logs` | get restore workload logs of the cluster | [View](../operations/GetRestoreLog.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/markClusterRestoreCompleted` | mark cluster to restore completed, usually used when manually repairing or recovering issues | [View](../operations/markClusterRestoreCompleted.md) |
| GET | `/admin/v1/organizations/{orgName}/alerts/cluster/{clusterName}` | Check if cluster alert is disabled | [View](../operations/getClusterAlertDisabled.md) |
| PATCH | `/admin/v1/organizations/{orgName}/alerts/cluster/{clusterName}` | Set cluster alert disabled or enabled | [View](../operations/setClusterAlertDisabled.md) |
| POST | `/admin/v1/alerts/checkURL` | Batch check URLs connectivity | [View](../operations/batchCheckURLConnectivity.md) |
| GET | `/admin/v1/alerts/statistic` | alert statistic | [View](../operations/alertStatistic.md) |
| GET | `/admin/v1/engineOptions` | List all engineOptions | [View](../operations/listEngineOptions.md) |
| GET | `/admin/v1/engineOptions/{engineName}` | Get engineOption | [View](../operations/getEngineOption.md) |
| GET | `/admin/v1/engineLicenses` | List all engineLicenses | [View](../operations/listEngineLicenses.md) |
| GET | `/admin/v1/engineTypes` | List engine types | [View](../operations/listEngineTypes.md) |
| GET | `/admin/v1/environments/{environmentName}/engines` | List engines in environment | [View](../operations/listEnginesInEnv.md) |
| GET | `/admin/v1/engines/resourceConstraints` | List engine resource constraints | [View](../operations/listEngineResourceConstraints.md) |
| GET | `/admin/v1/classes` | List classes | [View](../operations/listClasses.md) |
| POST | `/admin/v1/llm/check` | check apikey available | [View](../operations/checkAPIKey.md) |
| GET | `/admin/v1/llm/models` | List available model | [View](../operations/listAvailableModel.md) |
| GET | `/admin/v1/features` | Get feature list | [View](../operations/listFeature.md) |
| GET | `/admin/v1/features/{featureName}` | Get feature | [View](../operations/readFeature.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tenants` | list all tenants for the oceanbase cluster | [View](../operations/listTenants.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}` | get tenants detail information of the oceanbase cluster | [View](../operations/getTenant.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameters` | list cluster parameters | [View](../operations/listParameters.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameter` | alter cluster parameter | [View](../operations/alterParameter.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameterHistory` | List parameters history of the Oceanbase tenant | [View](../operations/tenantParameterHistory.md) |
| GET | `/admin/v1/platformParameters/{platformParameterName}` | get platformParameter by name | [View](../operations/getPlatformParameter.md) |
| GET | `/admin/v1/organizations/{orgName}/recycleBin/clusters` | List clusters in the Recycle Bin of the Org | [View](../operations/listRecycleBinCluster.md) |
| GET | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}` | Get cluster in the Recycle Bin of the Org | [View](../operations/getRecycleBinCluster.md) |
| DELETE | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}` | Delete cluster from the Recycle Bin of the Org | [View](../operations/deleteRecycleBinCluster.md) |
| POST | `/admin/v1/organizations/{orgName}/recycleBin/clusters/{clusterName}/restore` | Restore cluster from the Recycle Bin of the Org | [View](../operations/restoreRecycleBinCluster.md) |
| GET | `/admin/v1/taskTypes` | List task types | [View](../operations/listTaskTypes.md) |
| GET | `/admin/v1/organizations/{orgName}/cluster/{clusterName}/available-relations` | list the available clusters for the organization to create the a relation | [View](../operations/listAvailableClustersForRelation.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/relations` | list the clusters that have built a relation to the specified cluster | [View](../operations/listRelatedClusters.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/relations` | create a relation between the clusters in the organization | [View](../operations/createRelation.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/relation/{target}` | delete a existed relation between the clusters in the organization | [View](../operations/deleteRelation.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers` | Get all brokers in cluster | [View](../operations/getKafkaBrokers.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Get all configs of a broker | [View](../operations/getKafkaBrokerConfigs.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/brokers/{brokerId}/configs` | Update broker config | [View](../operations/updateKafkaBrokerConfig.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Get all topics in cluster | [View](../operations/getKafkaTopics.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics` | Create new topic | [View](../operations/createKafkaTopic.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Get topic Infos | [View](../operations/getKafkaTopicInfos.md) |
| DELETE | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}` | Delete topic | [View](../operations/deleteKafkaTopic.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/brokers` | Get broker distributions of topic | [View](../operations/getKafkaTopicBrokers.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | Get partition list of topic | [View](../operations/getKafkaTopicPartitions.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/partitions` | expand topic partition | [View](../operations/expandKafkaTopicPartitions.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Get topic configuration | [View](../operations/getKafkaTopicConfig.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/configs` | Update topic configuration | [View](../operations/setKafkaTopicConfig.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups` | List consumer groups of topic | [View](../operations/listKafkaTopicConsumerGroups.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | List consumer offsets of topic | [View](../operations/listKafkaTopicConsumerOffsets.md) |
| PUT | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/consumer-groups/{groupId}/offsets` | Reset consumer offset of topic | [View](../operations/resetKafkaTopicConsumerOffset.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | List messages from topic | [View](../operations/listKafkaTopicMessages.md) |
| POST | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages` | Produce message to topic | [View](../operations/produceKafkaTopicMessage.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups` | List all consumer groups | [View](../operations/listKafkaConsumerGroups.md) |
| GET | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Get consumer group describe | [View](../operations/getKafkaConsumerGroupDescribe.md) |
| DELETE | `/admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/consumer-groups/{groupId}` | Delete consumer group | [View](../operations/deleteKafkaConsumerGroup.md) |
| GET | `/admin/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts` | list redis accounts | [View](../operations/listRedisAccounts.md) |
| POST | `/admin/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts` | create redis account | [View](../operations/createRedisAccount.md) |
| DELETE | `/admin/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | delete redis account | [View](../operations/deleteRedisAccount.md) |
| PATCH | `/admin/v1/data/redis/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update redis account | [View](../operations/updateRedisAccount.md) |
| GET | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | List RabbitMQ accounts | [View](../operations/listRabbitAccounts.md) |
| POST | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | Create RabbitMQ account | [View](../operations/createRabbitAccount.md) |
| DELETE | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete RabbitMQ account | [View](../operations/deleteRabbitAccount.md) |
| PATCH | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update RabbitMQ account password | [View](../operations/updateRabbitAccountPassword.md) |
| PUT | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | Update RabbitMQ account privileges | [View](../operations/updateRabbitAccountPrivileges.md) |
| GET | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/vhosts` | List RabbitMQ vhosts | [View](../operations/listRabbitVHosts.md) |
| GET | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/exchanges` | List RabbitMQ exchanges | [View](../operations/listRabbitExchanges.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | get engine available console | [View](../operations/getEngineAvailableConsole.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | enable console | [View](../operations/enableConsole.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/console` | disable console | [View](../operations/disableConsole.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/demo` | generate demo data | [View](../operations/generateDemoData.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/dboptions` | get database options | [View](../operations/getDatabaseOptions.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | List cluster databases | [View](../operations/listDatabases.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases` | Create cluster database | [View](../operations/createDatabase.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` |  | [View](../operations/getDatabase.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | Delete cluster database | [View](../operations/deleteDatabase.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/databases/{databaseName}` | update database config | [View](../operations/updateDatabaseConfig.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listAccounts.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createAccount.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateAccount.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/root-password` | get root account password | [View](../operations/getRootAccountPassword.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | update account privileges | [View](../operations/updateAccountPrivileges.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/lock` | Lock cluster account | [View](../operations/lockAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock` | Unlock cluster account | [View](../operations/unlockAccount.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions` | List cluster sessions | [View](../operations/listSessions.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/sessions/{session}` | Kill cluster session | [View](../operations/killSession.md) |
| GET | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | List mongodb accounts | [View](../operations/listMongoDBAccounts.md) |
| POST | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | Create mongodb account | [View](../operations/createMongoDBAccount.md) |
| DELETE | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete mongodb account | [View](../operations/deleteMongoDBAccount.md) |
| DELETE | `/admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | delete mssql account compatible with windows account | [View](../operations/deleteMssqlAccount.md) |
| PATCH | `/admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | update mssql account compatible with windows account | [View](../operations/updateMssqlAccount.md) |
| PATCH | `/admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/tde` | batch modify database tde status | [View](../operations/manageMssqlTDEDatabase.md) |
| GET | `/admin/v1/keys` | List Keys | [View](../operations/listKeys.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight` | Data source preflight check | [View](../operations/importPreflight.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/preflight/{taskId}` | Get preflight task details | [View](../operations/getImportPreflightTask.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/objects` | Query replication objects for import | [View](../operations/queryImportObjects.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import` | Query import task list | [View](../operations/listImportTask.md) |
| POST | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import` | Create import task | [View](../operations/createImportTask.md) |
| GET | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}` | Get import task details | [View](../operations/getImportTask.md) |
| DELETE | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}` | Delete import task | [View](../operations/deleteImportTask.md) |
| PATCH | `/admin/v1/organizations/{orgName}/clusters/{clusterName}/import/{id}/ops/{opsType}` | Create a import task operation | [View](../operations/updateImportTaskOps.md) |
