## Design Tradeoffs

### Why Kafka?
Kafka provides durable, high-throughput ingestion and decouples data producers
from downstream consumers, enabling scalable streaming ingestion.

### Why Kafka Connect?
Kafka Connect simplifies integration between Kafka and external systems such as
Neo4j, avoiding custom consumer logic and improving reliability.

### Why Neo4j?
The data naturally forms a graph structure (locations and trips), making Neo4j
well-suited for traversal-based analytics such as PageRank and BFS.

### Why Kubernetes (Minikube)?
Kubernetes enables reproducible deployment, service isolation, and realistic
orchestration of distributed components in a local environment.
