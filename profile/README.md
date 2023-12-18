# Hiconic

`Hiconic` is an `open-source` general-purpose technology for building software with paradigms worthy of the 21st century.

## For Users

* [Documentation](https://academy.modularmind.eu/enablement/getting-started/overview.html) - basic `Hiconic` intro with **tutorials** and additional information
* [Download DevrockSdk](https://github.com/hiconic-os/maven-repo-dev/packages/2008060) - points to latest `devrock-sdk-2.1.xyz.zip`

### Local Setup

`DevRock SDK` requires a `GitHub` token to read artifacts from its maven repository:

* [generate a Personal Access Token (classic)](https://github.com/settings/tokens) with (at least) `read:packages` scope
* copy the value (something like `ghp_AbcD3FGh1jK....`)
* store the value in an environment variable `GITHUB_READ_PACKAGES_TOKEN`

_NOTE: We recommend a dedicated token with only the `read:packages` scope and `no expiration` date._

## For Contributors

### Important repositories:

* [Docker Images](https://github.com/hiconic-os/hiconic.ci.docker) - Dockerfiles + Pipelines to build Docker image with `Devrock SDK` (primairly for CI)
* [Group Workflows](https://github.com/hiconic-os/hiconic.ci.workflows) - standard YAMLs used by regular groups; for now: `PRs` and `Custom Range` + `Unpublished Artifacts` builds
* [Maintenance Workflows](https://github.com/hiconic-os/hiconic.ci.maintenance) - general maintenance tasks in case something goes wrong; for now: `artifact-index cleanup`
* [Documentation](https://gitlab.com/modularmindlabs/opentf-academy/enablement) - still in GitLab :(
* [This file](https://github.com/hiconic-os/.github) - the `.github` repository

### Important pipelines

* [Build Ant Tasks](https://github.com/hiconic-os/com.braintribe.devrock.ant/actions/workflows/devrock-ant-tasks.yaml)
* [Build Devrock SDK](https://github.com/hiconic-os/tribefire.extension.setup/actions/workflows/devrock-sdk.yaml)
* [Build Devrock SDK Docker Image](https://github.com/hiconic-os/hiconic.ci.docker/actions/workflows/dr-sdk.yaml)