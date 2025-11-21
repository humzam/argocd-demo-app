# ArgoCD Demo App

A simple nginx application for testing GitOps with ArgoCD.

## Components
- **Deployment**: nginx:1.25 with 2 replicas
- **Service**: ClusterIP service exposing port 80

## Usage
This app is managed by ArgoCD for GitOps workflow demonstration.

To update the app, modify the manifests in the `k8s/` directory and push to Git.