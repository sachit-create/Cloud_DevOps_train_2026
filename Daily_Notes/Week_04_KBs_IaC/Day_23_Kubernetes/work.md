## Day 23 - Kubernetes Introduction

### Work Completed

- Built a Docker image for a React project.
- Pushed the project code and updates to GitHub.
- Started Kubernetes basics and understood why it is used after Docker.

### Key Kubernetes Concepts Covered

- `Cluster`: A group of machines (nodes) where applications run.
- `Node`: A worker machine (VM/physical) that runs containers.
- `Pod`: The smallest deployable unit in Kubernetes (one or more containers).
- `Deployment`: Manages Pods and keeps the desired number of replicas running.
- `Service`: Exposes Pods to internal/external traffic with a stable endpoint.

### Why Kubernetes Is Relevant Here

- Docker helps build and package the React app.
- Kubernetes helps deploy, scale, and manage the app reliably.
- It supports rolling updates and self-healing when containers fail.

### Basic Commands Practiced

```bash
kubectl get nodes
kubectl get pods
kubectl get deployments
kubectl get services
kubectl describe pod <pod-name>
kubectl logs <pod-name>
```

### Next Practical Steps

- Create a Kubernetes manifest for the React app (`Deployment` + `Service`).
- Run the app in a local cluster (Minikube or kind).
- Expose the service and verify app access from browser.
