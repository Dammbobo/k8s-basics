# Kubernetes Basics

This repository demonstrates core Kubernetes concepts using declarative YAML
manifests.

## Why this project
Kubernetes is the standard platform for running containerized workloads
in production. This project shows how applications are deployed and exposed
inside a cluster.

## What this project includes
- A Deployment manifest to manage application replicas
- A Service manifest to expose the application internally
- Use of labels and selectors for pod management

## Kubernetes concepts covered
- Pods
- Deployments
- Services
- Labels and selectors

## How this would be used
In a real environment, these manifests would be applied to a Kubernetes
cluster using:

```bash
kubectl apply -f manifests/
