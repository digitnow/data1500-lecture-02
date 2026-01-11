# Testing Mermaid

```mermaid
sequenceDiagram
    participant SE as Software Engineer
    participant GH as GitHub
    participant CI as CI Server
    participant DR as Docker Registry
    participant KC as K8s Cluster
    participant MS as Microservice
    participant DB as Database
    participant MON as Monitoring

    SE->>+GH: Makes code changes
    GH-->>+CI: Detects new commit
    CI->>+DR: Builds new container image
    DR-->>+KC: Pushes image
    KC->>+MS: Deploys service on scale
    MS-->>+DB: Migrates data model
    DB-->>-MON: Sends metrics
    MON-->>-SE: Displays metrics
```
