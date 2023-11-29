# clusters/prd/control-plane/README.md

> **IMPORTANT**
>
> This directory and file is managed by Terraform using [github_repository_file](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/repository_file) - DO NOT edit!
>
> This directory is watched by Flux Kustomization [clusters/prd/flux/kustomizations/control-plane.yaml](../../..//clusters/prd/flux/kustomizations/control-plane.yaml) which is also managed by Terraform.
>
> Add manifests of additional control-plane components here, so they can be managed by the Flux Kustomization.

Folder for manifests deploying common services and configurations.

The control-plane is deployed before customer applications.
