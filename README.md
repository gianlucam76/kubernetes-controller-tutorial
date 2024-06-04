[![Slack](https://img.shields.io/badge/join%20slack-%23projectsveltos-brighteen)](https://join.slack.com/t/projectsveltos/shared_invite/zt-1hraownbr-W8NTs6LTimxLPB8Erj8Q6Q)
[![License](https://img.shields.io/badge/license-Apache-blue.svg)](LICENSE)

# kubernetes-controller-tutorial
This repository offers an opinionated guide to building Kubernetes controllers. I'll share the best practices and design patterns I've found useful through maintaining open-source projects like:

1. [Kubernetes add-on controller](http://github.com/projectsveltos/addon-controller)
2. [K8s-cleaner](https://github.com/gianlucam76/k8s-cleaner)

We will be using [Kubebuilder](https://github.com/kubernetes-sigs/kubebuilder) to create new APIs and controllers.

Table of Contents:
- [CustomResourceDefinition](docs/custom-resources.md)
- [Reconciler](docs/reconciler.md)
- [Handling Long-Running Operations in Kubernetes Reconcilers](docs/long-running-jobs.md)
- [Versioning Custom Resource Definitions (CRDs) in Kubernetes](docs/multiple_versions.md)
- [Testing a Controller](docs/testing.md)