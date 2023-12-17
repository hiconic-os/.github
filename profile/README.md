# Hiconic

`Hiconic` is an `open-source` general-purpose technology for building software with paradigms worthy of the 21st century.

## For Users

* [Documentation](https://academy.modularmind.eu/enablement/getting-started/overview.html) - Basic `Hiconic` intro with **tutorials** and additional information.
* [Download DevrockSdk](https://github.com/hiconic-os/maven-repo-dev/packages/2008060) latest `devrock-sdk-2.1.xyz.zip`
* ~~[Download DevrockSdk](https://academy.modularmind.eu/services/download-sdk)(OLD/artifactory)~~

## For Contributors

### Important repositories:

* [Docker Images](https://github.com/hiconic-os/hiconic.ci.docker) - Dockerfiles + Pipelines to build Docker image with `Devrock SDK` (primairly for CI)
* [Group Workflows](https://github.com/hiconic-os/hiconic.ci.workflows) - standard YAMLs used by regular groups; for now: `PRs` and `Custom Range` + `Unpublished Artifacts'` builds
* [Maintenance Workflows](https://github.com/hiconic-os/hiconic.ci.maintenance) - General maintenance tasks in case something goes wrong; for now: `artifact-index cleanup`.
* [Documentation](https://gitlab.com/modularmindlabs/opentf-academy/enablement) - Still in GitLab :(
* [This file](https://github.com/hiconic-os/.github) - The `.github` repository

### Important pipelines

* [Build Ant Tasks](https://github.com/hiconic-os/com.braintribe.devrock.ant/actions/workflows/devrock-ant-tasks.yaml)
* [Build Devrock SDK](https://github.com/hiconic-os/tribefire.extension.setup/actions/workflows/devrock-sdk.yaml)