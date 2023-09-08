# upbound-spaces-gitops

Bring Upbound Managed Control Planes into your own environment with GitOps and Flux
https://blog.upbound.io/announcing-spaces


This repository holds all the necessary resources for installing Upbound Spaces in a customer's cluster environment with GitOps Flux integration enabled.
**You'll require a pull secret from an Upbound representative to access and retrieve the solution.**

please update the following files in your environment:
```bash
infrastructure/postbuild.yaml
upbound-pull-secrets/flux-system-upbound.yaml
upbound-pull-secrets/upbound-system-upbound.yaml
```