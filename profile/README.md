# Hiconic

`Hiconic` is an `open-source` general-purpose technology for building software with paradigms worthy of the 21st century.

## For Users

### Documentation
* [Getting Started](https://docs.hiconic-os.org/tribefire.cortex.documentation/getting-started-doc/overview.html) - basic tutorials and additional information
* [Old proprietary version](https://documentation.tribefire.com/tribefire.cortex.documentation/concepts-doc/features.html) - extensive documentation of a previous version called `Tribefire`


### Tech Overview Documents
* [High-Level Overview - Slides (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/hiconic-highlevel-slides.pdf)
* [Practical Relevance for Distributed Computing (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/relevance-for-distributed-computing.pdf)
* [Projektskizze für Forschungsantrag [DE] (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/projektskizze.pdf)
* [US Patent (pdf)](https://patentimages.storage.googleapis.com/fb/43/c3/6a7041491ebdf8/US10095488.pdf)


### Downloads
* [Devrock SDK (latest)](https://api.hiconic-os.org/download-sdk.php)
* [Devrock SDK (all versions)](https://github.com/hiconic-os/maven-repo-dev/packages/2008060)


### Eclipse Plugins

Install from _Eclipse_ via `Help` / `Install New Software` with Location `https://eclipse.hiconic-os.org/beta`.

### Local Setup

`DevRock SDK` unfortunately requires a `GitHub` token to read artifacts from `GitHub`'s Maven repository:

* [generate a Personal Access Token (classic)](https://github.com/settings/tokens) with (at least) `read:packages` scope
* copy the value (something like `ghp_AbcD3FGh1jK....`)
* store it in an environment variable `GITHUB_READ_PACKAGES_TOKEN`

_NOTE: We recommend a dedicated token with only the `read:packages` scope and `no expiration` date._



## For Contributors

### Important repositories:

* [Docker Images](https://github.com/hiconic-os/hiconic.ci.docker) - Dockerfiles + Pipelines to build Docker image with `Devrock SDK` (primarily for CI)
* [Group Workflows](https://github.com/hiconic-os/hiconic.ci.workflows) - standard YAMLs used by regular groups; for now: `PRs` and `Custom Range` + `Unpublished Artifacts` builds
* [Maintenance Workflows](https://github.com/hiconic-os/hiconic.ci.maintenance) - general maintenance tasks in case something goes wrong; for now: `artifact-index cleanup`
* [This file](https://github.com/hiconic-os/.github) - the `.github` repository

### Important pipelines

* [Build Ant Tasks](https://github.com/hiconic-os/com.braintribe.devrock.ant/actions/workflows/devrock-ant-tasks.yaml)
* [Build Devrock SDK](https://github.com/hiconic-os/tribefire.extension.setup/actions/workflows/devrock-sdk.yaml)
* [Build Devrock SDK Docker Image](https://github.com/hiconic-os/hiconic.ci.docker/actions/workflows/dr-sdk.yaml)
* [Publish Documentation](https://github.com/hiconic-os/tribefire.cortex.documentation/actions/workflows/publish-doc.yaml)
