# Fluentd Daemonset for Kubernetes with output plugin for Datadog

## Supported tags and respective `Dockerfile` links

### Debian

- `v0.12-debian-datadog` [(v0.12/debian-datadog/Dockerfile)][debian-datadog-dockerfile]

### Alpine Linux

- `v0.12-alpine-datadog` [(v0.12/alpine-datadog/Dockerfile)][alpine-datadog-dockerfile]

## What is Fluentd?

![Fluentd Logo](http://www.fluentd.org/assets/img/miscellany/fluentd-logo.png)

Fluentd is an open source data collector, which lets you unify the data
collection and consumption for a better use and understanding of data.

> [www.fluentd.org](http://www.fluentd.org/)


## Image versions

The following repository expose images based on Alpine Linux and Debian. For production environments we strongly suggest to use Debian images.

Fluentd versioning is as follows:

| Series | Description                         |
|--------|-------------------------------------|
| v0.12  | Stable, production ready            |
| v0.14  | Development, next stable (Q3 2017)  |

### References

[Kubernetes Logging with Fluentd][fluentd-article]

[alpine-home]: http://alpinelinux.org
[alpine-dockerhub]: https://hub.docker.com/_/alpine
[debian-dockerhub]: https://hub.docker.com/_/debian
[fluentd-article]: http://docs.fluentd.org/v0.12/articles/kubernetes-fluentd

[alpine-datadog-dockerfile]: https://github.com/jgarrouste/fluentd-datadog-kubernetes-daemonset/blob/master/docker-image/v0.12/alpine-datadog/Dockerfile
[debian-datadog-dockerfile]: https://github.com/jgarrouste/fluentd-datadog-kubernetes-daemonset/blob/master/docker-image/v0.12/debian-datadog/Dockerfile
