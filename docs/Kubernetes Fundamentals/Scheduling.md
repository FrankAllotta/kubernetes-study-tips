---
layout: page
title: Scheduling
permalink: /Scheduling/
parent: Kubernetes Fundamentals
nav_order: 6
---

## Scheduling

- **Scheduling** is the process of assigning a Pod to a Node.
- Scheduling occurs when **a new Pod is created** and **has not yet been scheduled**.
- Scheduler takes into account things like **resource requirements, Pod affinity**, and **taints/tolerations** when selecting a Node.
