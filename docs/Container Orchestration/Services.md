---
layout: page
title: Services
permalink: /Services/
parent: Container Orchestration
nav_order: 5
---

## Services

- **Services** expose an application running on a set of replica Pods as a service.
- **Service Types:**
  - **ClusterIP** - Expose internally within the cluster.
  - **NodePort** - Expose externally on a port on each Node.
  - **LoadBalancer** - Expose using a cloud provider's load balancer.
  - **ExternalName** - Provide a DNS name for an external service.
- **Headless Service** - A Service with no cluster IP address.
- A **Service without a selector** requires any endpoints to be manually created.
- There are **two main service discovery methods in Kubernetes**: DNS and environment variables.
- An **Ingress** exposes and application externally and routes traffic to a Service. It can also provide additional functionality like SSL termination.
