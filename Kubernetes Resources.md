---
layout: page
title: Kubernetes Resources
permalink: /Kubernetes Resources/
nav_order: 1
---

## Kubernetes Resources

- A **resource** is an object of a certain type in the Kubernetes API You can list all available resource types
  in a cluster with the command:
  `    kubectl api-resources
   `
- You can get documentation for a resource type using:
  ```
  kubectl explain <resource>
  ```
- You can use an **init container** to run a task before a Pod's main container starts up.
- You can create your own custom resource types using a `CustomResourceDefinition`.
  You can create deployments with an imperative command:
  `    kubectl create deploy <name> \
    --image=<image> --replicas=<replicas>
   `
