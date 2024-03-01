---
layout: page
title: Kubernetes Components
permalink: /Kubernetes Components/
parent: Kubernetes Fundamentals
nav_order: 3
---

## Kubernetes Components

- **Worker Node** - Responsible for running container workloads.
- **Control Plane** - Set of components that manage the cluster.
- **API Server** - (Control Plane Component) Center of the control plane, other components use it to communicate and interact with the cluster.
- **etcd** (Control Plane Component) Distributed object storage used by the API Server.
- **Scheduler** - (Control Plane Component) Assigns new Pods to an appropriate worker Node.
- **Controller Manager** - (Control Plane Component) Bundles several controllers, each of which provides some cluster functionality.
- **Cloud Controller Manager** - (Control Plane Component) Bundles controllers that interact with cloud provider APIs.
- **kube-proxy** - (Worker Node Component) Manages local routing rules on the Node to route network traffic to Pods.
- **kubelet** (Worker Node Component) Kubernetes agent that works with the container runtime to run containers on the Node.
- **Container Runtime** - (Worker Node Component) Software that runs containers, such as containerd or CRI-O.
- **Kubernetes CRI** - Standard interface for container runtimes. Any runtime that implements CRI should work with Kubernetes.
- kubelet no longer uses dockershim to support Docker as a container runtime, since Docker does not implement the CRI.
