---
icon: house
---
# Welcome to scallir.de

## Here I will share my tested deployments with you!

Im running this kind of setup since years in my home-lab. Now im trying to make it available for everyone in a configurable more generic way.

Im using this project to learn more about all the technologies required to setup such stuff, but also as some kind of showcase for linkedin, headhunters and future employers.

* run your preferred services like

    * git ( [forgejo](https://forgejo.org/) )
    * ci/cd ( [argo-cd](https://argoproj.github.io/cd/) )
    * office ( [collabora](https://www.collaboraonline.com), [nextcloud](https://nextcloud.com/) )
    * smart home ( [evcc](https://evcc.io/), [home-assistant](https://www.home-assistant.io/) )
    * finance ( [firefly-iii](https://www.firefly-iii.org/) )
    * media ( [immich](https://immich.app/), [nextcloud](https://nextcloud.com/) )
    * mail & calendar ( [mailu](https://mailu.io) )
    * archive ( [piler](https://www.mailpiler.org/), [paperless-ngx](https://docs.paperless-ngx.com/) )
    * all other helm or k8s resources you want.
    * all other virtual machines you need.
        * either with [KubeVirt](https://kubevirt.io/) or [openstack](https://www.openstack.org/)

* on top of your own kubernetes

    * with lets-encrypt certificates ( [cert-manager](https://cert-manager.io/) )
    * as hyper-converged infrastructure ( [rook](https://rook.io/), [ceph](https://ceph.io), [longhorn](https://longhorn.io/) )

* on top of

    * your own hardware
    * a virtual private server
    * or within the cloud ( [AWS](https://aws.amazon.com), [GCP](https://cloud.google.com/), [Azure](https://azure.microsoft.com), ...)

All automatically kept up-to-date ( renovate ), deployed automatically (GitOps) and optionally even managed for you.

I also would like to have some kind of configuration-interface, but unsure if its an API, (Web)UI or just YAML. I will probably use [Python](https://www.python.org/), [Go](https://go.dev/) or [Rust](https://www.rust-lang.org/) to write any required glue code.

## OpenSource

All will be provided as OpenSource.

[github.com/scaliir](https://github.com/scaliir)

