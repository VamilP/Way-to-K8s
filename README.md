# ☸️ Kubernetes: Beginner to Advanced Learning Guide

> **From Docker to Production Kubernetes Operations & CKA Exam Preparation**

Welcome! This comprehensive guide will take you from **zero Kubernetes knowledge** to **confident production cluster operations** and **CKA exam readiness**.

---

## 🎯 Learning Path

This guide is structured to build your understanding progressively:

### **Phase 1: Foundations** (Weeks 1-2)

1. **[Foundations](./FOUNDATIONS.md)** - What is Kubernetes? Why does it exist?
2. **[Architecture](./ARCHITECTURE.md)** - Deep dive into how Kubernetes works internally
3. **[API Objects](./API_OBJECTS.md)** - Understanding kubectl, YAML, and the API

### **Phase 2: Core Concepts** (Weeks 3-4)

4. **[Pods & Workloads](./PODS_WORKLOADS.md)** - Deployments, StatefulSets, Jobs
2. **[Networking](./NETWORKING.md)** - Services, DNS, CNI, Ingress
3. **[Storage](./STORAGE.md)** - Volumes, PVs, PVCs, StorageClasses

### **Phase 3: Configuration & Management** (Weeks 5-6)

7. **[Config & Secrets](./CONFIG_SECRETS.md)** - ConfigMaps, Secrets, environment variables
2. **[Scheduling & Resources](./SCHEDULING.md)** - Resource limits, QoS, affinity, taints
3. **[Security & RBAC](./SECURITY.md)** - Authentication, authorization, RBAC, network policies

### **Phase 4: Operations** (Weeks 7-8)

10. **[Observability & Troubleshooting](./OBSERVABILITY.md)** - Logs, metrics, debugging
2. **[Cluster Maintenance](./MAINTENANCE.md)** - Upgrades, backups, HA, disaster recovery
3. **[Real-World Project](./PROJECT.md)** - Production-like application deployment

### **Phase 5: Mastery** (Week 9+)

13. **[Common Mistakes](./COMMON_MISTAKES.md)** - What to avoid in production
2. **[Mental Models](./MENTAL_MODELS.md)** - How Kubernetes thinks vs humans

---

## 🚀 Quick Start

**Prerequisites:**

- ✅ Docker basics (see `../Docker/` guide)
- ✅ Basic Linux command line
- ✅ Basic networking concepts

**Getting Started:**

1. Start with [Foundations](./FOUNDATIONS.md)
2. Follow the learning path sequentially
3. Complete all hands-on labs
4. Practice with the [Real-World Project](./PROJECT.md)

---

## 📚 What You'll Learn

By completing this guide, you will:

- ✅ Understand **why Kubernetes exists** and what problems it solves
- ✅ Master **Kubernetes architecture** and internal components
- ✅ Deploy and manage **production workloads** confidently
- ✅ Understand **Kubernetes networking** from first principles
- ✅ Manage **storage, configs, and secrets** securely
- ✅ Implement **RBAC** and security best practices
- ✅ **Debug and troubleshoot** cluster issues effectively
- ✅ Prepare for the **CKA (Certified Kubernetes Administrator)** exam
- ✅ Build a **mental bridge** from Docker to Kubernetes

---

## 🧪 Learning Approach

Each section includes:

- 📖 **Conceptual explanations** (beginner-friendly)
- 🎨 **Visual diagrams** (ASCII/Markdown)
- 💻 **Hands-on labs** with YAML manifests
- 🔧 **kubectl commands** with expected outputs
- ⚠️ **Common mistakes** and how to avoid them
- 🎯 **CKA exam tips** where applicable

---

## 🎓 CKA Exam Preparation

This guide maps to **CKA exam objectives**:

- ✅ Cluster architecture, installation & configuration (25%)
- ✅ Workloads & scheduling (15%)
- ✅ Services & networking (20%)
- ✅ Storage (10%)
- ✅ Troubleshooting (30%)

Each section includes **exam tips** and **time-saving tricks**.

---

## 📖 Table of Contents

1. [Foundations](./FOUNDATIONS.md) - What is Kubernetes?
2. [Architecture](./ARCHITECTURE.md) - Control Plane & Worker Nodes
3. [API Objects](./API_OBJECTS.md) - kubectl, YAML, Resources
4. [Pods & Workloads](./PODS_WORKLOADS.md) - Deployments, StatefulSets, Jobs
5. [Networking](./NETWORKING.md) - Services, DNS, CNI, Ingress
6. [Storage](./STORAGE.md) - Volumes, PVs, PVCs
7. [Config & Secrets](./CONFIG_SECRETS.md) - ConfigMaps, Secrets
8. [Scheduling & Resources](./SCHEDULING.md) - Limits, QoS, Affinity
9. [Security & RBAC](./SECURITY.md) - Authentication, Authorization
10. [Observability](./OBSERVABILITY.md) - Logs, Metrics, Debugging
11. [Maintenance](./MAINTENANCE.md) - Upgrades, Backups, HA
12. [Real-World Project](./PROJECT.md) - Production Application
13. [Common Mistakes](./COMMON_MISTAKES.md) - What to Avoid
14. [Mental Models](./MENTAL_MODELS.md) - How Kubernetes Thinks

---

## 🛠️ Setup Your Learning Environment

### Option 1: Local Kubernetes (Kind/Minikube)

```bash
# Install Minikube (recommended for beginners)
# Windows: choco install minikube
# macOS: brew install minikube
# Linux: See https://minikube.sigs.k8s.io/docs/start/

minikube start
kubectl get nodes
```

### Option 2: Cloud Kubernetes (GKE/EKS/AKS)

```bash
# After creating a cluster in your cloud provider
kubectl get nodes
```

### Option 3: Playground (No Installation)

- [Kubernetes Playground](https://labs.play-with-k8s.com/)
- [Killercoda](https://killercoda.com/)

---

## 💡 How to Use This Guide

1. **Read sequentially** - Each section builds on previous knowledge
2. **Complete all labs** - Hands-on practice is essential
3. **Draw diagrams** - Visualize concepts yourself
4. **Experiment** - Break things and fix them
5. **Review** - Revisit concepts as you progress

---

## 🎯 Success Metrics

You'll know you're ready when you can:

- ✅ Explain Kubernetes architecture to someone else
- ✅ Deploy a multi-tier application with networking
- ✅ Debug a pod crash loop
- ✅ Configure RBAC for a team
- ✅ Troubleshoot networking issues
- ✅ Perform cluster maintenance tasks

---

## 📞 Next Steps

**Start here:** [Foundations](./FOUNDATIONS.md)

**Questions?** Each section includes troubleshooting tips and common issues.

**Ready for production?** Complete the [Real-World Project](./PROJECT.md) to validate your skills.

---

**Let's begin your Kubernetes journey! 🚀**
