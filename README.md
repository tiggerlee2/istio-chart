```console
$ helm package helm istio
$ mv helm istio-1.3.0.tgz docs
$ helm repo index docs --url https://tiggerlee2.github.io/istio-chart
```