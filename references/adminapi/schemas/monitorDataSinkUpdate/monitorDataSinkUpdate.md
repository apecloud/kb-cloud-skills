# monitorDataSinkUpdate

External Endpoint update option

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `monitorDataSinkType` | string | Yes | type of monitor data sink(logs or metrics) |
| `environmentName` | string | Yes | Name for relative Environment |
| `exporterUrl` | string | No | url for exporter(eg. url for ElasticSearch) |
| `name` | string | No | Endpoint name |
| `username` | string | No | Username |
| `password` | string | No | Password |
| `apiKey` | string | No | apiKey |
| `indexName` | string | No | indexName for ElasticSearch |

