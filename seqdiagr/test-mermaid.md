# Testing Mermaid

```mermaid
sequenceDiagram
  Software Engineer->>+GitHub: Makes code changes
  GitHub-->>-CI Server: Detects new commit
  CI Server->>+Docker Registry: Builds new container image
  Docker Registry-->>-K8s Cluster: Pushes image
  K8s Cluster->>+Microservice: Deploys service on scale
  Microservice-->>-Database: Migrates data model
  Database-->>-Monitoring: Sends metrics
```
