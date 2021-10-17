# Helm repo for Metacontroller

Metacontroller does not publish a package (see [https://github.com/metacontroller/metacontroller/issues/302]).

This repo publishes their charts as an installable package.

```shell
$ helm repo add metacontroller https://orf.github.io/metacontroller-chart
$ helm install metacontroller metacontroller/metacontroller
```
