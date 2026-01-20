# About

This repository stores the ArgoCD Applications definitions and *values\*.yaml* to deploy helm charts inside the kubernetes cluster. These files are properly loaded using kustomize to make sure they are reusable accross different applications/environments.

[GitHub Actions CD Pipelines](https://github.com/ricardofukuda-org/github-actions-self-hosted-runner-workflow-test/tree/master/.github/workflows) automatically update the docker tag and *values\*.yaml* files inside this repository for further ArgoCD synchonization.

## Kubernetes Cluster
Repository with the required kubernetes cluster:

https://github.com/ricardofukuda/github-actions-self-hosted-runner-poc
