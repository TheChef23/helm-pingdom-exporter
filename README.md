# Pingdom exporter

Prometheus exporter for uptime metrics exposed by the Pingdom API.

This Helm chart deploy the tool that is avaialble in this repostiry:

[jusbrasil/pingdom-exporter](https://github.com/jusbrasil/pingdom-exporter)

## TL;DR

```shell
$ git clone git@github.com:TheChef23/helm-pingdom-exporter.git
$ cd helm-pingdom-exporter
$ helm install pingdom \
  --set pingdom.api_token=[pingdom_api_key] \
  .
```

## Prerequisites

- This chart has only been tested on Kubernetes 1.18+

## Configuration

View the [values.yml](blob/main/values.yml) file for available options.
