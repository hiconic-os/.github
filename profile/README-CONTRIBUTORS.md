# Hiconic

### Important repositories:

* [Docker Images](https://github.com/hiconic-os/hiconic.ci.docker) - Dockerfiles + Pipelines to build Docker image with `Hiconic SDK` (primarily for CI)
* [Group Workflows](https://github.com/hiconic-os/hiconic.ci.workflows) - standard YAMLs used by regular groups; for now: `PRs` and `Custom Range` + `Unpublished Artifacts` builds
* [Maintenance Workflows](https://github.com/hiconic-os/hiconic.ci.maintenance) - general maintenance tasks in case something goes wrong; for now: `artifact-index cleanup`
* [Web Resources](https://github.com/hiconic-os/web-resources) - file storage; content accessible via `https://hiconic-os.github.io/web-resources/${relative-path}`

### Important pipelines

* [Build HC Build App](https://github.com/hiconic-os/com.braintribe.devrock.cicd/actions/workflows/hc-build.yaml)
* [Build Hiconic SDK](https://github.com/hiconic-os/tribefire.extension.setup/actions/workflows/hiconic-sdk.yaml)
* [Build Hiconic SDK Docker Image](https://github.com/hiconic-os/hiconic.ci.docker/actions/workflows/hc-sdk.yaml)
* [Publish Cortex Documentation](https://github.com/hiconic-os/tribefire.cortex.documentation/actions/workflows/publish-doc.yaml)

### Downloads
* [Hiconic SDK (latest)](https://api.hiconic-os.org/dowload-latest-artifact-part.php?groupId=tribefire.extension.setup&artifactId=hiconic-sdk&type=zip)
* [Hiconic SDK (all versions)](https://github.com/hiconic-os/maven-repo-dev/packages/2152237)
* [Eclipse preferences](https://hiconic-os.github.io/web-resources/development/eclipse-preferences/hiconic-eclipse-preferences.epf) - see also the [readme](https://github.com/hiconic-os/web-resources/blob/main/development/eclipse-preferences/README.md)

### Other
* [Cortex](https://docs.hiconic-os.org/tribefire.cortex.documentation/getting-started-doc/overview.html) - tutorial for our **monolith platform**
* [Eclipse plugins](https://eclipse.hiconic-os.org/documentation/com.braintribe.devrock.eclipse/devrock-tutorials/intro.html) - tutorials on our **_Eclipse_ plugins**
* [Old TF documentation](https://documentation.tribefire.com/tribefire.cortex.documentation/concepts-doc/features.html)