# Gitlab All-in-One Blueprint

This blueprint deploys the proof of concept [GitLab Helm chart](https://docs.gitlab.com/charts/). This chart deploys all GitLab components to a Kubernetes cluster and is only suitable for a POC environment.

The blueprint creates the `gitlab` namespace and deploys two charts:

1. [cert-manager](https://cert-manager.io/) 
2. GitLab

