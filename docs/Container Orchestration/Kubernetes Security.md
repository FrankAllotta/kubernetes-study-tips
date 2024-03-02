---
layout: page
title: Kubernetes Security
permalink: /Kubernetes Security/
parent: Container Orchestration
nav_order: 3
---

## Kubernetes Security

- **4Cs of Cloud Native Security** - Cloud, Clusters, Containers, and Code.
- **Client Certificates** - API Server uses a signed X509 client certificate to authenticate a user.
- **OpenID Connect** - Uses a **JSON Web Token (JWT)** signed by an external identity provider to authenticate a user.
- **OPA Gatekeeper** - You can create policies to limit what can be done in your cluster. Gatekeeper validates incoming requests to the API according to your policies.
- The **OPA Gatekeeper** tool exists outside of Kubernetes and can be used in other contexts.
