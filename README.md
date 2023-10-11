# Helm chart project
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/mach1el-charts)](https://artifacthub.io/packages/search?repo=mach1el-charts) ![License](https://img.shields.io/github/license/mach1el/helm-charts?color=purple&style=plastic)

Easy to install applications on Kubernetes using [Kubernetes helm](https://github.com/helm/helm)


### Install Helm

Helm is a tool for managing Kubernetes charts. Charts are packages of pre-configured Kubernetes resources.

To install Helm, refer to the [Helm install guide](https://github.com/helm/helm#install) and ensure that the `helm` binary is in the `PATH` of your shell.

### Using Helm

Once you have installed the Helm client, you can deploy a Bitnami Helm Chart into a Kubernetes cluster.

Please refer to the [Quick Start guide](https://helm.sh/docs/intro/quickstart/) if you wish to get running in just a few commands, otherwise the [Using Helm Guide](https://helm.sh/docs/intro/using_helm/) provides detailed instructions on how to use the Helm client to manage packages on your Kubernetes cluster.

### Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repository as follows:

```console
helm repo add mach1el-charts https://mach1el.github.io/helm-charts
```

You can then run `helm search repo mach1el-charts` to see the charts.

### License
![License](https://img.shields.io/github/license/mach1el/helm-charts?color=purple&style=plastic)