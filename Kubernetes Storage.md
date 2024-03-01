---
layout: page
title: Storage
permalink: /Storage/
nav_order: 13
---

## Storage

- **Volume** - Provide external storage to your Kubernetes containers to store application data.
- **PersistentVolume** - Define a dynamically consumable storage resource.
- **PersistentVolumeClaim** - Binds to a PersistentVolume and allows you to mount the storage resource in a Pod.
- **Rook** - Automates storage management with self-managing, self-scaling, self-healing storage services.
- PersistentVolume **reclaim policies**:
  - **Retain** - Reclaim manually.
  - **Recycle** - Automatic reclamation via a simple data scrub.
  - **Delete** - Underlying storage resource is deleted. (Ex. S3 Bucket)
- Use `immutable: true` with ConfigMaps and Secrets to mark the data as unchangeable.
- By default, Secret data is **NOT encrypted**, just base64-encoded.
