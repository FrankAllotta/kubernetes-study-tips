---
layout: page
title: Resources for Managing Pods
permalink: /Resources for Managing Pods/
nav_order: 2
---

## Resources for Managing Pods

- A **ReplicaSet** ensures a given number of replica Pods are running at any given time.
- A **Deployment** provides declarative updates
  for ReplicaSets and Pods. It's great for scaling stateless applications, and it uses the default RollingUpdate deployment strategy for zero-downtime deployments.
- **StatefulSet** - Similar to Deployment, but for statful applications. Replica Pods have a sticky identity. Required to manually create a headless Service.
- **DaemonSet** - dynamically run replica Pods on each Node,
  or you can use filtering criteria to run it on just some Nodes. But the important thing to remember is those replicas are tied to the worker Nodes.
- **Job** - runs a containerized task to completion
  automatically retrying it if it fails.
- **CronJob** - runs Jobs repeatedly
  according to a schedule.
