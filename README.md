# Helm Charts for Managed Openshift Black Belt examples

See [/charts](charts) for a list of charts.

1. Add This Repository to your Helm

    ```bash
    helm repo add mobb https://rh-mobb.github.io/helm-charts/
    ```

1. Update your Repository

    ```bash
    helm repo update
    ```

1. Install a Chart

    ```bash
    curl -sSL https://raw.githubusercontent.com/rh-mobb/helm-charts/main/charts/rosa-federated-prometheus/files/deploy-operators.sh | bash
    helm install -n my-prometheus mobb/rosa-federated-prometheus
    ```