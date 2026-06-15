# benchmark

Benchmark APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/benchmark` | List benchmark tasks | [View](../operations/listBenchmark.md) |
| DELETE | `/api/v1/organizations/{orgName}/benchmark` | Delete benchmark tasks | [View](../operations/deleteBenchmark.md) |
| GET | `/api/v1/organizations/{orgName}/benchmark/{benchmarkId}` | Get benchmark task info | [View](../operations/getBenchmark.md) |
| POST | `/api/v1/organizations/{orgName}/benchmark/pgbench` | Create a pgbench benchmark task | [View](../operations/createPgbench.md) |
| POST | `/api/v1/organizations/{orgName}/benchmark/sysbench` | Create a sysbench benchmark task | [View](../operations/createSysbench.md) |
| POST | `/api/v1/organizations/{orgName}/benchmark/tpcc` | Create a tpcc benchmark task | [View](../operations/createTpcc.md) |
| POST | `/api/v1/organizations/{orgName}/benchmark/ycsb` | Create a ycsb benchmark task | [View](../operations/createYcsb.md) |
| POST | `/api/v1/organizations/{orgName}/benchmark/esrally` | Create an esrally benchmark task | [View](../operations/createEsrally.md) |
