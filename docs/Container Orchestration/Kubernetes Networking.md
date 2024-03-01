---
layout: page
title: Kubernetes Networking
permalink: /Kubernetes Networking/
parent: Container Orchestration
nav_order: 4
---

## Kubernetes Networking

- Kubernetes uses a **virtual cluster network** to allow containers to communicate transparently regardless of which Node they are on.
- The cluster Domain Name Server (DNS) allows containers to **discover Services** by hostname.
- **Network Policies** control what network traffic is allowed in the cluster network, and determine whether Pods are isolated or non-isolated.
- Pods are **non-isolated** by default. All network traffic is allowed.
- If any Network Policy selects a Pod, the Pod is **isolated**. Only traffic allowed by any Network Policy that selects the Pod is allowed.
- Isolation is **treated separately** for incoming (ingress) traffic and outgoing (egress) traffic.
