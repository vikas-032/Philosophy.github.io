---
layout: default
title:  "Kubernets"
date:   2026-03-09 11:29:03 +0530
categories: k8s
---
 
 Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications. The most important points to understand are its core concepts (Pods, Services, Deployments), its architecture (control plane + worker nodes), and how it ensures reliability through self-healing and scaling.

🔑 Key Kubernetes Points
1. Core Concepts
- Pod: The smallest deployable unit in Kubernetes, usually running one or more tightly coupled containers.
- Service: Provides stable networking and load balancing for Pods, ensuring they can be reached even if Pods are rescheduled.
- Deployment: Defines how applications are deployed and updated, managing replicas and rolling updates.
- ConfigMap & Secret: Store configuration data and sensitive information separately from application code.
2. Architecture
- Control Plane (Master):
- API Server: Entry point for all Kubernetes commands.
- Scheduler: Assigns Pods to nodes based on resource availability.
- Controller Manager: Ensures the desired state of the cluster is maintained.
- etcd: Distributed key-value store for cluster state.
- Worker Nodes:
- Run Pods using kubelet (agent) and kube-proxy (networking).
- Each node has a container runtime (e.g., Docker, containerd).
3. Reliability & Scaling
- Self-Healing: Automatically restarts failed containers, replaces Pods, and reschedules workloads.
- Horizontal Pod Autoscaler (HPA): Scales Pods up or down based on CPU/memory usage.
- Rolling Updates & Rollbacks: Deploy new versions without downtime and revert if issues occur.
4. Networking & Storage
- Cluster Networking: Every Pod gets its own IP; Services provide stable endpoints.
- Persistent Volumes (PV) & Persistent Volume Claims (PVC): Manage storage independent of Pods.
- Ingress: Manages external access (HTTP/HTTPS) to services.
5. Security & Configurations
- RBAC (Role-Based Access Control): Manages permissions for users and services.
- Namespaces: Logical separation of resources within a cluster.
- Secrets Management: Securely store sensitive data like passwords and tokens.





