# Hiconic

### Important repositories:

* [Docker Images](https://github.com/hiconic-os/hiconic.ci.docker) - Dockerfiles + Pipelines to build Docker image with `Devrock SDK` (primarily for CI)
* [Group Workflows](https://github.com/hiconic-os/hiconic.ci.workflows) - standard YAMLs used by regular groups; for now: `PRs` and `Custom Range` + `Unpublished Artifacts` builds
* [Maintenance Workflows](https://github.com/hiconic-os/hiconic.ci.maintenance) - general maintenance tasks in case something goes wrong; for now: `artifact-index cleanup`

### Important pipelines

* [Build Ant Tasks](https://github.com/hiconic-os/com.braintribe.devrock.ant/actions/workflows/devrock-ant-tasks.yaml)
* [Build Devrock SDK](https://github.com/hiconic-os/tribefire.extension.setup/actions/workflows/devrock-sdk.yaml)
* [Build Devrock SDK Docker Image](https://github.com/hiconic-os/hiconic.ci.docker/actions/workflows/dr-sdk.yaml)
* [Publish Documentation](https://github.com/hiconic-os/tribefire.cortex.documentation/actions/workflows/publish-doc.yaml)

### Other
* [Old TF documentation](https://documentation.tribefire.com/tribefire.cortex.documentation/concepts-doc/features.html)