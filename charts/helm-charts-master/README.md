# helm-charts
Helm charts for some famous open source projects - ready to use in your Kubernetes environment

## TL;DR

```bash
$ helm repo add rudy500 https://rudy500.github.io/helm-charts/
$ helm repo update
```

## Introduction

This repository contains various helm charts for some famous open source projects.
Goal was to create some universal charts that use the original docker images from [Docker Hub](https://hub.docker.com) instead of the modified version which Bitnami offers.


## Prerequisites

- Helm 3.x

## Adding this helm repository

To add this repository to the helm configuration:

```bash
$ helm repo add rudy500 https://rudy500.github.io/helm-charts/
```

## Using this helm repository

To install a chart from this repository (example with Redis):

```bash
$ helm install my-redis rudy500/redis
```

## Removing this helm repository

To remove the helm repository from helm configuration:

```bash
$ helm repo remove rudy500
```
