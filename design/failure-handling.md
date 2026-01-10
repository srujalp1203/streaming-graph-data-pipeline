## Failure Handling & Reliability

- Kafka provides message durability, allowing consumers to recover from failures
- Kafka Connect can resume ingestion from committed offsets
- Neo4j runs as a dedicated service within the cluster, isolated from ingestion
- Kubernetes restarts failed pods automatically

This design minimizes data loss and enables graceful recovery during component failures.
