## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
  helm repo add devopsapp84 https://devopsapp84.github.io/helmchart-releaser
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
test` to see the charts.

To install the app01 chart:
```
    helm install app01 devopsapp84/app01
```

To uninstall the chart:
```
    helm delete app01
```

To install the app02 chart:
```
    helm install app02 devopsapp84/app02
```

To uninstall the chart:
```
    helm delete app02
```
