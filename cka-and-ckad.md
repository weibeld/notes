# Certified Kubernetes Administrator (CKA) Exam Curriculum

[v1.14.1](https://github.com/cncf/curriculum)

## Core concepts (19%)

- How the API works
- Kubernetes resource objects
- Kubernetes architecture
- Services

## Installation, Configuration & Validation (12%)

- Install Kubernetes
- Install Kubernetes with kubeadm (will be moved to separate competency in v1.15)
- Make cluster secure and highly-available
- Install CNI
- End-to-end tests

## Security (12%)

- Configure authentication and authorisation in API server
- Security-related resources
    - NetworkPolicy, PodSecurityPolicy, (Cluster)Role, (Cluster)RoleBinding
- Manage TLS certificates for cluster components
- Container image security
- Secrets

## Cluster (11%)

- Kubernetes version upgrades
- Node operating system upgrade
- Backup and restore solutions

## Networking (11%)

- How networking is implemented on nodes
- Ingress
- Cluster DNS
- CNI

## Troubleshooting (10%)

- Application failure
- Control plane failure
- Worker node failure
- Networking failure

## Application Lifecycle Management (8%)

- Deployment rolling updates and rollbacks
- ConfigMaps and Secrets
- Scaling
- How to develop self-healing applications

## Storage (7%)

- Volume types
- Volume access modes
- PersistentVolume
- PersistentVolumeClaim
- StorageClass

## Scheduling (5%)

- Configure Kubernetes scheduler
- Run multiple schedulers
- How resource requests and limits affect scheduling
- DaeomonSet

## Logging/Monitoring (5%)

- Monitor cluster components
- Monitor applications
- Logging architectures for cluster components and applications
    - https://kubernetes.io/docs/concepts/cluster-administration/logging/

# Certified Kubernetes Application Developer (CKAD) Exam Curriculum

[v1.14.1](https://github.com/cncf/curriculum)


## Pod design (20%)

- Labels and selectors
- Annotations
- Deployment
- Deployment rolling updates and rollbacks
- Jobs and CronJobs

## Configuration (18%)

- ConfigMaps and Secrets (how to inject into environment variables)
- SecurityContexts (`pod.spec.containers.securityContext`)
- Resource requests and limits (`pod.spec.containers.resources`)
- ServiceAccounts

## Observability (18%)

- Liveness probes and readiness probes
- Logging
    - https://kubernetes.io/docs/concepts/cluster-administration/logging/
    - https://kubernetes.io/docs/tasks/debug-application-cluster/logging-stackdriver/
    - https://kubernetes.io/docs/tasks/debug-application-cluster/logging-elasticsearch-kibana/
- Monitoring
    - https://kubernetes.io/docs/tasks/debug-application-cluster/resource-usage-monitoring/
- Degugging
    - Many sections in: https://kubernetes.io/docs/tasks/debug-application-cluster/

## Core concepts (13%)

- How the API works
- Kubernetes resource objects
- Pods

## Services & Networking (13%)

- Services
- NetworkPolicies 

## Multi-container Pods (8%)

- Understand patterns like ambassador, adapter, sidecar, etc.

## State Persistence (8%)

- How to use PVCs
