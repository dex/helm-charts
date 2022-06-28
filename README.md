# Dex's Helm Charts

[Helm](https://helm.sh) repo for different charts which can be installed on [Kubernetes](https://kubernetes.io)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add freedns https://dex.idv.tw/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo <alias>` to see the charts.

To install the freedns-updater chart:

    helm install my-freedns-updater freedns/freedns-updater

To uninstall the chart:

    helm delete my-freedns-updater
