---
date: 2025-07-30
tags:
- bootstrap
---

# How to bootstrap initial node?

let us concentrate on the following topics for now:

* SoHo / self-hosting use-cases
* single node
* local discs

Possible options would be

* provide some USB/ISO-Boot-Image
    * this image should work on Bare-Metal (f.e. Intel Nuc or other x86_64)
* the installation will automatically setup our baseOS
    * can we use something like [Talos Linux](Talos Linux.md)
    * or [FlatCar](http://flatcar.org)
    * should we use some debian based OS (f.e. by using debian preseed) + [minimal kubernetes](kube.md)
* the OS will gets an IP by DHCP on primary nic
* initial k8s-setup will be run automatically
* there is a UI to login
    * did a short search, seems [devtron.ai](https://devtron.ai) looks suitable

# How to add new nodes later on?

* Maybe by using [matchbox](https://matchbox.psdn.io)?