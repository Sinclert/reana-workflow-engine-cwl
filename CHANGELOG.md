# Changelog

## [0.95.0](https://github.com/Sinclert/reana-workflow-engine-cwl/compare/v0.9.3...0.95.0) (2024-05-07)


### Build

* **docker:** install correct extras of reana-commons submodule ([#261](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/261)) ([21957fe](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/21957fe41921d9c557067b2773205af6385f755b))
* **docker:** non-editable submodules in "latest" mode ([#255](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/255)) ([a6acc88](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/a6acc888a36694e3306993cfc3108752b60bd1f3))
* **python:** bump all required packages as of 2024-03-04 ([#267](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/267)) ([ed6a846](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/ed6a846eb1d8a0bf92f77906749b5853e5794114))
* **python:** bump shared REANA packages as of 2024-03-04 ([#267](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/267)) ([47155ef](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/47155ef95c4eb19642dd54a732402b2551973658))


### Bug fixes

* **progress:** handle stopped jobs ([#260](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/260)) ([bc36cb7](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/bc36cb7813a20fde685a40694af0732ded483d3a))


### Code refactoring

* **docs:** move from reST to Markdown ([#263](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/263)) ([3cf272f](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/3cf272f657cc3e0b329c6d159f5e476f06000f93))


### Continuous integration

* **actions:** update GitHub actions due to Node 16 deprecation ([#271](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/271)) ([6c04bb8](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/6c04bb81f1624ba72e667aa11318feb1f58e8fa4))
* add hadolint and flake8 linters ([624c6d9](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/624c6d98536f3af0bf9578d92d4f05f818e95093))
* added github actions workflow ([937e93f](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/937e93fa32cf3ab213042dc8a2ed9ff49ae2f55d))
* **commitlint:** addition of commit message linter ([#256](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/256)) ([021854e](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/021854e309999938cf01c31bda5ab095679e03b0))
* **commitlint:** allow release commit style ([#268](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/268)) ([ed7ad11](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/ed7ad114ccf09ab3182b4cdd49265761f44cd37b))
* **commitlint:** check for the presence of concrete PR number ([#262](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/262)) ([9a45817](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/9a45817075f98e04405845f0d49cbcd86ee95556))
* pin hadolint version ([5fbd117](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/5fbd117d05c69a12f41fec619de1b6e86a62b255))
* publish docker image after new release ([7c6c8ed](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/7c6c8ed298a076e067cc48cdb298bca84d03884c))
* **release-please:** initial configuration ([#256](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/256)) ([bcd87d1](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/bcd87d1bbaa4c9b589e4025989ff880594af2b3d))
* **release-please:** update version in Dockerfile ([#259](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/259)) ([0961257](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/096125709172e6bea1510a9fd2fdcb90299fac8b))
* remove older versions from python tests ([1d0df00](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/1d0df000ebab0c5900de1348d034429da6fb630b))
* **shellcheck:** fix exit code propagation ([#262](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/262)) ([6568b9b](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/6568b9b229141dd8dd2a261a833057358143590f))
* update all actions ([d5a36c8](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/d5a36c8aad6c9d59061ca10d9c2a959267993f8a))


### Documentation

* add .readthedocs.yaml to migrate to RTD v2 ([824abdf](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/824abdf4312f9c693fa670c4adb250da865262a9))
* add overview & local execution instructions ([dd2c8c9](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/dd2c8c9405cc5b1aac594e19f3068194e622e8ba))
* added conformance badges to the readme ([e19f294](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/e19f2944e2acd49a0acf0233a162e7386723196c))
* author ORCID links ([74faf33](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/74faf33b4495feece1ace12b2a45a65db823b196))
* **authors:** complete list of contributors ([#266](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/266)) ([2960cd9](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/2960cd9c06a8e12283822ec9fbf87aba7b9b9fb5))
* better structure ([0a03c87](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/0a03c87821557c7dd43c6e5476319560dbf3c14e))
* **conformance-tests:** update CWL conformance test badges ([#264](https://github.com/Sinclert/reana-workflow-engine-cwl/issues/264)) ([45afa2e](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/45afa2efd984fd84bbae48fde6ca663f70dd86dc))
* fixes docstrings for __init__ methods ([5aca7e8](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/5aca7e876bb81e10359a86134751a415ccdfd002))
* new logo, panel verbiage and links ([e3eaa1e](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/e3eaa1e8f4d56c53cb70bb563531cb87336db5b0))
* removes outdated dev docs & unused conf vars ([d376629](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/d37662929112563d153806635475c3d13ac6b18f))
* set default language to English ([a1a1dae](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/a1a1daef03dfa7fb088b612ae6ee1ce015d28005))
* single-page RTFD outline ([c420b27](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/c420b27107baf33ad4a424c18faf6c0dfc376042))
* update changelog ([7919fc1](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/7919fc1714200a9ca3b4c20c73fd2d596838704a))
* update CWL conformance tests instructions ([fd8ce89](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/fd8ce89ad0dd369977687f9f498e992c474d5d33))
* update information about conformance testing ([6baa2e2](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/6baa2e275e25f6c4d66fde0727f55a5b3be86a3f))


### Chores

* **master:** release 0.95.0-alpha.1 ([f528ba3](https://github.com/Sinclert/reana-workflow-engine-cwl/commit/f528ba357273d14d459b3b35722e71deb22ee9c2))

## [0.9.3](https://github.com/reanahub/reana-workflow-engine-cwl/compare/0.9.2...0.9.3) (2024-03-04)


### Build

* **docker:** install correct extras of reana-commons submodule ([#261](https://github.com/reanahub/reana-workflow-engine-cwl/issues/261)) ([21957fe](https://github.com/reanahub/reana-workflow-engine-cwl/commit/21957fe41921d9c557067b2773205af6385f755b))
* **docker:** non-editable submodules in "latest" mode ([#255](https://github.com/reanahub/reana-workflow-engine-cwl/issues/255)) ([a6acc88](https://github.com/reanahub/reana-workflow-engine-cwl/commit/a6acc888a36694e3306993cfc3108752b60bd1f3))
* **python:** bump all required packages as of 2024-03-04 ([#267](https://github.com/reanahub/reana-workflow-engine-cwl/issues/267)) ([ed6a846](https://github.com/reanahub/reana-workflow-engine-cwl/commit/ed6a846eb1d8a0bf92f77906749b5853e5794114))
* **python:** bump shared REANA packages as of 2024-03-04 ([#267](https://github.com/reanahub/reana-workflow-engine-cwl/issues/267)) ([47155ef](https://github.com/reanahub/reana-workflow-engine-cwl/commit/47155ef95c4eb19642dd54a732402b2551973658))


### Bug fixes

* **progress:** handle stopped jobs ([#260](https://github.com/reanahub/reana-workflow-engine-cwl/issues/260)) ([bc36cb7](https://github.com/reanahub/reana-workflow-engine-cwl/commit/bc36cb7813a20fde685a40694af0732ded483d3a))


### Code refactoring

* **docs:** move from reST to Markdown ([#263](https://github.com/reanahub/reana-workflow-engine-cwl/issues/263)) ([3cf272f](https://github.com/reanahub/reana-workflow-engine-cwl/commit/3cf272f657cc3e0b329c6d159f5e476f06000f93))


### Continuous integration

* **commitlint:** addition of commit message linter ([#256](https://github.com/reanahub/reana-workflow-engine-cwl/issues/256)) ([021854e](https://github.com/reanahub/reana-workflow-engine-cwl/commit/021854e309999938cf01c31bda5ab095679e03b0))
* **commitlint:** allow release commit style ([#268](https://github.com/reanahub/reana-workflow-engine-cwl/issues/268)) ([ed7ad11](https://github.com/reanahub/reana-workflow-engine-cwl/commit/ed7ad114ccf09ab3182b4cdd49265761f44cd37b))
* **commitlint:** check for the presence of concrete PR number ([#262](https://github.com/reanahub/reana-workflow-engine-cwl/issues/262)) ([9a45817](https://github.com/reanahub/reana-workflow-engine-cwl/commit/9a45817075f98e04405845f0d49cbcd86ee95556))
* **release-please:** initial configuration ([#256](https://github.com/reanahub/reana-workflow-engine-cwl/issues/256)) ([bcd87d1](https://github.com/reanahub/reana-workflow-engine-cwl/commit/bcd87d1bbaa4c9b589e4025989ff880594af2b3d))
* **release-please:** update version in Dockerfile ([#259](https://github.com/reanahub/reana-workflow-engine-cwl/issues/259)) ([0961257](https://github.com/reanahub/reana-workflow-engine-cwl/commit/096125709172e6bea1510a9fd2fdcb90299fac8b))
* **shellcheck:** fix exit code propagation ([#262](https://github.com/reanahub/reana-workflow-engine-cwl/issues/262)) ([6568b9b](https://github.com/reanahub/reana-workflow-engine-cwl/commit/6568b9b229141dd8dd2a261a833057358143590f))


### Documentation

* **authors:** complete list of contributors ([#266](https://github.com/reanahub/reana-workflow-engine-cwl/issues/266)) ([2960cd9](https://github.com/reanahub/reana-workflow-engine-cwl/commit/2960cd9c06a8e12283822ec9fbf87aba7b9b9fb5))
* **conformance-tests:** update CWL conformance test badges ([#264](https://github.com/reanahub/reana-workflow-engine-cwl/issues/264)) ([45afa2e](https://github.com/reanahub/reana-workflow-engine-cwl/commit/45afa2efd984fd84bbae48fde6ca663f70dd86dc))

## 0.9.2 (2023-12-12)

- Adds automated multi-platform container image building for amd64 and arm64 architectures.
- Adds metadata labels to Dockerfile.
- Fixes container image building on the arm64 architecture.

## 0.9.1 (2023-09-27)

- Fixes container image names to be Podman-compatible.

## 0.9.0 (2023-01-19)

- Adds support for specifying `slurm_partition` and `slurm_time` for Slurm compute backend jobs.
- Adds support for Kerberos authentication for workflow orchestration.
- Adds support for Rucio authentication for workflow jobs.
- Changes the base image of the component to Ubuntu 20.04 LTS and reduces final Docker image size by removing build-time dependencies.
- Fixes status reporting for failed jobs that were incorrectly considered successful.

## 0.8.1 (2022-02-07)

- Adds support for specifying `kubernetes_job_timeout` for Kubernetes compute backend jobs.

## 0.8.0 (2021-11-22)

- Adds support for custom workspace paths.
- Adds supoort for `cwltool` version `3.1.20210628163208`

## 0.7.6 (2021-07-05)

- Changes internal dependencies to remove click.

## 0.7.5 (2021-04-28)

- Adds support for specifying `kubernetes_memory_limit` for Kubernetes compute backend jobs.

## 0.7.4 (2021-03-23)

- Changes job command serialisation using central REANA-Commons job command serialiser.

## 0.7.3 (2021-03-17)

- Changes workflow engine instantiation to use central REANA-Commons factory.
- Changes status `succeeded` to `finished` to use central REANA nomenclature.

## 0.7.2 (2021-02-03)

- Fixes minor code warnings.
- Changes CI system to include Python flake8 and Dockerfile hadolint checkers.

## 0.7.1 (2020-11-10)

- Adds support for specifying `htcondor_max_runtime` and `htcondor_accounting_group` for HTCondor compute backend jobs.
- Fixes restarting of CWL workflows.

## 0.7.0 (2020-10-20)

- Adds pinning of all Python dependencies allowing to easily rebuild component images at later times.
- Adds option to specify unpacked Docker images as workflow step requirement.
- Adds support for handling new workflow operational options.
- Adds support for VOMS proxy as a new authentication method.
- Changes base image to use Python 3.8.
- Changes code formatting to respect `black` coding style.
- Changes documentation to single-page layout.

## 0.6.1 (2020-05-25)

- Upgrades REANA-Commons package using latest Kubernetes Python client version.

## 0.6.0 (2019-12-20)

- Allows to specify compute backend (HTCondor, Kubernetes or Slurm) and
  Kerberos authentication requirement for CWL workflow jobs.
- Upgrades cwltool to 1.0.20191022103248.
- Moves workflow engine to the same Kubernetes pod with the REANA-Job-Controller
  (sidecar pattern).

## 0.5.0 (2019-04-23)

- Makes workflow engine independent of Celery so that independent workflow
  instances are created on demand for each user.
- Replaces `api_client` module with centralised one from REANA-Commons.
- Introduces CVMFS mounts in job specifications.
- Sets default file mode creation mask to 002 so that workflows are able to
  write to shared directories for any user identity under which the workflow
  processes may be running.
- Makes docker image slimmer by using `python:2.7-slim`.
- Centralises log level and log format configuration.
- Upgrades cwltool to 1.0.20181118133959.

## 0.4.0 (2018-11-06)

- Improves AMQP re-connection handling. Switches from `pika` to `kombu`.
- Utilises common openapi client for communication with REANA-Job-Controller.
- Changes license to MIT.

## 0.3.2 (2018-09-25)

- Upgrades to latest `cwltool` (`1.0.20180912090223`).

## 0.3.1 (2018-09-07)

- Pins REANA-Commons dependency.

## 0.3.0 (2018-08-10)

- Tracks progress of workflow runs.

## 0.2.0 (2018-04-19)

- Initial public release.