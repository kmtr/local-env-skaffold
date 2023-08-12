# Skaffold local env

## Prerequisites

- Skaffold
- local k8s and docker solution
    - I am testing with Docker Desktop on Macbook Air M2

## Code Map

### app/*

Source codes for each application are put under this directory.

### infra

It has configurations for Skaffold and k8s folder.

[skaffold.yaml](https://skaffold.dev/docs/references/yaml/) is for Skaffold configuration.

[skaffold.env](https://skaffold.dev/docs/environment/env-file/#setting-skaffold-flags-with-environment-variables) is to set Skaffold Flags.


### infra/k8s

This directory has k8s manufest files.
