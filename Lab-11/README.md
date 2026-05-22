# Lab 11 – Container Orchestration using Amazon EKS

## Objective
To deploy and manage containerized applications using Kubernetes on AWS EKS.

---

## Tasks Performed
- Created Kubernetes deployment using YAML configuration
- Deployed NGINX application with multiple replicas
- Verified running pods in cluster
- Scaled deployment from 2 to 4 replicas
- Deleted a pod to observe auto-recovery
- Exposed application using LoadBalancer service

---

## Key Implementation
- Deployment created with multiple pods managed by replica set 
- Scaling performed dynamically without downtime 
- Kubernetes automatically recreated deleted pod (self-healing) 
- LoadBalancer service exposed application to external users

---

## Result
Successfully deployed and managed a containerized application with scaling and fault tolerance.

---

## Learning Outcomes
- Kubernetes deployment and scaling
- Pod management and replication
- Self-healing systems
- External service exposure
