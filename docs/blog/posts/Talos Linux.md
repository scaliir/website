---
icon: talos
tags:
- talos linux
date: 2025-07-31
---

Took a quick look into Talos Linux to check if its suitable for this project. Feels like a great project, but maybe to complex for SoHo users.

## What is Talos?

Best described by [themselves](https://www.talos.dev/v1.10/introduction/what-is-talos/)

## Quick 1-Node-PoC

```bash
wget --timestamping curl https://factory.talos.dev/image/376567988ad370138ad8b2698212367b8edcb69b5fd68c80be1f2ec7d603b4ba/v1.10.5/metal-amd64.iso -O /var/lib/libvirt/images/metal-amd64.iso
```

* create a virtual machine with above ISO plugged in
* follow [QuickStart](https://www.talos.dev/v1.10/introduction/getting-started/)

finally you should have something like

```
NAME            STATUS   ROLES           AGE    VERSION
talos-0gk-u53   Ready    control-plane   126m   v1.34.0-beta.0
```
