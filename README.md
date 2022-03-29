# helm-chart-releaser-demo
Helm Chart Releaser Demo

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add helm-chart-releaser-demo https://gezimsejdiu.github.io/helm-chart-releaser-demo/
```
Let's go ahead and deploy our demo chart using the helm install command:

```console
helm install helm-chart-releaser-demo --set service.type=NodePort
```

Run the commands in the output to get a URL to access the NGINX service and pull it up in your browser.